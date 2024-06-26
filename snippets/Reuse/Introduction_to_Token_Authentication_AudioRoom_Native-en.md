鉴权是指验证用户是否拥有访问系统的权限，来避免因权限控制缺失或操作不当引发的安全风险问题，ZEGO 通过 Token（包括基础鉴权 Token 和权限认证 Token） 对用户进行鉴权。

基础鉴权 Token 指的是开发者在登录房间前必须通过 setCustomToken 接口将 Token 传给 SDK，来验证用户的合法性。

权限认证 Token 指的是为了进一步提高安全性开放了房间 ID 和推流 ID 这两个权限位，可以验证登录房间的 ID 和推流 ID。

房间 ID 和推流 ID 权限位的一般使用场景如下：

- 房间有普通房间和会员房间的区别，需要控制非会员用户登录会员房间。
- 语聊房中，需要控制推流用户和麦上用户的一致，防止“幽灵麦”现象，即在房间里听到了非麦上用户声音的情况。
- 狼人杀等发言游戏，需要防止应用被黑客破解之后，黑客可以使用其他用户 ID 登录同一房间，获取到游戏进行的信息进行作弊，影响正常用户的游戏体验。
