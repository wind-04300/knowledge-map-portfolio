# SelfLock工程路径

> 第 4 层 · 指路牌 ｜ 项目：[[SelfLock自律锁]]

## 结构

```
…\projects\selflock\
├── app\src\main\java\…\  手势识别 / 锁屏服务
├── app\build.gradle.kts    版本号在这里改
└── .github\workflows\      云端编译配置
```

## 关联知识点

- [[GitHub-Actions云端编译]] → `.github/workflows/`
- [[无障碍权限保活]] → 锁屏服务的权限配置
- [[固件烧录与COM口]] → 真机安装调试

## 版本号规则

改完代码必须同时递增 `versionCode`，否则手机会拒绝覆盖安装。
