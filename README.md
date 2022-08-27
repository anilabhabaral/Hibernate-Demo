# Hibernate-Demo
Hibernate-ORM Demo Project (CURD operations) With H2 Datasource and JBoss EAP 

# Build Project
~~~
mvn clean install
~~~

# Deploy in EAP 7.x
1. Strat the JBoss EAP
2. Connect to cli:
~~~
./jboss-cli.sh -c
~~~
3. Then deploy the war file (the war file can be found under /target folder) into JBoss EAP using below cli command:
~~~
deploy /path/to/xxxxxx.war
~~~
