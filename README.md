# yes-lab-homework
## ROS Noetic 安装步骤
1. 配置Ubuntu软件源，更换国内清华镜像源，解决下载网络超时问题。
2. 添加ROS软件源，导入密钥，更新软件列表。
3. 执行安装命令安装ros‑noetic‑desktop‑full。
4. 在 ~/.bashrc 写入环境变量，执行source生效。
5. 打开3个终端依次运行：
roscore
rosrun turtlesim turtlesim_node
rosrun turtlesim turtle_teleop_key
控制小乌龟移动，完成仿真测试。

## 遇到的问题以及解决办法
1. 软件下载网络报错、连接失败：更换清华国内镜像源，下载速度恢复正常。
2. 打不开多个终端窗口：使用终端标签页分开运行三条指令。
3. 小乌龟窗口不显示、闪退：运行顺序出错，必须先启动roscore，再启动海龟画面，最后键盘控制节点。
4. GitHub网页上传文件加载卡顿：国内网络不稳定，小文件正常上传，视频上传较慢。
