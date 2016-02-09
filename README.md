# Overview

* bt5r3-was.sait230.ca
  * linux distro with lots of security tools
* nessus.sait230.ca
  * nessus and nexpose vulnerability scanners
* samurai.sait230.ca
  * web testing framework
  * has vulnerable web applications as well as the tools to test them.
* websecdojo.sait230.ca
  * has vulnerable web apps as well as tools to test them.
  * preconfigured, stand-alone training environment for web app security.
* metasploitable.sait230.ca
  * has vulnerable network services and web applications for security testing.
* tomcat-apache.sait230.ca
  * tomcat installed, used for recon and file injection.
* bwa.sait230.ca
  * variety of applications with known vulnerabilities.
* ultimatelamp.sait230.ca
  * LAMP applications
  * used for recon, discovery and mapping phases.

Targets:

* bwa.sait230.ca
* metasploitable.sait230.ca
* tomcat-apache.sait230.ca
* ultimatelamp.sait230.ca

# web security technologies

Pure web server: serve static content only.

```ruby
  client -> server
```

Dynamic web servers: servers that serve both static and active content.
Application servers: 
  * examples: websphere, bea weblogic, jboss, tomcat
Proxy servers: 
  * front ends for one or more applications called a reverse proxy.
Http Protocol:
  * request response pattern
  * port 80

HTTP request packets

GET /login.php http/1.1
