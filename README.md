# Minecraft Generation Libraries Index

The MGLI is a way to make available all the libraries for Minecraft world generation.

I suggest to consult this website for [documentation](https://kaptainwutax.seedfinding.com)

The first thing you should do is create a new project in a folder by doing `gradle init` (if you don't know how, refer to 
[this guide](https://gradle.org/install/)).

Then you add those lines in your build.gradle:

```groovy
repositories {
	mavenCentral()
	maven {
		url "https://jitpack.io"
	}
}
dependencies {
	implementation 'com.github.hube12:SEED:master-SNAPSHOT'
}
```
