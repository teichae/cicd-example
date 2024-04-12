FROM tomcat:9.0.76-jdk11-temurin-focal
#war 파일을 ROOT.war 로 변경해야 http://localhost:8080 으로 접근 가능
COPY ./java-static-site.war /usr/local/tomcat/webapps/ROOT.war
WORKDIR /usr/local/tomcat/bin/
ENTRYPOINT ["catalina.sh", "run"]