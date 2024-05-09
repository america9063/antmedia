# antmedia ubuntu 22 VERSION ENTERPRISE
sudo apt-get update
wget https://raw.githubusercontent.com/ant-media/Scripts/master/install_ant-media-server.sh -O install_ant-media-server.sh  && chmod 755 install_ant-media-server.sh
sudo ./install_ant-media-server.sh -l (AMS2c366f350d82534ae92573bdcxxx) (LICENCIA KEYS)
cd /usr/local/antmedia/ && sudo ./enable_ssl.sh (free ssl)  /  Custom ssl (cd /usr/local/antmedia/ && sudo ./enable_ssl.sh -d domain.com)
-----RESULT--
 https://ams-XXX.antmedia.cloud:5443/ ACCESO A WEB

# antmedia ubuntu 22 VERSION comunnity
sudo ./install_ant-media-server.sh
