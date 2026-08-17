# インストール手順

Hula-jp を Python のライブラリから制御するには、`pyhula` をインストールする必要があります。
`pyhula` は、レッドクリフ社の Hula-jp 公式サイトからダウンロードできます。

## Hula-jp のインストールパッケージを入手する

Hula-jp 公式サイト（レッドクリフ社）にアクセスします。

https://redcliff-inc.co.jp/service/drone-sales-and-subscription/hula/

サイトから「Hula-jp Python[3.12.10] インストールパッケージ」をダウンロードしてください。

![代替テキスト](image/pythoninstall0.png)

ダウンロードした zip ファイルを展開します。

![代替テキスト](image/pythoninstall1.png)

> **注意:** 動作を保証するため、Python のバージョンは必ず **3.12.10** を使用してください。

## Python 3.12.10 をインストールする

展開したフォルダ内に、Python をインストールするための実行ファイル（`.exe`）が含まれています。
以下のファイルを実行してください。

```bash
python-3.12.10-amd64.exe
```

![代替テキスト](image/pythoninstall2.png)

インストーラーが起動したら、**「Add python.exe to Path」にチェックを入れて**からインストールを進めてください。
（このチェックを入れておくと、ターミナルから `python` コマンドを直接実行できるようになります。）

![代替テキスト](image/pythoninstall3.png)
![代替テキスト](image/pythoninstall4.png)
![代替テキスト](image/pythoninstall5.png)

画面の指示に従って、インストールを完了させてください。

## pyhula をインストールする

インストールが完了したら、展開したフォルダ内で右クリックし、**「ターミナルを開く」** を選択します。

![代替テキスト](image/pythoninstall6.png)
![代替テキスト](image/pythoninstall7.png)

開いたターミナル上で、以下のコマンドを実行して `pyhula` をインストールします。

```bash
pip install pyhula-1.1.8-cp312-cp312-win_amd64.whl
```

![代替テキスト](image/pythoninstall8.png)

必要なライブラリは、このコマンドによって自動でインストールされます。

![代替テキスト](image/pythoninstall10.png)


最後に、ターミナルに以下のように表示されれば、インストールは完了です。

```text
Successfully installed pyhula...
```
