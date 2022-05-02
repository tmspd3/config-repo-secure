# config-repo-secure

Spring Cloud Config (Secure) Repository 

## How to use

#### 1. service-name
* repo/${service-name}
#### 2. profiles
* {service-name}-${profiles}.yml
#### 3. branch
* master

#### URL
http://secure-config.raidea.io:8888/${service-name}/${profiles}/master

ex) 
- http://secure-config.raidea.io:8888/user-service/dev/master
