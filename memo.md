# 5月20日

`flutter create 名前`で新しいappを作成

### maindarnの中身を簡略化したコード
```dart
import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
 
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Demo',
      home: Scaffold(
        appBar: AppBar(
          title: Text('Hello Flutter!'),
        ),
        body: Text(
          'Hello Flutter World!!',
          style: TextStyle(fontSize:32.0),
        ),
      ),
    );
  }
}
```