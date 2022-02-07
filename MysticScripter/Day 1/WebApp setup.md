# Testing environment setup

I in this challenge, the DVWA and WebGoat will be the goto vulnerable webapps for testing.

Here's a simple walkthrough(assuming you are working on linux) on the set up:

# DVWA

We'll use docker. So first install the docker container.
```
sudo apt-get install docker.io
```
OR
```
sudo yum install docker.io
```
Install the DVWA
```
docker pull vulnerables/web-dvwa
```
To start the app, run
```
docker run -p 80:80 vulnerables/web-dvwa
```
navigate to http://127.0.0.1 using your preferred browser to access the app.

# WebGoat

Since you have docker installed:
Pull the WebGoat
```
docker pull szsecurity/webgoat
```
run the app
```
docker run -p 1337:80 szsecurity/webgoat
```
launch the app by navigating to http://localhost:1337/WebGoat (Capitalization is important)

The second method, which i highly recommend is using the WebGoat server jar file.
+ First, ensure the latest version of jave is installed in your machine.
+ Create a directory WebGoat
+ Downloadthe WebGoat server jar and the WebWolf jar files from:
```
https://github.com/WebGoat/WebGoat/releases
```
+ Move the files into your WebGoat directory
+ To run the server;
```
cd WebGoat
```
+ Start WebGoat, change version numbers as appropriate
```
java -jar webgoat-server-8.2.2.jar --server.port=8080 --server.address=localhost
```
+ Access it via http://localhost:8080/WebGoat

While working on the WebGoat, you might need to use WebWolf. It simuates an attcker's machine.

To run:
```
cd WebGoat
```
Start the server, changing version number as appropriate
```
java -jar webwolf-8.2.2.jar --server.port=9090 --server.address=localhost
```
**Note:** Port numbers are relative
