  FROM tomcat:version-seleccionada
  LABEL maintainer="oscarmata10@iespuerto.es"

  ARG WAR_FILE=target/*.war

  ADD ${ARG} /usr/local/tomcat/webapps/

  EXPOSE 8082
  CMD ["catalina.sh", "run"]
