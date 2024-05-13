# MedMinder
An Android app that helps users keep track of their medications.

## About

MedMinder is an Android application designed to make it easier for users to keep track of their medications and to help them remember to take them. It offers the ability to add medications for multpile patients, set medication reminders on a variety of intervals, and take notes on a medication to record any adverse effects if might cause. All user data is stored locally is not share with either the developer or any other third party.

## Requirements

+ Android 8.0 Oreo or newer
+ 15 MB storage

## Languages

 - English (default)
 - German by [uDEV2019](https://github.com/uDEV2019)

## Building the App

It is strongly recommended to use [Android Studio](https://developer.android.com/studio) to build and test this application.

### Additional Dependencies
#### C/C++ SQLite3 Library

This project uses the ````sqlite3.c```` and ````sqlite3.h```` files in its NDK portion. These can be found [here](https://www.sqlite.org/download.html) in the zip file under "Source Code". In order for CMake to find them, and enviroment variable called ````SQLITE3_LIB_PATH```` has to be set to their path.

##### Setting the Envrioment Variable

- Linux (Native)
  ````
  export SQLITE3_LIB_PATH=/path/to/dir/
  ````

  It is strongly recommended to add this to the ````.bashrc```` file in your home directory so they will persist across sessions.

- Linux (Flatpak)

  ````
  flatpak override --user --env=SQLITE3_LIB_PATH=/path/to/dir/ com.google.AndroidStudio
  ````

- Windows
  ````
  [Environment]::SetEnvironmentVariable('SQLITE3_LIB_PATH', 'C:\path\to\dir', 'Machine')
  ````

  This will create an environment variable that will persist across sessions.

## Installation

### GitHub

The latest releases can be found here: [releases](https://github.com/AdamGuidarini/MedMinder/releases). You may need to enable downloading apps from unknown sources to install it.

### F-Droid

Thanks to [IzzySoft](https://github.com/IzzySoft), this app is available in the [IzzyOnDroid](https://apt.izzysoft.de/fdroid/) F-Droid repository [here](https://apt.izzysoft.de/fdroid/index/apk/projects.medicationtracker/).

##### Adding the repository to the F-Droid App

- Download [F-Droid](https://f-droid.org/) (if not already installed)
- Navigate to "Settings"
- Under the "My Apps" section, select "Repositories"
- Click on the "+" button
- Copy the following URL: https://apt.izzysoft.de/fdroid/repo?fingerprint=3BF0D6ABFEAE2F401707B6D966BE743BF0EEE49C2561B9BA39073711F628937A
- After that, you should be able to find it by searching for "MedMinder"

## Screenshots

<img src="https://github.com/AdamGuidarini/MedMinder/assets/45023561/63f322c3-8006-4ba9-8c2f-fa27cbb7001e" width=10% height=10%>
<img src="https://github.com/AdamGuidarini/MedMinder/assets/45023561/5a8bdc42-ee52-426a-bc2c-6f898fdb825e" width=10% height=10%>
<img src="https://github.com/AdamGuidarini/MedMinder/assets/45023561/e4da8dca-804b-4280-9315-9835f80d9e69" width=10% height=10%>
<img src="https://github.com/AdamGuidarini/MedMinder/assets/45023561/09d363b6-1514-4d92-a1fd-81cdf05b9644" width=10% height=10%>
<img src="https://github.com/AdamGuidarini/MedMinder/assets/45023561/19f32b0c-2ff5-4bff-9e2a-e65c285b247e" width=10% height=10%>
<img src="https://github.com/AdamGuidarini/MedMinder/assets/45023561/a8b4bd89-00a1-411e-ae69-6868ef85247f" width=10% height=10%>
