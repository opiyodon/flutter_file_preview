# flutter_file_preview

PDF, Word, Excel, and PowerPoint Viewer For Flutter App

## Getting Started

This is a `Flutter` plugin for Office file preview.

It supports previewing local and online PDF, Word, Excel, and PowerPoint files.

For `Android`, it uses [TBS (Tencent Browsing Service)](https://x5.tencent.com/tbs/guide/sdkInit.html).

For `iOS`, it uses the native `WKWebView`.

![demo](./screenshot/demo.gif)

## Usage

Add the following to your `pubspec.yaml`:

```yaml
file_preview:
    git:
        url: git://github.com/aliyoge/flutter_file_preview.git
```

### Use in your file:

```dart
import 'package:flutter_file_preview/flutter_file_preview.dart';

// Preview an online file
FlutterFilePreview.openFile("http://www.xxx.com/1245.pdf", title: 'Online PDF');

// Preview a local file
FilePreview.openFile("/storage/emulated/0/Download/20180715.pdf", title: 'Local PDF');
```

## Frequently Asked Questions
For help getting started with Flutter, view our online documentation.

For help on editing plugin code, view the documentation.