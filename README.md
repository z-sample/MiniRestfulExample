# MiniRestfulExample

不依赖Spring Boot , 整个应用打包后非常小只有4M左右

# 使用Maven快速创建应用

```
mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-webapp \
                -DarchetypeGroupId=org.glassfish.jersey.archetypes -DinteractiveMode=false \
                -DgroupId=com.example -DartifactId=simple-service-webapp -Dpackage=com.example \
                -DarchetypeVersion=2.24.1
```
参考:https://jersey.java.net/documentation/latest/user-guide.html#new-webapp
