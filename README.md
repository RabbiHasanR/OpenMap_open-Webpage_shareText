# Project Title
OpenMap_open-Webpage_shareText
# Description
Simple android application how open google map with location also open webpage and how share text in social network or message.
# Usages
### Build.gradle
````
allprojects {
    repositories {
        maven{
            url "https://maven.google.com"
        }
        jcenter()
        google()
    }
}
````
### Dependencies
````
dependencies {
        classpath 'com.android.tools.build:gradle:3.4.0-alpha01'
    }
````
