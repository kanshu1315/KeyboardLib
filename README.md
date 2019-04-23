#### 使用方法

```
//Project下的build.gradle
allprojects {
    repositories {
						...
        maven { url "https://raw.githubusercontent.com/kanshu1315/KeyboardLib/master" }
        // jcenter()
    }
}

//模块中的build.gradle
dependencies {
                     ...
    implementation 'com.kanshu:keyboard:0.0.1'
}


```
