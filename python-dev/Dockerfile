From centos:centos7
MAINTAINER Ben Rich richbg@gmail.com

RUN yum -y install epel-release
RUN yum -y install gcc glibc 
RUN yum -y install python python-devel python-crypto python-gssapi python-pip
RUN yum -y install wget git

RUN cd /src; pip install

RUN pip install --upgrade pip 
RUN pip install pymongo 
RUN pip install paramiko
RUN pip install xmlrunner
RUN pip install pyaml
RUN pip install requests 
