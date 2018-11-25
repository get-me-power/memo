# daisuzu

## プラグインを標準機能で置き換える

## 普段どうやってVimを使ってきたか

- kaoriya vimをwindows XPで使った

- 基本normalmodeで操作

## 標準機能に移行

脱neocomplete

Vim標準の補完方法で置換した

- Omni補完

- キーワード補完

- 辞書補完

ユーザーが辞書を予め設定して、それを補完してくれる


## 脱neobundle

packageを使用

packpathを使用

遅延読み込みにも対応している

git clone でpackpathを指定

vim scriptでも置換可能

backgroundloadingというものがある

先にvimを起動してからvimのプラグイン情報を読み取る

