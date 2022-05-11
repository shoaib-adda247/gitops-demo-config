FROM tomcat:8.0-alpine
ADD /home/ec2-user/.m2/repository/$appwarname-$branch.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD [“catalina.sh”, “run”]
