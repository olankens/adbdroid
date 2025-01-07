# <samp>OVERVIEW</samp>

Automation library for Android, allowing you to invoke shell commands, manage files and packages, select elements using xpath, and much more.

# <samp>GUIDANCE</samp>

### Import the Library

Add repository to settings.gradle:

```gradle
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
```

Add dependency to build.gradle:

```gradle
dependencies {
    implementation 'com.github.olankens:adbdroid:1.0.0'
}
```
