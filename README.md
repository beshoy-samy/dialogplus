# Dialogplus
please refer to [Dialogplus](https://github.com/orhanobut/dialogplus) for a full wiki

Usage of this custom fork which fixes click listeners for viewHolder in the original library
[![](https://jitpack.io/v/beshoy-samy/dialogplus.svg)](https://jitpack.io/#beshoy-samy/dialogplus)
-----
## gradle
# in build.gradle project module
```groovy
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
# in build.gradle app module
```groovy
	implementation 'com.github.beshoy-samy:dialogplus:fix-v1'
```
