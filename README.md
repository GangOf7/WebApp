&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="960" style="align-content: center;" height="300" src="https://github.com/GangOf7/WebApp/blob/master/FD.png?raw=true">

# <img src="https://img.icons8.com/cotton/54/000000/wedding-gift.png"/>  Overview
![github-small](https://github.com/GangOf7/WebApp/blob/master/Screen%20record.gif?raw=true)

# <img src="https://img.icons8.com/fluent/54/000000/youtube-play.png"/> Youtube Video Link
https://youtu.be/CSEZSGFQ9V4

# <img src="https://img.icons8.com/cute-clipart/54/000000/application-shield.png"/> Web Application - Visualization 
Flying Dutchman is a web frontend that talks with Pirates bay and helps to visualize data captured by Kalypso IOT device.

# <img src="https://img.icons8.com/doodle/54/000000/blockchain-technology.png"/> Technology:-
 - Java
 - Spring Boot
 - HTML
 - CSS
 - Javascript
 - Jquery
 - Ajax

# <img src="https://img.icons8.com/cotton/54/000000/profitable-idea.png"/> Design IDE:-
 - Eclipse
 - Visual Studio Code

# <img src="https://img.icons8.com/nolan/54/overview-pages-2.png"/> Long Story Short:-
Flying Dutchman is designed to reflect all analytical data captured by Kalypso. Portal is able to collect data from rest API services and returns data as per the filtration process by the user. This portal provides a glanced view of all of the available devices, it also provides the detailed view of all the devices in graphical as well as tabular format. On the other hand, we have a very efficient admin panel where we can add device, add new user and monitor their activity closely. This way the web portal brings user and admin under the same roof.

# <img src="https://img.icons8.com/ios-filled/54/000000/insert.png"/> Install Prerequisites:-
 - <img src="https://img.icons8.com/dusk/15/000000/java-coffee-cup-logo.png"/>  JavaSE 11
 - <img src="https://img.icons8.com/color/15/000000/spring-logo.png"/>  Spring Boot
 - <img src="https://img.icons8.com/color/15/000000/haiku.png"/>  Local Maven Installation

# <img src="https://img.icons8.com/cotton/54/000000/smartphone-cpu.png"/> System Requirment:-
 - RAM : 512MB
 - HDD : 500MB
 - Internet Connectivity
 
# <img src="https://img.icons8.com/fluent/48/000000/code.png"/> Process To Build Webapp Locally:-
#### Clone the project and run these two commends from command line(windows), terminal(mac/linux) in order to build the webapp locally

#### Step 1: Check Java and Maven Version
```
java -version
mvn -v
```
#### Step 2: Install The Project
```
mvn install
java -jar ./target/javaspringapp-1.0-SNAPSHOT.jar
```
# <img src="https://img.icons8.com/cute-clipart/54/000000/bookmark-ribbon.png"/> External Libraries:
```
<dependencies>
   <!-- Core -->
   <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter</artifactId>
   </dependency>
   <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-test</artifactId>
      <scope>test</scope>
   </dependency>
   <!-- temp override to resolve CVE-2017-18640 -->
   <dependency>
      <groupId>org.yaml</groupId>
      <artifactId>snakeyaml</artifactId>
      <version>1.26</version>
   </dependency>
   <!-- https://mvnrepository.com/artifact/org.json/json -->
   <dependency>
      <groupId>org.json</groupId>
      <artifactId>json</artifactId>
      <version>20160810</version>
   </dependency>
   <!--Monitoring -->
   <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-actuator</artifactId>
   </dependency>
   <dependency>
      <groupId>io.micrometer</groupId>
      <artifactId>micrometer-registry-prometheus</artifactId>
   </dependency>
   <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-devtools</artifactId>
      <scope>runtime</scope>
      <optional>true</optional>
   </dependency>
   <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-thymeleaf</artifactId>
   </dependency>
   <!-- Distributed tracing with OpenTracing -->
   <dependency>
      <groupId>io.opentracing.contrib</groupId>
      <artifactId>opentracing-spring-jaeger-web-starter</artifactId>
      <version>${opentracing-spring-jaeger-web-starter.version}</version>
   </dependency>
   <!-- For this template -->
   <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-web</artifactId>
   </dependency>
   <dependency>
      <groupId>com.ibm.cloud</groupId>
      <artifactId>ibm-cloud-spring-boot-service-bind</artifactId>
      <version>1.1.2</version>
   </dependency>
   <dependency>
      <groupId>org.apache.commons</groupId>
      <artifactId>commons-lang3</artifactId>
      <version>3.9</version>
   </dependency>
</dependencies>
```

# <img src="https://img.icons8.com/dusk/54/000000/internet.png"/> Compatible Browser:-
 - <img src="https://img.icons8.com/fluent/15/000000/chrome.png"/>  Chrome 70.0+ 
 - <img src="https://img.icons8.com/dusk/15/000000/internet-explorer.png"/>  Internet Explorer 10+  
 - <img src="https://img.icons8.com/fluent/15/000000/ms-edge-new.png"/>  Edge 40+ 
 - <img src="https://img.icons8.com/color/15/000000/firefox.png"/>  Firefox 72+
 - <img src="https://img.icons8.com/color/15/000000/safari--v1.png"/>  Safari
 

# <img src="https://img.icons8.com/ultraviolet/40/000000/code.png"/> Endpoints:-

```
Home: http://localhost:8080/dutchman/dashboard
Admin: http://localhost:8080/admin/addNew

```
 







