# python for windows

PythonをWidnows10に最小構成でインストールしたのちインストールフォルダをZIPにしました。

`get-pip.py`のダウンロード
```bash
$ wget http://bootstrap.pypa.io/get-pip.py
```

`Python38.6.zip`を解凍

PATHを通すBATファイル
```
@echo off
set PATH=%~dp0\Python38
set PATH=%~dp0\Python38\Scripts
```