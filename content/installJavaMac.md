# Javaのインストール(Mac)

## 前提条件

なし

## インストール

下記のサイトを参考に、**JDK8(Java SE Development Kit 8)のインストール**を行って下さい。

> **注意点**<br>
> 2019年1月8日現在では JDK 8u192（Java SE Development Kit 8u192） が最新です。

[【初心者でもすぐわかる】JDKのインストール方法 Mac編](https://eng-entrance.com/java-install-jdk-mac)

## インストールできたら

[Terminalを起動](tipsForMac.md#terminalの起動方法) して
```sh
> java -version
java version "1.8.0_192"
Java(TM) SE Runtime Environment (build 1.8.0_192-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.192-b12, mixed mode)
```
というように `java` コマンドが動くことが確認できればOKです。

またこの時、`java -version`で表示されたバージョンが、自分がインストールしたJavaのバージョンと一致していることを確認してください。
