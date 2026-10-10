# 半导体量测技术日报

面向膜厚测量、白光干涉、晶圆缺陷、SiC 应力、厚度 / TTV 与 Fizeau 面型检测的中文技术日报网站。

## 网站
https://tifanic.github.io/semiconductor-metrology/

## 启用 GitHub Pages
仓库 Settings → Pages → Build and deployment → Source 选择 **GitHub Actions**。此后 main 分支每次更新会触发部署。

## 发布简报
创建 `reports/YYYY-MM-DD.html`，并在 `reports/index.json` 中按日期倒序添加：

```json
[{"date":"2026-10-11","title":"半导体量测技术日报｜2026-10-11","summary":"本期技术亮点","path":"reports/2026-10-11.html"}]
```

GitHub Pages 只负责部署仓库内容，不会自动读取 ChatGPT 已安排任务输出。无人值守的每日内容生成需要另行配置内容生产服务、密钥和调度。切勿将密钥提交到仓库。微信内置浏览器及中国大陆网络的可访问性需实际测试。
