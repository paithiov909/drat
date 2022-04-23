# Drat Repo

> Packages in this repository are available under their respective license.

## これは何？

RからMeCabを呼ぶためのバイナリパッケージを頒布している[drat](https://github.com/eddelbuettel/drat)リポジトリです。

次のパッケージを頒布しています。MeCabは入っていなくてもパッケージのインストールはできますが、パッケージを使用するにはMeCabの辞書が必要です。

- [paithiov909/RcppMeCab](https://github.com/paithiov909/RcppMeCab)

## 使い方

```r
drat::addRepo("paithiov909")
install.packages("RcppMeCab")
# or
update.packages()
```
