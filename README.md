Android Host App – E-Commerce
This native Android app integrates a Flutter-based SDK (JodeTx) to demonstrate Add-to-App capability.

Features
E-commerce-style UI

Launches Flutter SDK on button tap

Receives payment result via MethodChannel

Dart code from module is fully hidden via AAR integration

How to Use
Place the extracted Flutter AAR repo inside app/libs/flutter-repo

Make sure settings.gradle and build.gradle include correct Maven path

Build & run:

./gradlew clean
./gradlew assembleDebug
