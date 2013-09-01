# ビジネスアプリケーション演習
subtitle
:   Webプログラマになるための大特訓

author
:    中鉢欣秀

institution
:    AIIT

theme
:   rabbit


# 授業の目的

- ビジネスアプリケーションを構築するための基礎力としてのプログラミング力を身につけます。
- 分散型 PBL を実施する上で必要となる知識やツールの使い方を基礎から学びます。

# 授業の計画

* hoge
* baka

# デモンストレーション

- Vagrant up & ssh
- rails new
- git commit
- GitHub
- heroku

# 本日の目標

- VirtualBox/Vagrant
- 仮想マシンの構築

# 開発環境

- Ruby 2.0.0p247
- Rails 4.0.0

# 仮想マシンのインストール

- VirtualBox
- vagrant

# 仮想マシンへのログイン

- vagrant ssh

# Synced Folder

- cd /vagrant

# Editor

- [GNU Emacs - GNU Project - Free Software Foundation (FSF)](http://www.gnu.org/software/emacs/)
- [welcome home : vim online](http://www.vim.org/)
- [Sublime Text: The text editor you'll fall in love with](http://www.sublimetext.com/)

# GitHubHerokuアカウント

<!--
- [GitHub](https://github.com/)
- [Heroku | Cloud Application Platform](https://www.heroku.com/)
-->

# 公開鍵の登録(Heroku)

- heroku login
  - メールアドレスとパスワードを入力
- heroku keys:add
  - ssh鍵を生成
  - ssh鍵をherokuに登録

# 公開鍵の登録(GitHubの設定)

- GitHub
- ssh公開鍵の登録

# Rails

- cd /vagrant
- rails new my_app -T
- rails server

# Port forward

- Host:3000 -> Guest:3000
