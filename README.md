# yoyo-portfolio · 团队对外作品展示

GitHub Pages 静态站点，线上地址：**https://meiyanzhuang2012-tech.github.io/yoyo-portfolio/**

## 结构

```
index.html        # 单文件作品集（CSS/JS 内联，无构建步骤）
assets/           # 作品预览图（已压缩，单张 <200KB）
.nojekyll         # 关闭 Jekyll，静态资源原样发布
```

## 更新方式

1. 改 `index.html`（作品卡片、团队区块）
2. 预览图放 `assets/`，建议宽 900px、JPEG q88
3. `git add -A && git commit -m "..." && git push origin main`
4. Pages 约 30-60 秒自动重建

## 部署信息

- Pages 源：`main` 分支 `/`（根目录）
- 构建类型：legacy / branch build
- 绑定自有域名：仓库 Settings → Pages → Custom domain（需在 DNS 加 CNAME 记录）

## 注意

- 不要提交任何客户隐私数据与密钥；预览图允许公开。
- 页面无外部依赖（不引 CDN），离线可用，首屏体积小。
