# ANDROID APP

## requirements

* JDK 8
* Android studio 3.4
* Android SDK 28

## Project structure

```txt

app/src
|-- main
|   |-- AndroidManifest.xml
|   |-- java
|   |   `-- com
|   |       `-- learneasyapp
|   |           `-- app
|   |               |-- MainActivity.java # activity for login
|   |               |-- Register.java # activity for register
|   |               |-- database
|   |               |   |-- MySQL.java # connection file for mysql database
|   |               |   `-- SQLite.java # sqlite interface for local storage
|   |               `-- sync
|   `-- res
|       |-- drawable # icons
|       |   |-- ic_launcher_background.xml
|       |   `-- student.png
        ...
```

