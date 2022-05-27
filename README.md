# TASK3
課題
- DBサーバー MYSQL Server version: 8.0.29 MySQL Community Server
- APサーバー　Rails 6.1.3.1 application 
- WEBサーバー Puma version: 5.6.4 
- 言語　(ruby 2.7.2-p137) ←　2.6から上げてしまいました。
- 構成管理　("Birdie's Version")　Bundler version 2.3.14
- APサーバー・No application seems to be running here! 発生
- 再起動後問題なく接続確認
- DBサーバー・Can't connect to local MySQL server through socket '/var/lib/mysql/mysql.sock' (2)　発生
- 再起動後問題なく接続確認


# 今回の実習について
- 構築関係を行うのが初めてだったので、かなりいろいろな場所で躓いた。
- 実際にデバックをやってみても、いろいろとCLOUD９上にエラー内容が書かれているのであろうがそれを見つけて、調べて、違ったらまた調べてと解決まで一歩一歩踏みしていく感覚があった。
- RUBYに関しても使ったことがほとんどないので、どういうことが書かれているだとかがいまだによくわかっていないので、その辺を勉強するようにしたいと思います。

- Railsの構成に関しても、フレームワーク思考という覚えるべきことがでてきたので、徐々に慣れていき、ゆくゆくは自由に使いこなしていきたい。
- RUBYのVerをあげてしまったので、最初Railsを起動したときにエラーが出た。" rvm --default use 2.7.2"    で解消？

- ＤＢに関しても、今回は既存を抜いてインストールする項目だったので、いろいろとパターンがあるのでは対応しきれないと思う。この辺りも実践をふまえて覚えていきたい。
- アプリケーションサーバーを動かすだけで、いろいろなソフトやプログラムが動いており一つでも違うとエラーになって動かない。プログラミングはその通りにしか動かないを体感した。


# 結論
知識・経験が足りなさすぎると実感した課題でした。自分の思考がＳＴＯＰしている時間が結構多かったので、冷静にエラーなどを調べていけば動くので、そのあたりは重視したいです。
