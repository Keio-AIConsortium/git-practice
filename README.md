# git-practice
"git-practice"は、SIGの新メンバーがgitやGitHubの必要最低限の操作を学習するためのリポジトリです。

# ファイル構成
## README.md
このファイルでは、このリポジトリを初めて見る人に向けてリポジトリの概要や使い方、注意点などをわかりやすく説明します。

## .gitignore
このファイルでは、共有に不必要なファイルをGitHubにpushしないように制御することができます。
特に、mac OSのローカル環境では、".DS_Store"というファイルが自動で生成されますが、このファイルをそのままGitHubにpushするとエラーになってしまいます。
本リポジトリでは、このファイルの一行目に”.DS_Store"と記述することでエラーの発生を防いでいます。
詳しくはこちら（https://qiita.com/shunsa10/items/47f646655f5416501f29)