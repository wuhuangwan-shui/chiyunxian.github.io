# 2026 软科中国大学排名 · 985 / 211 / 双一流

全国 985、211、双一流高校完整名单与 2026 软科排名数据展示。

## 在线访问

部署到 GitHub Pages 后可通过如下地址访问：

```
https://<你的GitHub用户名>.github.io/<仓库名>/
```

## 本地预览

```bash
python -m http.server 8080
```

然后打开 http://localhost:8080/

## 部署步骤

1. 在 GitHub 新建一个公开仓库，例如 `ruankao2026`。
2. 将本目录下所有文件推送到仓库 `main` 分支：
   ```bash
   git init
   git add .
   git commit -m "init"
   git branch -M main
   git remote add origin https://github.com/<你的GitHub用户名>/<仓库名>.git
   git push -u origin main
   ```
3. 进入仓库 **Settings → Pages → Build and deployment**，选择 **GitHub Actions**。
4. 等待 Actions 运行完成，即可通过 Pages 链接访问。

## 功能

- 列表视图：按 2026 软科排名展示高校，支持筛选 985 / 211 / 双一流、搜索、排序
- 地图分布：中国地图展示各省高校数量，点击省份显示详情
- 离线可用：`echarts.min.js` 已本地化，地图 GeoJSON 已嵌入页面
