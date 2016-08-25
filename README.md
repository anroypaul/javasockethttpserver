# javasockethttpserver
Simple Java HTTP Server with using Socket API

How to:

1. Run user.sql script into H2 DB (Address must be 'jdbc:h2:~/test')
2. Start MainClass application
3. To invoke HTTP method GET (e.g. in cURL), type "curl -X GET http://localhost:1234/1"
4. To invoke HTTP method POST (e.g. in cURL), type "curl -X POST http://localhost:1234/4/James/May"
5. To see log open application-trace.log

P.S. Make sure that you added H2 JDBC-driver and log4j-library into your project.
Additional libraries:
- [H2 JDBC-driver](http://h2database.com/html/main.html)
- [log4j2](http://logging.apache.org/log4j/2.x/)