Android DB
==========

Android DB is a library that allows access to the database synchronously and asynchronously. Works on Android 2.3 (API level 10) and upwards.

[![Release](https://img.shields.io/github/release/raxden/AndroidDB.svg?label=maven central)](https://jitpack.io/#raxden/AndroidDB/) [![API](https://img.shields.io/badge/API-10%2B-green.svg?style=flat)](https://android-arsenal.com/api?level=10)

## Usage

In order to use the library, there are 3 options:

**1. Gradle dependency**

 - 	Add the following to your `build.gradle`:
 ```gradle
repositories {
	    maven { url "https://jitpack.io" }
}

dependencies {
	    compile 'com.github.raxden:AndroidDB:v2.1.7@aar'
}
```

**2. Maven**
- Add the following to your `pom.xml`:
 ```xml
<repository>
       	<id>jitpack.io</id>
	    <url>https://jitpack.io</url>
</repository>

<dependency>
	    <groupId>com.github.raxden</groupId>
	    <artifactId>AndroidDB</artifactId>
	    <version>v2.1.7</version>
</dependency>
```

**3. clone whole repository**
 - Open your **commandline-input** and navigate to your desired destination folder (where you want to put the library)
 - Use the command `git clone https://github.com/raxden/AndroidDB.git` to download the full AndroidDB repository to your computer (this includes the folder of the library project as well as the example project)

### Documentation 

For a **detailed documentation**, please have a look at the [**Wiki**](https://github.com/raxden/AndroidDB/wiki).
