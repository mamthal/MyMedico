My Medico:

To access the application:

Open index.html for navigating to home page.


To access backend:
# MyMedico
Maven Java application

RESTful MyMedico Service

$ mvn clean package

$ java -jar target/mymedico-0.0.1-SNAPSHOT.jar server config/dev_config.yml

How to run this Java process forever

$ nohup ./bin/dev.sh 0<&- &> /tmp/app.log &

Service endpoint: http://localhost:9000/mymedico/v1

Admin: http://localhost:9001/