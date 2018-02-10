# start_wsl
:baby: はじめてのWSL

## 環境
Windows 10 （Windows Update は最新の状態にしておく）

## やること
Windows 10 でLinux開発環境を構築する（10分で）

## Windows + Linux の選択肢
### Cygwin
* LinuxっぽいシステムをWindows上で再現する（ちっちゃいLinux）
* 古くからあり使いこなせば安定していて情報も多い
* インストールが面倒 ＆ パッケージ（アプリみたいなもの）管理が面倒
* Cygwinソフト自体が重くてHDD容量を食う
* Setupのデフォルトのインストールパッケージが多すぎてHDDの息の根が止まる
* 必要なものを選別するのすら面倒
* 起動が遅い

### Virtual Box
* Windows上に完全に分離した領域を作成しOSをインストールする
* お好みの Linux OS を完全に純正のふるまいで動かすことができる
* OS上でOSを常に動かしている = CPU・メモリの要求が多い（重い）
* HDDのパーティションを切る必要がある（たいがい多めに切るから容量を食う）
* 初期インストールにコツがいる（Linux にくわしい人が周りにいないときつい）
* いちいち起動するから実質遅い

### WSL
* **W**indows **S**ubsystem for **L**inux
* ほぼ純正のふるまい
* なんてったって MicroSoft 公式
* つまりサポート権がつきます（企業の方には重要）
* 市民権を得ている「Ubuntu」が10分で使える

## WSLインストール資料
[シス管系女子](http://system-admin-girl.com/comic/begins/sp-wsl/)

注：非常にわかりやすいのですが惜しいことに会社で読むには勇気必至な萌え漫画です。紳士の方は必要に応じて同じことが書かれている下の**WSLインストール**を読んでください。

## WSLインストール

