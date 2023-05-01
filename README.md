YesPlayMusic 原项目提供的 Dockerfile 构建并上传至阿里云，网络不好时用()，未做修改

docker run -d --name yesplaymusic -p 3000:80 --pull registry.cn-hangzhou.aliyuncs.com/zipated/yesplaymusic

按需自行修改端口