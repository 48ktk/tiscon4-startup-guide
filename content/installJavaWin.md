# Javaのインストール(Windows)

## 前提条件

* [自分のPCのOSが何bitか知っていますか？](preparationForWin.md#自分のpcのbit数を知っておく)
* [ファイルの拡張子が表示されていますか？](preparationForWin.md#ファイルの拡張子表示)

## インストール

下記のサイトを参考に、**JDK8(Java SE Development Kit 8)のインストール**及び**環境変数の設定**を行って下さい。

> **注意点**
> * 2019年1月8日現在では JDK 8u192（Java SE Development Kit 8u192） が最新です。
> * 環境変数のパス設定には、ご自身がインストールした先のパスを設定してください。
> * コマンドプロンプトの開き方が分からない方は、[コマンドプロンプトの起動方法 | Windowsマシンの開発TIPS](tipsForWin.md#コマンドプロンプトの起動方法)を読んでみてください。
> * [環境変数の修正時は必ず **追記** してください！](tipsForWin.md#環境変数pathの編集)すでに書かれた内容を消してしまうと、最悪の場合PCが起動しなくなります。

* [[Windows 10 をお使いの方] JDK8(Java8)のインストール方法](https://qiita.com/RichardImaokaJP/items/a1bc723437f4be420cd2)
* [[Windows 8 をお使いの方] JDK8(Java8)のインストール方法](http://javatechnology.net/java/windows8-java8-install/)
* [[Windows 7 をお使いの方] JDK8(Java8)のインストール方法](http://javaworld.helpfulness.jp/post-24/)


## インストールできたら

[コマンドプロンプトを起動](tipsForWin.md#コマンドプロンプトの起動方法)して、

```sh
C:\Users\yourUserName> echo %JAVA_HOME%
C:\Program Files\Java\jdk1.8.0_192
```
というように `echo` コマンドが動くことと、

```sh
(Windows が 32bitの場合)
C:\Users\yourUserName> java -version
java version "1.8.0_192"
Java(TM) SE Runtime Environment (build 1.8.0_192-b12)
Java HotSpot(TM) Client VM (build 25.192-b12, mixed mode)
```

```sh
(Windows が 64bitの場合)
C:\Users\yourUserName> java -version
java version "1.8.0_192"
Java(TM) SE Runtime Environment (build 1.8.0_192-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.192-b12, mixed mode)
```
というように `java` コマンドが動くことが確認できればOKです。

またこの時、`java -version`で表示されたバージョンが、自分がインストールしたJavaのバージョンと一致していることを確認してください。
