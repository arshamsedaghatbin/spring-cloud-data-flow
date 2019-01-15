# spring-cloud-data-flow
start server
create jar from source processor and sink 
create appp in server ui localhost:9393
   dataflow:>app register --name source-app --type source --uri maven://com.javainuse:source:jar:0.0.1-SNAPSHOT
   dataflow:>app register --name processor-app --type processor --uri maven://com.javainuse:processor:jar:0.0.1-SNAPSHOT
   dataflow:>app register --name sink-app --type sink --uri maven://com.javainuse:sink:jar:0.0.1-SNAPSHO
run stream and see logs 
