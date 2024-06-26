## 功能简介

同一个用户可以同时加入多个房间，并同时在多个房间内推流、拉流、发送实时消息和接收消息回调。


<div class="mk-hint">

- ZEGO Express SDK 从 2.9.0 版本开始支持该功能。
- 本功能默认不开启，如需使用，请联系 ZEGO 技术支持开通相关权限。
- 本功能开启后，默认支持最多同时加入 5 个房间，如果您有更多需求，请联系 ZEGO 技术支持提供处理。
</div>


### 应用场景

本功能可以隔离多个房间的消息及回调，实现更灵活的连麦业务。ZEGO 推荐用于跨房间连麦和在线教育的超级小班场景。

- 跨房间连麦

    主播 A 与主播 B 进行跨房间连麦，主播 A 可以通知房间 A 中所有观众登录主播 B 的房间进行拉流，主播 B 同样可以通知房间 B 中所有观众登录主播 A 的房间进行拉流。


- 超级小班

    老师进入大班房间推流，学生都登录大班房间拉流，同时登录小组房间与同组学生讨论和连麦。助教老师登录小组房间维持课堂秩序或解答学生问题。















