# MDL-Android-Repo

This is MDL Android repository for MDL_Android_project

# Dependency

at root project `build.gradle`

```gradle
repositories {
    maven {
        url 'https://raw.githubusercontent.com/MDL-Sinlov/MDL-Android-Repo/master/mvn-repo/'
    }
    //jcenter()
    ...
}
```

use at module build.gradle

```gradle
dependencies{
    compile 'compile:latest.integration'
    //compile 'compile:latest.integration@aar'
}
```

# List of this repo

|ProjectName|compile|URL|
|-----------|-------|---|
|Android ALog|compile 'mdl.sinlov.android:log:0.0.2'|https://github.com/MDL-Sinlov/MDL_Android_Log|
|Android Updater|compile 'mdl.sinlov.android:updater:0.0.3'|https://github.com/MDL-Sinlov/MDL_Android_Updater|
|Android WebSocket|compile 'mdl.sinlov.android:websocket:0.0.2'|https://github.com/MDL-Sinlov/MDL_Android_WebSokcet|
|Android Device-Mark|compile 'mdl.sinlov.android:device-mark:0.0.1'|https://github.com/MDL-Sinlov/MDL_Android-Device-Mark|
