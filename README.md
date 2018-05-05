# example-webservice

## build
./gradlew build

## run
java -jar target/gs-soap-service-0.1.0.jar

## test
curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws
