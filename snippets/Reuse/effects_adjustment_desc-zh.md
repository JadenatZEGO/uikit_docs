游戏本身会存在三类提示效果，包括：
- 音乐：在游戏过程中循环播放的声音，通常是游戏的背景音乐。
- 音效：在游戏过程中短暂播放的声音，例如发牌声、掌声等。
- 震动。

以上三种效果，均有两种调节方式：
- 在游戏 UI 上进行调整。在游戏过程中，玩家可以在游戏 UI 上调整上述提示效果，例如当玩家在安静的环境中希望关闭音乐、音效和震动等。
- 调用 ZEGO MiniGameEngine SDK 的 API 进行调整。基于游戏场景，业务侧可以主动调节音量，例如当用户在游戏大厅玩游戏时，您的 App 可以默认开启音乐音效等，但是当用户在语聊房或用户需要开麦说话的场景下，您的 App 可以默认关闭音乐音效或降低音量等。

本文档主要说明如何调用 ZEGO MiniGameEngine SDK 的 API 进行调整音乐、音效和震动效果。







