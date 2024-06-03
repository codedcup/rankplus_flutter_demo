# rankplus_flutter_demo

# Flutter

First depend on the library by adding this to your packages pubspec.yaml:
```
dependencies:
  flutter_unity_widget: ^2022.2.0
```

Now inside your Dart code you can import it.
```
import 'package:flutter_unity_widget/flutter_unity_widget.dart';
```

Setting the Android NDK

Add NDK path in your flutter project at android/local.properties as ndk.dir=

for e.g. 
```
ndk.dir=C:\\Program Files\\Unity\\Hub\\Editor\\2021.3.13f1\\Editor\\Data\\PlaybackEngines\\AndroidPlayer\\NDK
```

You can instead define it in android/app/build.gradle.
```
android {
  ndkVersion "21.3.6528147"
}
```

For more details: https://pub.dev/packages/flutter_unity_widget
