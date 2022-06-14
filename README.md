# tabler_icons
### !!! this repository forked of https://github.com/bigbadbob2003/tabler_icons 😉

The official [Tabler Icon Pack](https://github.com/tabler/tabler-icons).

official Tabler icons version: 1.53

## pubspec.yaml
```yml
dependencies:
  flutter:
    sdk: flutter
  tabler_icons: ^1.2.2
```

## Usage
```Dart
import 'package:tabler_icons/tabler_icons.dart';

class MyWidget extends StatelessWidget {
  Widget build(BuildContext context) {
    return new IconButton(
      icon: new Icon(TablerIcons.ambulance),
      onPressed: () { print('Ambulance pressed'); }
     );
  }
}
```
![alt text](https://github.com/bigbadbob2003/tabler_icons/raw/master/.github/screenshot.png)
