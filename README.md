maven-pom-plugin
================

operate pom.xml with command line


#init
  pom init
  
#dependency
  pom dependency add spring
  pom dependency add spring@lastest
  pom dependency add spring@3.1.2.RELEASE
  pom dependency remove spring

#plugin
  pom plugin add jetty@ -Dreload=automatic -DscanIntervalSeconds=3
  pom plugin remove jetty

#plugin
  pom config properties -Djava.version=1.5
  pom config version 1.0

#version
  pom -v



