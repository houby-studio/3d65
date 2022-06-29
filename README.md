# 3D65

Micro "ERP" to manage hobby 3D printing, save your print history, manage spool inventory, share printer with your friends - pay for what they actually use.

## Development

### Editor

<https://docs.flutter.dev/get-started/editor>

* Install extension
  * Dart-Code.flutter

### Appwrite Backend

* Start with docker-compose or docker command <https://appwrite.io/docs/installation>
* Create new project <https://appwrite.io/docs/getting-started-for-flutter>
* Add Web platform for dev

### Flutter Web

* Download Flutter SDK <https://docs.flutter.dev/get-started/install/windows>
* Setup Web project <https://docs.flutter.dev/get-started/web>
* Unzip to folder
* Add flutter/bin to PATH env
* If you alternative Chrome browser, set CHROME_EXECUTABLE env, for example `CHROME_EXECUTABLE=C:\Program Files\BraveSoftware\Brave-Browser\Application\brave.exe`
* Set up project

```powershell
flutter channel stable
flutter upgrade
flutter create my_app
cd .\app_3d65\
flutter run -d chrome
```

### Flutter Windows

* Install Visual Studio 2022 with Desktop Development C++
