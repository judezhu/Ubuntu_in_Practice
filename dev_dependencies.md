## set up java
		sudo add-apt-repository ppa:webupd8team/java
		sudo apt-get update
		sudo apt-get install oracle-java7-installer

It'll keep your java 7 installation up to date.

http://stackoverflow.com/questions/16263556/installing-java7-on-ubuntu

## set up Tomcat server:

 1. download from apache foundation website;
 2. set up ```$JAVA_HOME```and ```$CATALINA_HOME``` 
   at ~/.profile
 3. run sh catalina.sh start

## set up IDE development:
 1. Download Eclipse;
 2. Add CDT plugin for C/C++ project;
   repository address:http://download.eclipse.org/tools/cdt/releases/kepler
 3. Add PyDev plugin for python project;
   repository address:http://pydev.org/updates

