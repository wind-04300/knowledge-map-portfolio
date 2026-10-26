# GitHub-Actions云端编译

> 第 3 层 · 知识点。

## 结论

- 把 `.github/workflows` 里的编译配置推上 GitHub，服务器代你跑 gradle，产出 APK 可直接下载
- 低配电脑的救星：本机 7.6GB 内存跑不动 Android Studio，云端编译零占用

## 踩坑记录

- `local.properties` 含本机路径，**必须排除在仓库外**（用 `local.properties.example` 做模板）
- 编译失败九成是中文注释/变量引发编码问题，统一 UTF-8 无 BOM

## 被谁使用

- [[SelfLock自律锁]]
