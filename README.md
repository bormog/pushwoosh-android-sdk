Pushwoosh Android SDK
=====================
[![GitHub release](https://img.shields.io/github/release/Pushwoosh/pushwoosh-andorid-sdk.svg?style=flat-square)](https://github.com/Pushwoosh/pushwoosh-android-sdk/releases) 
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.pushwoosh/pushwoosh/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.pushwoosh/pushwoosh)

The SDK uses JobIntentService. You must include the following maven repository URL in build.gradle:

	allprojects {
	    repositories {
	        jcenter ()
	        google()
	    } 
	}
	
In addition, add the following dependencies.

	dependencies {
	   ...
	   compile 'com.android.support:support-compat:26.+'
	   compile 'com.google.firebase:firebase-messaging:11.+'
	   compile 'com.pushwoosh:pushwoosh:6.1.3'
	}
Starting with Pushwoosh SDK 5.4.2, you need to use [Android Plugin for Gradle v3.0.0](https://developer.android.com/studio/build/gradle-plugin-3-0-0.html) (or higher) with Gradle v4.1 (or higher).

Starting with Pushwoosh SDK 5.1.1, FCM library is used by default, therefore, you need to integrate Firebase into your project correctly. Please refer to [Getting Started](https://www.pushwoosh.com/platform-docs/pushwoosh-sdk/android-push-notifications/integrate-pushwoosh-android-sdk) guide.

[Pushwoosh.aar](https://github.com/Pushwoosh/pushwoosh-android-sdk/blob/master/Pushwoosh.aar) - compiled version of Pushwoosh Android SDK. Includes all necessary AndroidManifest.xml changes required for receiving FCM push notifications. For Amazon integration please add the following dependency:

	compile 'com.pushwoosh:pushwoosh-amazon:6.1.3'

Maven integration:

	<dependency>
  		<groupId>com.pushwoosh</groupId>
  		<artifactId>pushwoosh</artifactId>
  		<version>6.1.3</version>
	</dependency>

Documentation:
https://github.com/Pushwoosh/pushwoosh-android-sdk/tree/master/Documentation

Samples:
https://github.com/Pushwoosh/pushwoosh-android-sdk/tree/master/Samples

Pushwoosh team
http://www.pushwoosh.com
