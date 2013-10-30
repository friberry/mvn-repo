How to use
========

Simply add the repository to your build.gradle file:

    repositories {
        maven {
            url 'https://github.com/friberry/mvn-repo/raw/master/'
        }
        mavenCentral()
    }

And you can use the artifacts like this:

    dependencies {
        compile "com.friberry.viewpagerindicator:library:2.4.1"
        compile "com.jeremyfeinstein.slidingmenu:slidingmenu:1.3-SNAPSHOT"        
    }

Note that "com.friberry.viewpagerindicator" is customized [com.viewpagerindicator](http://viewpagerindicator.com/) by friberry