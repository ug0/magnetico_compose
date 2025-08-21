# 启动说明

## 启动服务

1. **克隆并进入本目录，确保相关命令均在本项目目录下执行**

2. **（可选）编辑 `.env` 文件**
   你可以添加编辑 `.env` 文件，设置 `MAGNETICO_PORT=XXXX` 环境变量来自定义端口。

3. **启动服务**
   使用以下命令启动所有服务：
   ```bash
   docker compose up
   ```

   或者启动服务在后台运行
   ```bash
   docker compose up -d
   ```

4. **访问服务**
   默认情况下，`magnetico` 服务会暴露在宿主机的 8080 端口（或通过环境变量`MAGNETICO_PORT`修改端口）。可通过浏览器访问 http://localhost:8080

## 停止服务

- 如需停止服务，可运行：
  ```bash
  docker compose down
  ```
