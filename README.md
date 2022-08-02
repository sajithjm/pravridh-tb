# pravridh-tb
Base setup for tb project

install > jdk11.14 onwards
install postgres
# check the sql files to create table and insert data into table
# find all the DDL sql files and run the query's - > inside dao -> resources- > sql folder 
# find this file and run through postgres - dao-> test -> system-data.sql (to have sysadmin)

username: sysadmin@thingsboard.org
password:sysadmin



# to build the project
if command line  - mvn clean install -DskipTests
if eclispe - clean install -DskipTests 

# to run project 
find thingboard-boot.jar inside application folder and run
java -jar thingboard-boot.jar




