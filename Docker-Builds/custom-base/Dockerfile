FROM centos:latest

RUN yum -y update && yum -y install rsync 
#&& yum install -y epel-release 
RUN yum install -y python36 
#RUN yum install -y python36-pip 
RUN pip3 install --upgrade pip 
RUN yum clean all && rm -rf /var/cache/yum
