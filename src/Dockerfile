FROM public.ecr.aws/r2d7r3i9/dockerhub-tomcat:9

LABEL maintainer="mamvai@amazon.com"

COPY HelloWorld-1.0.war /usr/local/tomcat/webapps/  
COPY index.html /usr/local/tomcat/webapps/ROOT/

EXPOSE 8080

CMD ["catalina.sh", "run"]
