# Host environment
Windows 10, WSL2, ubuntu 20.04

# Apache Maven 3.6.3
Maven home: /usr/share/maven
Java version: 11.0.14.1, vendor: Ubuntu, runtime: /usr/lib/jvm/java-11-openjdk-amd64
Default locale: en, platform encoding: UTF-8
OS name: "linux", version: "5.10.16.3-microsoft-standard-wsl2", arch: "amd64", family: "unix"

# JDK verson 11
openjdk 11.0.14.1 2022-02-08
OpenJDK Runtime Environment (build 11.0.14.1+1-Ubuntu-0ubuntu1.20.04)
OpenJDK 64-Bit Server VM (build 11.0.14.1+1-Ubuntu-0ubuntu1.20.04, mixed mode)

# build without test
mvn package -Dmaven.test.skip=true
