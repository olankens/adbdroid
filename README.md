# <samp>OVERVIEW (WIP)</samp>

Advanced automation library for Android.

<table>
  <tr align="center">
    <th><samp>AND</samp></th>
    <th><samp>IOS</samp></th>
    <th><samp>LIN</samp></th>
    <th><samp>MAC</samp></th>
    <th><samp>WIN</samp></th>
    <th><samp>WEB</samp></th>
  </tr>
  <tr align="center" height="50">
    <td width="9999">🟩</td>
    <td width="9999">🟥</td>
    <td width="9999">🟥</td>
    <td width="9999">🟥</td>
    <td width="9999">🟥</td>
    <td width="9999">🟥</td>
  </tr>
</table>

# <samp>FEATURES</samp>

- Expand archives
- Invoke shell commands
- Manage files and packages
- Scrape screen elements
- Select elements with xpath

# <samp>GUIDANCE</samp>

### Import library

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
