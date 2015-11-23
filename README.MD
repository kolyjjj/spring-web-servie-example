## Build project:
gradle build

## run app:
gradle bootRun

## see [WSDL](http://www.w3schools.com/xml/xml_wsdl.asp):
http://localhost:8080/ws/countries.wsdl

A copy is under root directory named "countries.wsdl"

## send request to test:
cd to the project

$ curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws

the request is under request.xml, and one sample result is in result.xml

## class generated
countries.xsd is used to generate the classes under generated-sources/jaxb and build/classes/jaxb

