# grpc-hello-server
```
 mvn -DskipTests package
 # Start the Server application
 mvn -DskipTests package exec:java -Dexec.mainClass=com.example.grpc.App
 # Or
 mvn exec:java -Dexec.mainClass=com.example.grpc.App

 # Start the Client in another shell
 mvn -DskipTests package exec:java -Dexec.mainClass=com.example.grpc.Client
 # Or
 mvn exec:java -Dexec.mainClass=com.example.grpc.Client
 ```


