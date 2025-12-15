# vps-Argo一键xray脚本

声明：本仓库仅为自用备份，不适合别人使用，非开源项目，请勿擅自使用与传播，否则责任自负

####  特点

支持多种协议选择，支持哪吒，argo等


####  复制下面命令之一即可
========================================
```
bash -c "$(curl -sL https://raw.githubusercontent.com/dsadsadsss/vps-argo/main/install.sh)"
```
```
bash -c "$(wget -qO- https://raw.githubusercontent.com/dsadsadsss/vps-argo/main/install.sh)"
```
```
curl -sL https://raw.githubusercontent.com/dsadsadsss/vps-argo/main/install.sh -o install.sh && chmod +x install.sh && ./install.sh
```
```
wget -O install.sh https://raw.githubusercontent.com/dsadsadsss/vps-argo/main/install.sh && chmod +x install.sh && ./install.sh
```
========================================

下面为自用版本：
```
bash -c "$(curl -sL https://raw.githubusercontent.com/dsadsadsss/vps-argo/main/install2.sh)"
```
```
bash -c "$(wget -qO- https://raw.githubusercontent.com/dsadsadsss/vps-argo/main/install2.sh)"
```
```
curl -sL https://raw.githubusercontent.com/dsadsadsss/vps-argo/main/install2.sh -o install2.sh && chmod +x install2.sh && ./install2.sh
```
```
wget -O install2.sh https://raw.githubusercontent.com/dsadsadsss/vps-argo/main/install2.sh && chmod +x install2.sh && ./install2.sh
```
========================================

下面为ssh命令中使用的脚本，支持如ser00,哪吒面板中等容器使用，无交互一键命令：

```
https://github.com/dsadsadsss/one-key-xray.git
```
# 免责声明:

本仓库仅为自用备份，非开源项目，因为需要外链必须公开，但是任何人不得私自下载, 如果下载了，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权。 

如果你使用本仓库文件，造成的任何责任与本人无关, 本人不对使用者任何不当行为负责。


### xray-sb

#### 一键部署三协议,无需登录面板，体验不一样的快感

#### SSH登陆后执行

带哪吒和临时隧道的：
```
NSERVER='' NKEY='' SUB_NAME='vps' XIEYI='vms' bash <(curl -Ls https://dl.argo.nyc.mn/ser.sh)
```
带哪吒和固定隧道的：
```
NSERVER='' NKEY='' SUB_NAME='vps' TOK='' DOM='' XIEYI='vms' bash <(curl -Ls https://dl.argo.nyc.mn/ser.sh)
```
参数解释:

NSERVER 哪吒服务器，v1格式：服务器地址:端口

NKEY  哪吒密钥

SUB_NAME 节点名称

TOK 固定隧道token  

DOM 隧道域名 

XIEYI 节点类型，可选vls,vms，rel,socks,tuic,hy2,3x，ech等,默认为vms，3x包含vmess.tuic,hy2三协议



#### 推荐一个抱脸保活项目:

https://github.com/dsadsadsss/serv00-baohuo.git

#### 其他平台通用脚本

https://github.com/dsadsadsss/java-wanju.git

