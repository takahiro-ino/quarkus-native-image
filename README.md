# quarkus-native-image
Quarkus native image for confirmation

 - Native build on Linux (x86).
 - target file: target/getting-started-1.0.0-SNAPSHOT-runner
 
# build container

for Mac M1
```
docker build --platform linux/x86_64 -f src/main/docker/Dockerfile.native-micro -t quarkus-quickstart/getting-started .
```

others
```
docker build  -f src/main/docker/Dockerfile.native-micro -t quarkus-quickstart/getting-started .
```

