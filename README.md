# Espresso + Perfecto execution steps:

Pre-requisites: </br>
    Make sure to install the Android SDK and setup the ANDROID_HOME environment variable & setup JAVA_HOME pointing to JDK 11.
    Gradle version used is 7.4

To build universal apk from .aab file refer to JenkinsFile.

To build the apk & activate the plugin - Open a command-line/terminal window in the project's folder and run the following tasks in gradle:</br></br>
`./gradlew assembleDebug assembleAndroidTest perfecto-android-inst -PconfigFileLocation=configFile.json -PcloudURL=${url} -PsecurityToken=${securityToken}`</br>

### Note: 
1. Replace ${url} with your perfecto cloud url. E.g.: demo.perfectomobile.com </br>
2. Replace ${securityToken} with your perfecto security token.</br>


