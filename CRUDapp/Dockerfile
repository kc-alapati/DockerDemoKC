FROM openjdk:17

COPY ./target/demo*.jar usr/app/CRUDapp.jar

WORKDIR usr/app

ENTRYPOINT ["java","-jar","CRUDapp.jar"]