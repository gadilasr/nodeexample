FROM gadilasr/centos-jenkins:latest

ENV LANG=en_US
RUN yum install -y yum-plugin-ovl && yum -y upgrade \
 && yum reinstall -y glibc-common \
 && yum reinstall -y glibc \
 && yum clean all


RUN  rm -rf /tmp/* \
 && rm -rf /var/log/* \
# && rm -rf /var/cache/yum/* \
# && rm -rf /boot 
