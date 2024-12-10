# Docker常用命令
'''
#拉取镜像	
docker pull <image_name>
#查看镜像	
docker images
#进入正在运行的容器	
docker exec -it <container_name> bash
#启动并进入新创建的容器	
docker run -it <image_name> bash
docker run -it --gpus all --name <docker name> --shm-size 8gb -v /home/:/home ubuntu:20.04 bash
#启动并进入停止的容器	
docker start <container_name> + docker exec -it <container_name> bash
#查看容器列表	
docker ps / docker ps -a
#查看容器列表
docker ps -a
'''

# 进入docker容器后，可以执行以下命令：
'''
#镜像列表	
docker images 
#拉取镜像	
docker pull <image_name>
#删除镜像	
docker rmi <image_name> 
#运行镜像	
docker run <image_name> 
#环境配置
apt update && apt install -y vim
apt install -y git
apt install -y python3 python3-pip
python3 -m pip install -r requirements.txt

#复制文件或目录	
docker cp <source_file> <container_name>:<destination_file>
#移动文件或目录	
docker mv <source_file> <destination_file> 
#查看文件内容	
docker exec -it <container_name> cat <file_name>
#查看文件大小	
docker exec -it <container_name> du -h <file_name>
#查看系统信息	
dockeruname -a
#查看CPU信息	
lscpu
#查看环境变量	
ocker env
#查看容器内的进程	
docker top <container_name>
#查看容器日志	
docker logs <container_name> 
#退出容器	
exit
#删除容器	
docker rm <container_name> 
'''

