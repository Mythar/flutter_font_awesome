# flutter_font_awesome_web_names

The flutter_font_awesome_web_names package is developed to support [Font Awesome](https://fontawesome.com/icons) web icons names.  

The [Font Awesome](https://fontawesome.com/icons) Icon pack available as set of Flutter Icons.

Based on Font Awesome 5.15.3. Includes all free icons:

  * Regular
  * Solid
  * Brands

## Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
dependencies:
  flutter_font_awesome:
    git:
      url: https://github.com/Mythar/flutter_font_awesome_web_names
      ref: master
```

## Usage

```dart
import 'package:flutter_font_awesome_web_names/flutter_font_awesome.dart';

class MyWidget extends StatelessWidget {
  Widget build(BuildContext context) {
    return IconButton(
      icon: FaIcon('fas fa-gamepad'),
      onPressed: () { print("Pressed"); }
     );
  }
}
```


## Getting Started

This project is a starting point for a Dart
[package](https://flutter.dev/developing-packages/),
a library module containing code that can be shared easily across
multiple Flutter or Dart projects.

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
