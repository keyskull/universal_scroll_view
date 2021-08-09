# universal_scroll_view

Universal Scroll View is a cross platform package which base on Flutter framework.  

latest updated: 17:49:19 08-08-2021
---


## Install

Install by adding this package to your `pubspec.yaml`:

```yaml
dependencies:
  universal_scroll_view: ^[latest version]
```

## Usage
---

### Import
```dart
import 'package:universal_scroll_view/universal_single_child_scroll_view.dart';
```

### Simple Example
```dart

UniversalSingleChildScrollView(
    child: Center(
        child: Column(
            mainAxisAlignment: MainAxisAlignment.center,
            children: List.generate(
                50,
                (index) => Container(
                    height: 500,
                    color: Colors.primaries[Random().nextInt(Colors.primaries.length)],
                    child: Center(child: Column(
                            children: [
                                Text(index.toString()),
                                Text("Supported browser scrolling event.")
                    ],
                ),
            ),
        ))),
    ),
);

```

# License
Copyright © 2020, [Jialin Li](https://github.com/keyskull).  
Released under the [GNU AGPLv3](LICENSE).