FROM tomcat:8.5


ADD conf/server.xml /usr/local/tomcat/conf/server.xml
ADD conf/tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
ADD bookstorewebapp-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/bookstorewebapp-0.0.1-SNAPSHOT.war
ADD conf/context.xml /usr/local/tomcat/webapps/manager/META-INF/context.xml