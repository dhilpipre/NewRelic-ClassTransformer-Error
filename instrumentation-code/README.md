# Building Instrumentation Jar  

## Initial Task   

Before compiling and/or building you need to run an initialization task.

./gradlew checkForDependencies    

 ## Building

 Set the environment variable NEW_RELIC_EXTENSIONS_DIR to the location of the extensions directory of the New Relic Java Agent   

 run this command to build the extension jar

 ./gradlew kotlin-suspends:clean kotlin-suspends:install    

 Because this instrumentation package does not Weave any classes, it is not possible to verify the instrumentation
