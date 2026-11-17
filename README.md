# 889-product-images

889 / 699 产品图云端托管，供亚马逊 listing 批量上传使用。

- 47 张图片，ASCII 文件名，位于 `images/`
- 主链接：`https://cdn.jsdelivr.net/gh/q177010899a1a7-ship-it/889-product-images@main/images/<文件名>`
- 备用链接：`https://raw.githubusercontent.com/q177010899a1a7-ship-it/889-product-images/main/images/<文件名>`
- 已逐条实测：HTTP 200、Content-Type `image/jpeg` / `image/png`、返回真实图片字节、无跳转

新增图片后 push 到 main 分支，URL 立即生效；建议只增不删，避免已上架 listing 重新提交时抓不到图。
