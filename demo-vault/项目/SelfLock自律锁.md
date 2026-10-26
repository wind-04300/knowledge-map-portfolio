# SelfLock自律锁

> 第 2 层 · 项目卡。

## 一句话

在屏幕上划三角形"魔法阵"触发锁屏的自律 App，锁屏期间内嵌视频，播完自动解锁。

## 用到的知识点（第 3 层）

- [[GitHub-Actions云端编译]] —— 低配电脑不跑 Android Studio，APK 云端生成
- [[Selenium自动化]] —— 不是本项目的，但调试思路相通

## 状态

- A/B 双协议确认：A=开启自律锁，B=我划错了（反悔）
- 走 GitHub Actions 云端编译路线，APK 装真机验证
