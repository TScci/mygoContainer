## 源项目地址：[wangwc18/mygoFlaskProject](https://github.com/wangwc18/mygoFlaskProject)

## 本分支添加 [容器化部署](https://github.com/TScci/mygoContainer/blob/dev/README.md#%E5%AE%B9%E5%99%A8%E5%8C%96%E9%83%A8%E7%BD%B2) 方案

## 容器化部署

   ```
   mkdir mygo && cd mygo
   mkdir vedio
   docker pull tscci/mygoflaskproject:amd64
   docker-compose up -d
   ```

   - 可选异构镜像标签 `:arm64`、`:i386`
   - 容器读取 `~/mygo/vedio` 文件夹下的.mp4文件作为视频源
