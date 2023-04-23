# quarkus-native-image
Quarkus native image for confirmation

## build log
mvn -f /tmp/hello/getting-started/pom.xml clean package -Pnative -DskipTests

[INFO] Scanning for projects...
[INFO] 
[INFO] ------------< com.redhat.quarkus.platform:getting-started >-------------
[INFO] Building getting-started 1.0.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy/2.2.5.Final-redhat-00010/quarkus-resteasy-2.2.5.Final-redhat-00010.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy/2.2.5.Final-redhat-00010/quarkus-resteasy-2.2.5.Final-redhat-00010.pom (2.5 kB at 8.4 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-parent/2.2.5.Final-redhat-00010/quarkus-resteasy-parent-2.2.5.Final-redhat-00010.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-parent/2.2.5.Final-redhat-00010/quarkus-resteasy-parent-2.2.5.Final-redhat-00010.pom (748 B at 17 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-server-common/2.2.5.Final-redhat-00010/quarkus-resteasy-server-common-2.2.5.Final-redhat-00010.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-server-common/2.2.5.Final-redhat-00010/quarkus-resteasy-server-common-2.2.5.Final-redhat-00010.pom (2.0 kB at 47 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-common/2.2.5.Final-redhat-00010/quarkus-resteasy-common-2.2.5.Final-redhat-00010.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-common/2.2.5.Final-redhat-00010/quarkus-resteasy-common-2.2.5.Final-redhat-00010.pom (4.6 kB at 112 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-core/4.7.0.Final-redhat-00004/resteasy-core-4.7.0.Final-redhat-00004.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-core/4.7.0.Final-redhat-00004/resteasy-core-4.7.0.Final-redhat-00004.pom (8.7 kB at 198 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-jaxrs-all/4.7.0.Final-redhat-00004/resteasy-jaxrs-all-4.7.0.Final-redhat-00004.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-jaxrs-all/4.7.0.Final-redhat-00004/resteasy-jaxrs-all-4.7.0.Final-redhat-00004.pom (19 kB at 435 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-dependencies/4.7.0.Final-redhat-00004/resteasy-dependencies-4.7.0.Final-redhat-00004.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-dependencies/4.7.0.Final-redhat-00004/resteasy-dependencies-4.7.0.Final-redhat-00004.pom (48 kB at 1.0 MB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-core-spi/4.7.0.Final-redhat-00004/resteasy-core-spi-4.7.0.Final-redhat-00004.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-core-spi/4.7.0.Final-redhat-00004/resteasy-core-spi-4.7.0.Final-redhat-00004.pom (8.0 kB at 190 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy/2.2.5.Final-redhat-00010/quarkus-resteasy-2.2.5.Final-redhat-00010.jar
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-server-common/2.2.5.Final-redhat-00010/quarkus-resteasy-server-common-2.2.5.Final-redhat-00010.jar
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-common/2.2.5.Final-redhat-00010/quarkus-resteasy-common-2.2.5.Final-redhat-00010.jar
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-core/4.7.0.Final-redhat-00004/resteasy-core-4.7.0.Final-redhat-00004.jar
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-core-spi/4.7.0.Final-redhat-00004/resteasy-core-spi-4.7.0.Final-redhat-00004.jar
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-server-common/2.2.5.Final-redhat-00010/quarkus-resteasy-server-common-2.2.5.Final-redhat-00010.jar (7.7 kB at 161 kB/s)
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy/2.2.5.Final-redhat-00010/quarkus-resteasy-2.2.5.Final-redhat-00010.jar (88 kB at 1.1 MB/s)
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-core-spi/4.7.0.Final-redhat-00004/resteasy-core-spi-4.7.0.Final-redhat-00004.jar (185 kB at 1.8 MB/s)
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/org/jboss/resteasy/resteasy-core/4.7.0.Final-redhat-00004/resteasy-core-4.7.0.Final-redhat-00004.jar (787 kB at 5.8 MB/s)
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-common/2.2.5.Final-redhat-00010/quarkus-resteasy-common-2.2.5.Final-redhat-00010.jar (25 kB at 148 kB/s)
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ getting-started ---
[INFO] 
[INFO] --- quarkus-maven-plugin:2.2.5.Final-redhat-00007:generate-code (default) @ getting-started ---
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-deployment-2.2.5.Final-redhat-00010.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-deployment-2.2.5.Final-redhat-00010.pom (4.0 kB at 90 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-server-common-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-server-common-deployment-2.2.5.Final-redhat-00010.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-server-common-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-server-common-deployment-2.2.5.Final-redhat-00010.pom (2.2 kB at 54 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-common-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-common-deployment-2.2.5.Final-redhat-00010.pom
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-common-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-common-deployment-2.2.5.Final-redhat-00010.pom (1.8 kB at 43 kB/s)
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-common-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-common-deployment-2.2.5.Final-redhat-00010.jar
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-server-common-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-server-common-deployment-2.2.5.Final-redhat-00010.jar
[INFO] Downloading from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-deployment-2.2.5.Final-redhat-00010.jar
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-deployment-2.2.5.Final-redhat-00010.jar (23 kB at 553 kB/s)
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-server-common-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-server-common-deployment-2.2.5.Final-redhat-00010.jar (32 kB at 718 kB/s)
[INFO] Downloaded from jboss-enterprise-maven-repository-ga: https://maven.repository.redhat.com/ga/io/quarkus/quarkus-resteasy-common-deployment/2.2.5.Final-redhat-00010/quarkus-resteasy-common-deployment-2.2.5.Final-redhat-00010.jar (21 kB at 133 kB/s)
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ getting-started ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Copying 2 resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.8.1:compile (default-compile) @ getting-started ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 1 source file to /tmp/hello/getting-started/target/classes
[INFO] 
[INFO] --- quarkus-maven-plugin:2.2.5.Final-redhat-00007:generate-code-tests (default) @ getting-started ---
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ getting-started ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory /tmp/hello/getting-started/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.8.1:testCompile (default-testCompile) @ getting-started ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 2 source files to /tmp/hello/getting-started/target/test-classes
[INFO] 
[INFO] --- maven-surefire-plugin:3.0.0-M5:test (default-test) @ getting-started ---
[INFO] Tests are skipped.
[INFO] 
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ getting-started ---
[INFO] Building jar: /tmp/hello/getting-started/target/getting-started-1.0.0-SNAPSHOT.jar
[INFO] 
[INFO] --- quarkus-maven-plugin:2.2.5.Final-redhat-00007:build (default) @ getting-started ---
[INFO] [org.jboss.threads] JBoss Threads version 3.4.2.Final-redhat-00001
[INFO] [io.quarkus.deployment.pkg.steps.JarResultBuildStep] Building native image source jar: /tmp/hello/getting-started/target/getting-started-1.0.0-SNAPSHOT-native-image-source-jar/getting-started-1.0.0-SNAPSHOT-runner.jar
[INFO] [io.quarkus.deployment.pkg.steps.NativeImageBuildStep] Building native image from /tmp/hello/getting-started/target/getting-started-1.0.0-SNAPSHOT-native-image-source-jar/getting-started-1.0.0-SNAPSHOT-runner.jar
[INFO] [io.quarkus.deployment.pkg.steps.NativeImageBuildStep] Running Quarkus native-image plugin on native-image 22.1.0.0-Final Mandrel Distribution (Java Version 11.0.15+10)
[INFO] [io.quarkus.deployment.pkg.steps.NativeImageBuildRunner] /usr/local/mandrel-java11-22.1.0.0-Final/bin/native-image -J-Dsun.nio.ch.maxUpdateArraySize=100 -J-Djava.util.logging.manager=org.jboss.logmanager.LogManager -J-Dvertx.logger-delegate-factory-class-name=io.quarkus.vertx.core.runtime.VertxLogDelegateFactory -J-Dvertx.disableDnsResolver=true -J-Dio.netty.leakDetection.level=DISABLED -J-Dio.netty.allocator.maxOrder=3 -J-Duser.language=en -J-Duser.country= -J-Dfile.encoding=UTF-8 -H:-ParseOnce -H:InitialCollectionPolicy=com.oracle.svm.core.genscavenge.CollectionPolicy\$BySpaceAndTime -H:+JNI -H:+AllowFoldMethods -H:FallbackThreshold=0 -H:+ReportExceptionStackTraces -H:-AddAllCharsets -H:EnableURLProtocols=http -H:NativeLinkerOption=-no-pie -H:-UseServiceLoaderFeature -H:+StackTrace getting-started-1.0.0-SNAPSHOT-runner -jar getting-started-1.0.0-SNAPSHOT-runner.jar
================================================================================
GraalVM Native Image: Generating 'getting-started-1.0.0-SNAPSHOT-runner' (executable)...
================================================================================
[1/7] Initializing...                                            (6.1s @ 0.18GB)
 Version info: 'GraalVM 22.1.0.0-Final Java 11 Mandrel Distribution'
 C compiler: gcc (redhat, x86_64, 8.5.0)
 Garbage collector: Serial GC
 2 user-provided feature(s)
  - io.quarkus.runner.AutoFeature
  - io.quarkus.runtime.graal.ResourcesFeature
The bundle named: messages, has not been found. If the bundle is part of a module, verify the bundle name is a fully qualified class name. Otherwise verify the bundle path is accessible in the classpath.
[2/7] Performing analysis...  [*01:03:03,541 INFO  [org.jbo.threads] JBoss Threads version 3.4.2.Final-redhat-00001
***********]                    (39.0s @ 0.76GB)
   9,764 (89.32%) of 10,931 classes reachable
  14,423 (61.59%) of 23,417 fields reachable
  49,009 (57.26%) of 85,595 methods reachable
     405 classes,    18 fields, and 1,289 methods registered for reflection
      68 classes,    88 fields, and    54 methods registered for JNI access
[3/7] Building universe...                                       (2.1s @ 1.21GB)
[4/7] Parsing methods...      [***]                              (7.8s @ 1.62GB)
[5/7] Inlining methods...     [*****]                           (17.2s @ 1.52GB)
[6/7] Compiling methods...    [******]                          (41.9s @ 2.07GB)
[7/7] Creating image...                                          (4.0s @ 1.87GB)
  18.73MB (43.27%) for code area:   31,101 compilation units
  20.03MB (46.27%) for image heap:   6,690 classes and 249,424 objects
   4.53MB (10.46%) for other data
  43.29MB in total
--------------------------------------------------------------------------------
Top 10 packages in code area:           Top 10 object types in image heap:
   1.73MB sun.security.ssl                 4.19MB byte[] for code metadata
 975.90KB java.util                        2.38MB java.lang.Class
 715.53KB com.sun.crypto.provider          2.35MB byte[] for general heap data
 484.63KB sun.security.x509                2.25MB java.lang.String
 414.88KB io.netty.buffer                  1.80MB byte[] for java.lang.String
 414.83KB java.lang                      915.38KB c.o.s.c.h.DynamicHubCompanion
 409.36KB java.util.concurrent           619.97KB java.util.HashMap$Node
 400.31KB java.io                        472.79KB java.lang.String[]
 353.95KB io.netty.handler.codec.http2   421.27KB byte[] for reflection metadata
 302.44KB java.net                       294.00KB java.util.HashMap$Node[]
      ... 350 additional packages             ... 2144 additional object types
                       (use GraalVM Dashboard to see all)
--------------------------------------------------------------------------------
   29.1s (23.8% of total time) in 73 GCs | Peak RSS: 2.74GB | CPU load: 2.34
--------------------------------------------------------------------------------
Produced artifacts:
 /tmp/hello/getting-started/target/getting-started-1.0.0-SNAPSHOT-native-image-source-jar/getting-started-1.0.0-SNAPSHOT-runner (executable)
 /tmp/hello/getting-started/target/getting-started-1.0.0-SNAPSHOT-native-image-source-jar/getting-started-1.0.0-SNAPSHOT-runner.build_artifacts.txt
================================================================================
Finished generating 'getting-started-1.0.0-SNAPSHOT-runner' in 2m 1s.
[INFO] [io.quarkus.deployment.pkg.steps.NativeImageBuildRunner] objcopy --strip-debug getting-started-1.0.0-SNAPSHOT-runner
[INFO] [io.quarkus.deployment.QuarkusAugmentor] Quarkus augmentation completed in 125839ms
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  02:11 min
[INFO] Finished at: 2023-04-23T01:04:47Z
[INFO] --------------------------------------------------
