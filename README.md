在 Docker 中运行一个名为 "sanbing666/speedtest" 标签 "latest" 的容器，并执行速度测试。这个容器会使用宿主机的网络模式（--net=host），这意味着容器内的网络与宿主机是相同的，可以访问宿主机的网络接口。"-it" 标志表示要以交互模式运行容器，并且当容器退出时立即删除 (--rm)。

`docker run -it --rm --net=host sanbing666/speedtest:latest`
