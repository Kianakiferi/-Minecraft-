# Minecraft
Mine Minecraft Servers Codes

//建立一个screen
screen

//启动 Mcsmanager 面板 /root/mcsmanager
npm start 

node -v

https://github.com/Suwings/MCSManager


### Minecraft Overviewer
http://docs.overviewer.org/en/latest/

cd D:\Game\Minecraft - overviewer-0.15.30
overviewer.exe "saves\world" Maps
//        地图路径    输出路径
可能花费几小时，1GB地图输出3GB文件


### 阿里云ECS 文件转移至 OSS
https://blog.csdn.net/weixin_36171533/article/details/83657732

//服务器下载太慢了，影响服务器，OSS下载飞快

在服务器安装ossutil

./ossutil config -e oss.aliyuncs.com -i YourAccessKeyID -k YourAccessKeySecret
生成的配置文件在/root/.ossutilconfig

上传单个文件：
cd "ossutil文件所在目录"
./ossutil cp world.zip oss://kianakiferi

上传文件夹：
cd "ossutil文件所在目录"
./ossutil cp -r world oss://kianakiferi
