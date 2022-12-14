# dynamodb-autoconfiguration
\
Dynamo-DB Spring-Boot AutoConfiguration for
- **AmazonDynamDB** (Low-Level Interface)
- **DynamoDB** (Document Interface)
- **DynamoDBMapper** (Object persistance Interface)

To add the dependency in your project:
#### Maven
```
<dependency>
    <groupId>com.dz.dynamodb</groupId>
    <artifactId>ddconfig-spring-boot-starter</artifactId>
    <version>0.0.1-SNAPSHOT</version>
</dependency>
```
#### Gradle
```
compile "com.dz.dynamodb:ddconfig-spring-boot-starter:0.0.1-SNAPSHOT"
```

### application.properties
```
dynamodb.endpoint=
dynamodb.region=
dynamodb.accessKey=
dynamodb.secretKey=
```
### application.yml
```
dynamodb:
    endpoint:
    region:
    accessKey:
    secretKey:
```
<br>

> To disable the beans creation, set
> ```dynamodb.enabled``` property to ```false```
> 
