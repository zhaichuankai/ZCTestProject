# 接入指南
## Gradle: 
	allprojects {
   	 repositories {
        ...
        maven { url 'https://jitpack.io' }
        maven { url 'http://maven.aliyun.com/nexus/content/groups/public/' }
    	}
	}
implementation 'com.github.zhaichuankai:ZCTestProject:Tag'
## Maven
    <dependency>
	    <groupId>com.github.zhaichuankai</groupId>
	    <artifactId>ZCTestProject</artifactId>
	    <version>Tag</version>
    </dependency>
