# Weiguan Lite

[Weiguan(围观)](https://weiguan.app/) is a social media app developed using Google's Flutter UI framework. This repository contains the core code of weiguan app, just for learning and studying purpose.

[相关视频课程](https://blog.jaggerwang.net/jw-course-flutter-mobile-app-development/)

## Feature Video

[![Weiguan Lite](http://i3.ytimg.com/vi/TN_p9I55PzI/maxresdefault.jpg)](https://youtu.be/_ZjPmv3Mzwc)

## Screenshots

<p float="left">
  <img src="https://user-images.githubusercontent.com/1255011/51241776-81de8980-19b9-11e9-87e3-edbd24c50ef1.jpeg" width="180">
  <img src="https://user-images.githubusercontent.com/1255011/51241779-83a84d00-19b9-11e9-8352-35d1f6e028fa.jpeg" width="180">
  <img src="https://user-images.githubusercontent.com/1255011/51241781-83a84d00-19b9-11e9-9408-e5f831cd2c76.jpeg" width="180">
  <img src="https://user-images.githubusercontent.com/1255011/51241782-8440e380-19b9-11e9-9a11-06994fe701aa.jpeg" width="180">
</p>

## How to run

### Install flutter sdk

Please refer to flutter official document [Install](https://flutter.io/docs/get-started/install).

### Clone repository

```bash
git clone git@github.com:jaggerwang/jw-weiguan.git && cd jw-weiguan
```

### Install pub packages

```bash
flutter packages get
```

### Connect a device or run a simulator

Connet your Android or iOS device to your computer or run a simulator using the following commands.

```bash
$ emulator -list-avds
9.0-1440p
$ emulator -avd 9.0-1440p
```

### Build and run app

```bash
flutter run
```

This will run app in production mode, it will disable debug log and request real api server. If you want to run in development mode, you can specify the entry-point file to `lib/main_dev.dart`.

```bash
flutter run -t lib/main_dev.dart
```

> The video player can not work on iOS simulator, you should use a real device.

## Changelog

### 2019-05-25

1. Upgrade Flutter SDK to v1.5.

### 2019-01-14

1. First release.
