
1. build.gradle - build script (like package.json)
2. gradle/wrapper/gradle-wrapper.jar - executable JAR file
3. gradle/wrapper/gradle-wrapper.properties - config properties for gradlew (gradle wrapper)
4. gradlew - gradle wrapper (auto downloads the correct version of gradle without manually installing it)
5. gradlew.bat - same as 4 but for windows
6. settings.gradle - config settings for gradle build



## Plugins vs Dependencies
* plugins are for tasks, dependencies are for your project


## what are tasks?
* tasks are kind of like npm scripts. You run them like: ``` ./gradlew {task name} ```

## What tasks are available to me?
* Run ``` ./gradlew task ``` to see, you will see the tasks you created and the ones that come built in.