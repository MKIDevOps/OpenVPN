# OpenVPN Access Server With Unlimited Licence

Server Required : Centos 7 x86_64.

Login As root and Run it:

yum install wget

then,

wget https://github.com/MKIDevOps/openvpn/master/centos7.sh && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh
