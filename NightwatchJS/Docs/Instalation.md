# NightwatchJS installation

## Machine characteristics

> * Fedora 24
> * Java >= 8
> * NodeJS >= 6.9.0
> * npm >= 3.10.9
> * nightwatch 
> * webdriver-manager
> * 2 cores
> * 2GB RAM
> * Internet acces

## Install Java 8 JRE

first you have to change to your home directory and download the Oracle 8.

``` 
su root
cd ~
wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" \
"http://download.oracle.com/otn-pub/java/jdk/8u60-b27/jre-8u60-linux-x64.rpm"
```
### Install the RPM

```
dnf install  jre-8u60-linux-x64.rpm
````

### Delete the archive file

```
rm ~/jre-8u60-linux-x64.rpm
```

## Install Java 8 JDK

```
su root
cd ~
wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/8u60-b27/jdk-8u60-linux-x64.rpm"
```
### Install the RPM

```
dnf install  jdk-8u60-linux-x64.rpm
````

### Delete the archive file

```
rm ~/jdk-8u60-linux-x64.rpm
```

### Check Java version

```
java -version
```

## Install NodeJS

Download the NodeJS tar from the oficial page

```
cd /opt
wget https://nodejs.org/dist/v6.9.1/node-v6.9.1-linux-x64.tar.xz
```

decompress
```
tar xJf node-v6.9.1-linux-x64.tar.xz
```

Edit the bashrc file to put NodeJS like an enviromental variable
add the follow line at the en of the file.

```
export PATH=$PATH:/opt/node-v6.9.0-linux-x64/bin 
```
to edit the file you can use nano, where usuario is the user name
``` 
nano /home/usuario/.bashrc
```
then you should reboot the console and to check that everything is ok run the follow command

```
node -v 
npm -v
```

wheter everything is ok, when you run the commandas you should see the version of node and npm packages.

## Install webdriver-manager and nightwatch

webdriver-manager is to manage the browsers webdriver and with this tool we can run the tests. To install you should run the following command in the terminal.

```
npm install -g webdriver-manager
```

ref. [webdriver-manager](https://www.npmjs.com/package/webdriver-manager)

nightwatch is the framework that will allow us to make the tests on nodejs language. To install it you have to run the following command in the terminal.
```
npm install -g nightwatch
```

ref.[nightwatch](http://nightwatchjs.org/)