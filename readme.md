# python for windows

PythonをWidnows10に最小構成でインストールしたのちインストールフォルダをZIPにしました。

[to Python3.9.5+](https://github.com/a-nakajima-at-shokuryu/python-for-windows-2021)

`get-pip.py`のダウンロード
```bash
$ wget http://bootstrap.pypa.io/get-pip.py
```

`Python38.6.zip`を解凍

PATHを通すBATファイル
```
@echo off
set PATH=%~dp0\Python38;%PATH%
set PATH=%~dp0\Python38\Scripts;%PATH%
```
