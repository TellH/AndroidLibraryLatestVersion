# AndroidLibraryLatestVersion
#Base
##[dagger2](https://github.com/google/dagger) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.google.dagger/dagger/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)

```
buildscript {
  repositories {
    mavenCentral()
  }
  dependencies {
    classpath 'com.neenbedankt.gradle.plugins:android-apt:1.8'
  }
}

// Apply plugin
apply plugin: 'com.neenbedankt.android-apt'

// Add Dagger dependencies
dependencies {
  compile 'com.google.dagger:dagger:2.x'
  apt 'com.google.dagger:dagger-compiler:2.x'
}
```
##[RxJava](https://github.com/ReactiveX/RxJava) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.reactivex/rxjava/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
dependencies {
  compile 'io.reactivex:rxjava:${LatestVersion}'
}
```
##[RxAndroid](https://github.com/ReactiveX/RxAndroid) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.reactivex/rxandroid/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
dependencies {
  compile 'io.reactivex:rxandroid:{LatestVersion}'
}
```
##[butterknife](https://github.com/JakeWharton/butterknife) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.jakewharton/butterknife/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)

```
buildscript {
  repositories {
    mavenCentral()
   }
  dependencies {
    classpath 'com.neenbedankt.gradle.plugins:android-apt:1.8'
  }
}
apply plugin: 'android-apt'

dependencies {
  compile 'com.jakewharton:butterknife:${LatestVersion}'
  apt 'com.jakewharton:butterknife-compiler:${LatestVersion}'
}
```
##[Logger](https://github.com/orhanobut/logger) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.orhanobut/logger/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
dependencies {
  compile 'com.orhanobut:logger:${LatestVersion}'
}
```
##[leakcanary](https://github.com/square/leakcanary) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.squareup.leakcanary/leakcanary-android/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
 dependencies {
   debugCompile 'com.squareup.leakcanary:leakcanary-android:1.4-beta2'
   releaseCompile 'com.squareup.leakcanary:leakcanary-android-no-op:1.4-beta2'
   testCompile 'com.squareup.leakcanary:leakcanary-android-no-op:1.4-beta2'
 }
 -----------
 public class ExampleApplication extends Application {
  @Override public void onCreate() {
    super.onCreate();
    LeakCanary.install(this);
  }
}
```

#NetWork

##[volley](https://bintray.com/android/android-utils/com.android.volley.volley) [![Download](https://api.bintray.com/packages/android/android-utils/com.android.volley.volley/images/download.svg) ](https://bintray.com/android/android-utils/com.android.volley.volley/_latestVersion)
```
    compile 'com.android.volley:volley:1.0.0'
```

##[OkHttp](https://github.com/square/okhttp) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.squareup.okhttp3/okhttp/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
    compile 'com.squareup.okhttp3:okhttp:3.4.1'
    //compile 'com.squareup.okhttp3:logging-interceptor:3.4.1'
```

##[Retrofit](https://github.com/square/retrofit) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.squareup.retrofit2/retrofit/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
    compile 'com.squareup.retrofit2:retrofit:2.1.0'
    //compile 'com.squareup.retrofit2:converter-gson:2.1.0'
    //compile 'com.squareup.retrofit2:adapter-rxjava:2.1.0'
```

#JsonParser
##[Gson](https://github.com/google/gson) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.google.code.gson/gson/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
    compile 'com.google.code.gson:gson:2.7'
```

##[fastjson](https://github.com/alibaba/fastjson) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.alibaba/fastjson/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser) [![GitHub release](https://img.shields.io/github/release/alibaba/fastjson.svg)](https://github.com/alibaba/fastjson/releases)
[For Android Version](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22com.alibaba%22%20AND%20a%3A%22fastjson%22)：
```
    compile 'com.alibaba:fastjson:1.1.53.android'
```

#ImageLoader
##[Glide](https://github.com/bumptech/glide) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.bumptech.glide/glide/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
dependencies {
  compile 'com.github.bumptech.glide:glide:3.7.0'
  compile 'com.android.support:support-v4:19.1.0'
}
```
##[Picasso](https://github.com/square/picasso) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.squareup.picasso/picasso/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
dependencies {
    compile 'com.squareup.picasso:picasso:2.5.2'
}
```
##[fresco](https://github.com/facebook/fresco) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.facebook.fresco/fresco/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)
```
dependencies {
    compile 'com.facebook.fresco:fresco:0.12.0'
}
```
