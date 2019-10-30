# aprendiendo-flutter

## Intalación de Flutter

- [Linux](https://flutter-es.io/get-started/install/linux)
- [Mac](https://flutter-es.io/get-started/install/macos)
- [Windows](https://flutter-es.io/get-started/install/windows)

## creando proyecto

``` bash
flutter create --androidx -a kotlin -i swift --org com.example <nombre_proyecto>
```

> Nota: el nombre del proyecto debe usar la nomenclatura `lowercase_with_underscores`

Para este ejemplo se utilizó:


``` bash
flutter create --androidx -a kotlin -i swift --org mx.jazijaziel aprendiendo_flutter
```

El resultado obtenido fué:

```
Creating project aprendiendo_flutter...
  aprendiendo_flutter/ios/Runner.xcworkspace/contents.xcworkspacedata (created)
  aprendiendo_flutter/ios/Runner/Info.plist (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/LaunchImage.imageset/LaunchImag
  e@2x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/LaunchImage.imageset/LaunchImag
  e@3x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/LaunchImage.imageset/README.md
  (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/LaunchImage.imageset/Contents.j
  son (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/LaunchImage.imageset/LaunchImag
  e.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-76x
  76@2x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-29x
  29@1x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-40x
  40@1x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-20x
  20@1x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-102
  4x1024@1x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-83.
  5x83.5@2x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-20x
  20@3x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Contents.jso
  n (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-20x
  20@2x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-29x
  29@3x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-40x
  40@2x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-60x
  60@3x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-60x
  60@2x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-76x
  76@1x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-40x
  40@3x.png (created)
  aprendiendo_flutter/ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-29x
  29@2x.png (created)
  aprendiendo_flutter/ios/Runner/Base.lproj/LaunchScreen.storyboard (created)
  aprendiendo_flutter/ios/Runner/Base.lproj/Main.storyboard (created)
  aprendiendo_flutter/ios/Runner.xcodeproj/project.xcworkspace/contents.xcworksp
  acedata (created)
  aprendiendo_flutter/ios/Runner.xcodeproj/xcshareddata/xcschemes/Runner.xcschem
  e (created)
  aprendiendo_flutter/ios/Flutter/Debug.xcconfig (created)
  aprendiendo_flutter/ios/Flutter/Release.xcconfig (created)
  aprendiendo_flutter/ios/Flutter/AppFrameworkInfo.plist (created)
  aprendiendo_flutter/test/widget_test.dart (created)
  aprendiendo_flutter/aprendiendo_flutter.iml (created)
  aprendiendo_flutter/.gitignore (created)
  aprendiendo_flutter/.metadata (created)
  aprendiendo_flutter/android/app/src/profile/AndroidManifest.xml (created)
  aprendiendo_flutter/android/app/src/main/res/mipmap-mdpi/ic_launcher.png
  (created)
  aprendiendo_flutter/android/app/src/main/res/mipmap-hdpi/ic_launcher.png
  (created)
  aprendiendo_flutter/android/app/src/main/res/drawable/launch_background.xml
  (created)
  aprendiendo_flutter/android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png
  (created)
  aprendiendo_flutter/android/app/src/main/res/mipmap-xxhdpi/ic_launcher.png
  (created)
  aprendiendo_flutter/android/app/src/main/res/values/styles.xml (created)
  aprendiendo_flutter/android/app/src/main/res/mipmap-xhdpi/ic_launcher.png
  (created)
  aprendiendo_flutter/android/app/src/main/AndroidManifest.xml (created)
  aprendiendo_flutter/android/app/src/debug/AndroidManifest.xml (created)
  aprendiendo_flutter/android/gradle/wrapper/gradle-wrapper.properties (created)
  aprendiendo_flutter/android/gradle.properties (created)
  aprendiendo_flutter/android/settings.gradle (created)
  aprendiendo_flutter/android/app/build.gradle (created)
  aprendiendo_flutter/android/app/src/main/kotlin/mx/jazijaziel/aprendiendo_flut
  ter/MainActivity.kt (created)
  aprendiendo_flutter/android/build.gradle (created)
  aprendiendo_flutter/android/aprendiendo_flutter_android.iml (created)
  aprendiendo_flutter/pubspec.yaml (created)
  aprendiendo_flutter/README.md (created)
  aprendiendo_flutter/ios/Runner/Runner-Bridging-Header.h (created)
  aprendiendo_flutter/ios/Runner/AppDelegate.swift (created)
  aprendiendo_flutter/ios/Runner.xcodeproj/project.pbxproj (created)
  aprendiendo_flutter/lib/main.dart (created)
  aprendiendo_flutter/.idea/runConfigurations/main_dart.xml (created)
  aprendiendo_flutter/.idea/libraries/Flutter_for_Android.xml (created)
  aprendiendo_flutter/.idea/libraries/Dart_SDK.xml (created)
  aprendiendo_flutter/.idea/libraries/KotlinJavaRuntime.xml (created)
  aprendiendo_flutter/.idea/modules.xml (created)
  aprendiendo_flutter/.idea/workspace.xml (created)
Running "flutter pub get" in aprendiendo_flutter...                 2.6s
Wrote 65 files.

All done!
[✓] Flutter is fully installed. (Channel stable, v1.9.1+hotfix.6, on Mac OS X 10.14.6 18G103, locale es-MX)
[✓] Android toolchain - develop for Android devices is fully installed. (Android SDK version 29.0.2)
[✓] Xcode - develop for iOS and macOS is fully installed. (Xcode 10.1)
[✓] Android Studio is fully installed. (version 3.5)
[!] Connected device is not available.

Run "flutter doctor" for information about installing additional components.

In order to run your application, type:

  $ cd aprendiendo_flutter
  $ flutter run

Your application code is in aprendiendo_flutter/lib/main.dart.
```

Dando como resultado el siguiente directorio:
``` bash
$ ls
aprendiendo-flutter	aprendiendo_flutter	git-new-repo


$ tree -L 2
.
├── aprendiendo-flutter
│   └── README.md
├── aprendiendo_flutter
│   ├── README.md
│   ├── android
│   ├── aprendiendo_flutter.iml
│   ├── ios
│   ├── lib
│   ├── pubspec.lock
│   ├── pubspec.yaml
│   └── test
└── git-new-repo
    └── README.md

7 directories, 6 files
```
