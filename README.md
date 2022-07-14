Flutter implementation of the [Mono Icons icons pack](https://github.com/mono-company/mono-icons).

![](https://mono.company/wp-content/uploads/2020/09/Image-1-1024x576.png)

## Installation

You can install `mono_icons` using pub, add this to your pubspec.yaml file:

``` yaml
dependencies:
  mono_icons: ^1.0.0
```

## Usage

You can use mono icons with the `Icon` Widget like this: 

```dart
import 'package:mono_icons/mono_icons.dart'; 

...

@override
Widget build(BuildContext context) {
  return Scaffold(
    appBar: AppBar(
      title: const Text('Mono Icons'),
    ),
    body: const Center(
      child: Icon(MonoIcons.remove),
    ),
  );
}
```

