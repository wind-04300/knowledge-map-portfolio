# Selenium自动化

> 第 3 层 · 知识点。

## 结论

- Selenium 驱动 Edge 浏览器模拟真人操作，适合"重复次数多、规则固定"的网页任务
- 脚本 + 显式等待（WebDriverWait）比 sleep 稳定十倍

## 踩坑记录

- Windows 中文系统默认 GBK 编码，读写文件统一声明 `encoding="utf-8"`
- 选择器优先用 id，其次 CSS，别迷信 XPath 绝对路径——页面一改就断

## 被谁使用

- [[学习成长]] · [[SelfLock自律锁]]（调试思路相通）
