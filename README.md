# USAVsTheWorld
Trump needs to protect USA from Mexican invaders, help him build towers and walls to prevent it.

# Deployment instructions

### SDK
* Build Tools 25.0.2
* Platform Tools 25.0.3
* Android SDK platform 25
* Android SDK platform 19 (you might need this, but it seems it's optional)

### Local files
* Add a `local.properties` file with the following content:

```
sdk.dir=/opt/android-sdk
```
Of course, replace that path with your own one, where you installed your Android SDK.

* Add a `gradle.properties` file with the following content:

```
org.gradle.daemon=true
org.gradle.jvmargs=-Xms128m -Xmx1500m
org.gradle.configureondemand=true
org.gradle.java.home=/usr/lib/jvm/java-8-openjdk
```

You must change **org.gradle.java.home** with your own one, where Java is installed in your machine.


