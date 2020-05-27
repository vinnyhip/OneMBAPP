# OneMBAPP
Android min size app

Language: Kotlin
Release Size: 308 KB
Debug Size: 1282 KB

Strategy
Remove LayoutConstraint
Remove AppCompat
App Gradle
buildTypes {
    release {
        minifyEnabled true
        shrinkResources true
        proguardFiles getDefaultProguardFile('proguard-android-optimize.txt'), 'proguard-rules.pro'
    }
}

Build Gradle

