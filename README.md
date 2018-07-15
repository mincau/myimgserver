# myimgserver
基于 imageserver 的图片服务,可监听指定目录，指定端口，指定图片的最大宽高,缓冲区大小

运行：`imageserver -dir ./upload`

## 参数
  -cache int
        缓存大小 (default 134217728)
  -dir string
        图片目录 (default "upload")
  -http string
        监听端口 (default ":8080")
  -maxh int
        最大高度 (default 2048)
  -maxw int
        最大宽度 (default 2048
