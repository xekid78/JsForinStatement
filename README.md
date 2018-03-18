# JsForinStatement
for – in文

## 処理
配列の内容をfor-in文を使って出力します。

## コード
```
(function () {
    'use strict';

    var team = ["佐藤", "鈴木", "田中", "岸田", "有森"];
    for (var key in team) {
        console.log(team[key] + "さん");
    }

})();
```

## 出力結果  
```
佐藤さん
鈴木さん
田中さん
岸田さん
有森さん
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Java Script |
| Js環境 | Node.js 8.10.0 |
