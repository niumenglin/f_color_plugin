[comment]: <> ([![pub package]&#40;https://img.shields.io/pub/v/flutter_color_plugin.svg&#41;]&#40;https://pub.dartlang.org/packages/flutter_color_plugin&#41;)

[comment]: <> ([ ![PRs Welcome]&#40;https://img.shields.io/badge/PRs-Welcome-brightgreen.svg&#41;]&#40;https://github.com/crazycodeboy/flutter_color_plugin/pulls&#41;)

[comment]: <> ([ ![flutter_color_plugin release]&#40;https://img.shields.io/github/release/crazycodeboy/flutter_color_plugin.svg?maxAge=2592000?style=flat-square&#41;]&#40;https://github.com/crazycodeboy/flutter_color_plugin/releases&#41;)

A color parse package for flutter,it works on iOS and Android.

## Getting Started

### To get a color


```dart
Color color1 = ColorUtil.color('#f2f2f2');
Color color2 = ColorUtil.color('f2f2f2');
print(color1 == color2); //true
Color color3 = ColorUtil.color('#a1FF5733');
Color color4 = ColorUtil.color('a1FF5733');
print(color3 == color4); //true
```

### To get a int color

```dart
//The following is the same
int colorInt1 = ColorUtil.intColor('#f2f2f2');
int colorInt2 = ColorUtil.intColor('f2f2f2');
int colorInt3 = ColorUtil.intColor('#fff2f2f2');
int colorInt5 = ColorUtil.intColor('fff2f2f2');
```