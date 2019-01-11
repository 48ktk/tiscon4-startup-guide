# Gitのインストール(Mac)

## [brew](http://brew.sh/index_ja.html)のインストール
macOS 用パッケージマネージャーを先にインストールします。<br>
[Terminalを起動](tipsForMac.md#terminalの起動方法)してインストールされているか確認します。
```sh
> which brew
/usr/local/bin/brew
```
というように表示されたらスキップしてください。 <br>
`brew not found` と言われた場合は以下のステップを実行してください。
```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
を実行して終了したらOKです。処理が終了した時に明らかにエラーと分かるような赤い文字などが出ていたら、エラー内容と共にインターン実施担当者まで問い合わせてください。

## Gitのインストール
brewを使用してGitをインストールします。<br>
[Terminalを起動](tipsForMac.md#terminalの起動方法)して

```sh
brew install git
```
してください。処理が終了した時に :beer: のアイコンが出ていたらOKです。

## インストールできたら
[Terminalを起動](tipsForMac.md#terminalの起動方法)して

```sh
git --version
git version 2.16.2
```
というように `git` コマンドが動くことが確認できればOKです。
