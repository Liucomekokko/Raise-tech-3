# 第三回目課題
### WEB アプリケーションとは
### WEB アプリケーションでよく使う（見かける）言葉　　
### システム（アプリケーション）開発の流れ
### 外部ライブラリと公正管理の重要性
### Gem と　Bnudler
### アプリケーションサーバー
### Rails によるWebアプリケーションの起動 
### DB と　SQL

#### ⚫️AP サーバーについて調べてみましょう。
1.AP サーバーの名前とバージョンを確認してみましょう。　⇨　　rails 7.0.4  
2.AP サーバーを終了させた場合、引き続きアクセスできますか？結果を確認して、また AP サーバーを起動してください。    
　　　　　　![起動スクリーンショット 2023-10-11 14 54 49](https://github.com/Liucomekokko/Raise-tech-5/assets/139355789/884b885a-2efc-449f-8424-43baeb35e9c6)
　　 　　![停止スクリーンショット 2023-11-16 15 44 40](https://user-images.githubusercontent.com/139355789/284146208-092de213-2875-4948-ab10
494e804a1112.png)
   ![再起動スクリーンショット 2023-11-16 12 34 40](https://github.com/Liucomekokko/Raise-tech-5/assets/139355789/03a14861-addb-4339-9dd3-aa4f78317116)

#### ⚫️DB サーバーについて調べてみましょう。　　
１.サンプルアプリケーションで使った DB サーバー（DB エンジン）の名前と、今 Cloud9 で動作しているバージョンはいくつか確認してみましょう。  
2.DB サーバーを終了させた場合、引き続きアクセスできますか？  
　　　　　![mysql スクリーンショット 2023-11-15 15 24 35](https://github.com/Liucomekokko/Raise-tech-5/assets/139355789/31d82ad0-d7a0-4506-9007-c1b09993b114)


#### ⚫️Rails の構成管理ツールの名前は何でしたか？確認してみてください。

#### ⚫️今回の課題から学んだことを報告してください。　　
* WEBアプリケーションについての学習、こんな風に情報を開示していたとは思わなかった。さらにここから、「HTTPの基礎」の動画を視聴して知識不足を補う。聞きなれない単語が多くて覚え切れるのだろうか不安になりつつも視聴。　　

* システム（アプリケーション）開発の流れでは開発モデルについて。V字W字モデル他にも「ウォーターフォール」「アジャイル」「スクラム」があるのを学んだ。
* Ruby on Railsを学ぶ。文章上だと便利なシステムで手軽に操作が行えるアプリケーションであること。Rails アプリケーションというのは PC のような実行ファイル 1 つではなく、「ファイルの集まり」なので形としては「フォルダー」。
* 外部ライブラリと構成管理の重要性では外部ライブラリとは「他の誰か」が作った「便利機能」の集まり。インフラエンジニアはプログラマーが書いたアプリケーションをサーバーで動かすことを業務の 1 つとして必要な知識。外部ライブラリは便利な反面インストールの数が大容量になってくると、管理が大変になる。ここで構成管理ツールを活用することでアプリケーションに必要なライブラリを
入手し、構成を簡単に再現する事ができる。

* Gem と Bundler　
Gem と呼ばれるものは Ruby で使われるパッケージングされたアプリケーション、モジュール（部品）の事。構成管理Bundler　、「Gem が動作する為に必要なプログラム」や、「Gem が必要な Gem の種類、バージョン」などを管理するツール。
* アプリケーションサーバーとはRuby や Java のようなプログラムで作られたアプリケーションを実行する為に必要なサーバー（「サービスを提供するもの」である、本来のサーバー）
最近はフレームワークを使う際に「組み込み」と言われる内蔵型のアプリケーションサーバーもあり、とくにサーバーを意識することなくアプリケーションの起動や実行ができるようになっている。
* DB（データベース） と SQL（ストラクチャード・クエリ・ランゲージ）
DB とはデータを整理して検索しやすくした情報の集まり。SQLとはデータベース言語の一つで、データベース言語とは「データベースを操作するための言語」のこと。
CRUD（クラッド）とは、ほとんど全てのコンピュータソフトウェアが持つ永続性[1]の4つの基本機能のイニシャルを並べた用語。その4つとは、Create（生成）、Read（読み取り）、Update（更新）、Delete（削除）である。ユーザインタフェースが備えるべき機能（情報の参照/検索/更新）を指す用語としても使われる。
SQL はAmazon Athena(SQL で S3 にあるログを横断検索できるサービス)でも活用したりするので、インフラエンジニアとして使わないかのというと、ときどき使うことがある。できると良い。

内容が、第二回目より濃くなって、講義動画とスライドだけでは学習内容が圧倒的に自信には足りない。アプリケーションの起動はいくら真似ても同じようにはいかない。順番に環境設定を行いながらもなかなか起動の画面に到達できずモヤモヤ。。。これは何をしているのかを一個づつ見ていきながらも起動できず。エラーについても、正解に辿り着けないことに焦りを感じる。質問しても逆に疑問が増えてしまう。　こんな感じ？のニュアンスだけではうまくいかないことを改めて痛感した。

