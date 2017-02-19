FROM oysteinjakobsen/armv7-oracle-java8
#FROM anapsix/alpine-java
MAINTAINER Virtuosys 
COPY dev1_runnable.jar /home/dev1_runnable.jar
COPY device.cfg /home/device.cfg
CMD ["java","-jar","/home/dev1_runnable.jar","/home/device.cfg"]
