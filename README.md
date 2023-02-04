# Qbittorrent-Nox
窗口运行安装
```
apt install screen
```
再安装
```
apt update && apt upgrade
sudo apt-get install qbittorrent-nox
```
窗口运行
```
screen -S VV
sudo qbittorrent-nox
```
ctrl+A+D，从VV退出
#删除窗口
```
 screen -S VV -X quit
```
