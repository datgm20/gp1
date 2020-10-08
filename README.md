## 注：10/1に講義がある前提で進めましたが休講でした。次回は10/8です
## 課題の締め切りも、再来週の10/8に延長します。2週間じっくり取り組んでください


# ゲームプログラミング1年生-2020年度入学生
- [シラバス](https://1drv.ms/x/s!Anf4PowESFUjg_tlVWmEGx-XJvimOA?e=qdTo1h)

# 参考URL
- [paiza開発日誌. 初心者がC#の基本からアプリ・ゲーム開発まで学ぶための記事まとめ](https://paiza.hatenablog.com/entry/2020/06/09/%E5%88%9D%E5%BF%83%E8%80%85%E3%81%8CC%23%E3%81%AE%E5%9F%BA%E6%9C%AC%E3%81%8B%E3%82%89%E3%82%A2%E3%83%97%E3%83%AA%E3%83%BB%E3%82%B2%E3%83%BC%E3%83%A0%E9%96%8B%E7%99%BA%E3%81%BE%E3%81%A7%E5%AD%A6%E3%81%B6)
- [SOLID原則](https://docs.google.com/document/d/1TVdyioxBuSwz89Vh92ziADulEB47P5IMolytxopdBrM/)
- [Udemy. ユニティちゃんが教える！初心者向けUnity講座](https://www.udemy.com/course/unity-chan-tutorial-01/)

# 授業資料
- [質問](https://meet.google.com/yav-uzhd-wjq)
  - [質問の仕方](https://www.youtube.com/watch?v=nE6FesKgPio&list=PLdRD_lOLS4j3FvkAqc5ddKHEH25GYMH3f)
- [講義ふり返り動画-13 9/24](https://youtu.be/ptECX_lncVc)
- [講義ふり返り動画-12 9/17](https://youtu.be/27hOQ0Uh0zE)
- [講義ふり返り動画-11前半 9/10](https://youtu.be/fryTKYIyvyA)
- [講義ふり返り動画-11後半 9/10](https://youtu.be/p2xio5tc4R0)
- [講義ふり返り動画-10 9/3](https://youtu.be/Keut4_hNPp8)
- [講義ふり返り動画-09 8/27](https://youtu.be/W7IdAceQGpc)
- [講義ふり返り動画-08 8/6](https://youtu.be/xX8IwGMyMdw)
- [講義ふり返り動画-07 7/22](https://youtu.be/Tf7VsyorBXs)
- [講義ふり返り動画-06 7/16](https://youtu.be/dSVp5NED9as)
- [講義ふり返り動画-05 7/9](https://youtu.be/xWXGXjIOmtY)
- [講義ふり返り動画-04 7/2](https://youtu.be/FlBQB4v2qFw)
- [講義ふり返り動画-03 6/25](https://youtu.be/GvGI0bRRpdA)
- [講義ふり返り動画-02 6/18](https://youtu.be/OXJdRh83uiw)

## 環境設定
- [Unity2019.3.15f1インストール手順](https://youtu.be/QlQYoIuif6s)
- [Visual Studio 2019 CommunityでC#を開発するための設定手順](https://youtu.be/UBHH6Nx0R-o)
- [GitHub Desktopのインストール手順](https://youtu.be/fFqQuozo9RM)

# 後期1回目

## 課題の発表
- Meetで画面共有して、ランダムで決めた順で成果発表
  - 実行して動作を確認
  - コードを開いて、実装したポイントを紹介
  - 作業日時のメモを公開

## 課題の発表
- GitHubで最新版をコミットしてプッシュしておく
- 作業日時の提出
  - テキストファイルの場合、 `X:\2020年\ゲーム学科\Student\ゲームプログラム1年\gp1yoketoruvs20` に自分の名前のフォルダーを作成して、その中に提出
  - Googleドキュメントで作成した場合は、 [こちら](https://forms.gle/EfD6xBZ6rY8Ex7Kb8) を開いて、氏名と リンクを知っている人が閲覧 できるようにした共有URLを貼り付けて送信

## 予定
- 完成手順紹介
- Unity版よけとるの開発

---

# 13回目
## 課題の確認
- 前回の最後に指示した以下の課題を開いて、開始したら、Meetで画面共有する

## 今日までの課題
- ゲーム開始時に、すべてのvxとvyに、`-SpeedMax`～`SpeedMax`の範囲の乱数を代入
- ゲーム中のみ、敵とアイテムを移動
- 敵とアイテムは、フォームの端で跳ね返す

## 次回10/8までの課題
- 今日までの作業が完了しなかった人は、そこまで自力で終わらせる
- アイテムとクリア
  - アイテムの数を管理する処理を実装
  - アイテムの残り数を表示
  - アイテムを取ったら減らし、0以下になったらクリアさせる
  - 残りのアイテム数が正しく減らないはずなので、それの原因を考えて、対策をする
- タイム
  - タイムを管理する変数を定義
  - ゲーム中、タイムを減らし、表示を更新する
  - タイムが0になったらゲームオーバー
- ハイスコア
  - ハイスコアを記録する変数を定義
  - クリア時の残り時間がハイスコアより大きければ、ハイスコアを更新
  - ハイスコアをクリアやタイトルで表示
- その他、不具合を治す
- プロジェクトを開いて考えたり作業している時や、ふり返り動画を見ている時の日時を、Googleドキュメントやスマホのメモ帳などに記録しておいて、次回、すぐに提出できるようにする


## 予定
- [ミニゲームの製作](https://github.com/datgm20/csharp-manual/blob/master/16.md)
- [作業メモ](https://docs.google.com/document/d/1kI4-tORWc4josCHCQRHewEsNQ72IgYwsZ4rm-ZQ_wHU/)

## よけとるvs2020TODOリスト
- [x] 状態遷移を完成させる
  - [x] ゲームオーバーの初期化
  - [x] クリアの初期化
  - [x] スタートへボタンの実装
- [x] キャラクター管理のための定義
  - [x] キャラクター数を定数で定義
  - [x] キャラクターインデックスを定数で定義
  - [x] アイテムの残りの数を管理する変数を定義
- [x] ゲームの初期化
  - [x]タイムの初期化
  - [x] プレイヤーの作成
  - [x] 敵の作成
  - [x] アイテムの作成
- [x] タイムの更新
- [x] プレイヤーの操作
  - [x] マウス座標にくっつけてプレイヤーラベルを移動
- [x] 敵とアイテムの移動
  - 移動と跳ね返り
- [x] プレイヤー(マウスカーソル)と敵やアイテムとの当たり判定
  - とりあえずメッセージ表示
- [x] ぶつかった相手を見分ける
  - 方法の検討と実装
- [x] ゲームオーバーへ
- [x] アイテムを取る
  - [x] 問題発生！原因を考える
  - [x] 解決策を検討する
- [x] ハイスコア判定
- [x] キャラクターの大きさを設定する
  - ひな型のラベルを定義
  - ひな型のラベルの設定をキャラクターにコピーする

## 時間があったら
- [ベクトルの基礎](https://docs.google.com/document/d/1bptMOCYRdX4_IP8uhToeYloXgRh7C9v-nC1yLI8EFSE/edit#heading=h.d99a40vmi848)


# 12回目
## 次回までの課題
- ゲーム開始時に、すべてのvxとvyに、`-SpeedMax`～`SpeedMax`の範囲の乱数を代入
- ゲーム中のみ、敵とアイテムを移動
- 敵とアイテムは、フォームの端で跳ね返す

## 前期の残り
- 10/1にまとめの総合復習課題を実施予定

## 前回の復習の確認
- 正解 12名(+2)
  - +ボーナス 9名(+-0)
- 軽微なミス 2名

## 内容
- gp20でログイン
- GitHubにパブリッシュしていた yoketoruvs20 をクローン(Clone)する
  - 先週休んでいたか、作業を完了できなかった人は以下をやる
    - yoketoruvs20 がすでにあったら、Settingsメニューから削除しておく
    - https://github.com/datgm20/yoketoruvs20 を開く
    - 右上の Fork ボタンをクリック
    - 自分のアカウントへの Fork が完了したら、Codeボタンをクリックして、 Open with GitHub Desktop をクリック
    - ドキュメントの自分の名前のフォルダーにクローンする 
- [ミニゲームの製作](https://github.com/datgm20/csharp-manual/blob/master/16.md)
- [作業メモ](https://docs.google.com/document/d/1kI4-tORWc4josCHCQRHewEsNQ72IgYwsZ4rm-ZQ_wHU/)

## よけとるvs2020TODOリスト
- [x] 状態遷移を完成させる
  - [x] ゲームオーバーの初期化
  - [x] クリアの初期化
  - [x] スタートへボタンの実装
- [ ] キャラクター管理のための定義
  - [x] キャラクター数を定数で定義
  - [x] キャラクターインデックスを定数で定義
  - アイテムと敵の残りの数を管理する変数を定義
- [ ] ゲームの初期化
  - タイムの初期化
  - [x] プレイヤーの作成
  - [x] 敵の作成
  - [x] アイテムの作成
- [ ] タイムの更新
- [x] プレイヤーの操作
  - [x] マウス座標にくっつけてプレイヤーラベルを移動
- [ ] 敵とアイテムの移動
  - 移動と跳ね返り
- [ ] プレイヤー(マウスカーソル)と敵やアイテムとの当たり判定
  - とりあえずメッセージ表示
- [ ] ぶつかった相手を見分ける
  - 方法の検討と実装
- [ ] ゲームオーバーへ
- [ ] アイテムを取る
  - 問題発生！原因を考える
  - 解決策を検討する
- [ ] ハイスコア判定


# 11回目

## 前回の復習の確認
- 正解 10名(+4)
  - +ボーナス 9名(+5)
  - 軽微なミス 2名(+-0)

## 復習問題
- [指示書](https://github.com/datgm20/gp1/wiki/11%E5%9B%9E%E7%9B%AE%E5%BE%A9%E7%BF%92%E5%95%8F%E9%A1%8C)

## 内容
- 繰り返し(for文)～沢山のものを動かす（２）～ の残っている演習をやって仕上げる

## 演習
- [ミニゲームの製作](https://github.com/datgm20/csharp-manual/blob/master/16.md)
- [作業メモ](https://docs.google.com/document/d/1kI4-tORWc4josCHCQRHewEsNQ72IgYwsZ4rm-ZQ_wHU/)


# 10回目

## 前回の復習の確認
- 正解 6名(-4)　※内容的には実質いつも通り
  - +ボーナス 4名(-2)
  - 軽微なミス 2名(+1)

## 復習問題 兼 今日の演習用プロジェクト
- [指示書](https://github.com/datgm20/gp1/wiki/10%E5%9B%9E%E7%9B%AE%E5%BE%A9%E7%BF%92%E5%95%8F%E9%A1%8C)

## 内容
- ラベル3つを独立させて移動させる
- 配列～沢山のものを動かす（１）～ から
  - [3つにしたプロジェクト](https://github.com/tanakaedu/v0903/archive/v0.1.0.zip)
    - 上記をクリックしてダウンロード
    - ダウンロードが完了したら、クリックして開く
    - 開いたエクスプローラーのドキュメントを右クリックして、新しいウィンドウで開く を選択
    - 自分のフォルダーを開く
    - v0903-0.1.0 フォルダーをドラッグして、自分のフォルダーの任意の場所にドロップして展開する
    - 自分のフォルダーにドロップしたv0903-0.1.0フォルダーを開く
    - v0903.sln をダブルクリックして開く


# 9回目
## 話題
- [スイカ割り](https://unityroom.com/games/suikawarigame)

## 前回の復習の確認
- 正解 10名(+-0)
  - +ボーナス 6名(+-0)
  - 軽微なミス 1名(-1)

## 復習問題 兼 今日の演習用プロジェクト
- [指示書](https://github.com/datgm20/gp1/wiki/9%E5%9B%9E%E7%9B%AE%E5%BE%A9%E7%BF%92%E5%95%8F%E9%A1%8C)

## 内容
- [分岐(2) その2～複数の条件判断～](https://github.com/datgm20/csharp-manual/blob/master/11.md) から
  - [復習問題に跳ね返りを加えたForm1.cs](https://github.com/datgm20/v0827/blob/master/v0827/Form1.cs)


---

# 8回目
## 前回の復習の確認
- 正解 10名(-2)
  - +ボーナス 6名(-3)
  - 軽微なミス 2名

## 復習問題　兼　今日の演習用プロジェクト
- [復習問題](https://github.com/datgm20/gp1/wiki/8%E5%9B%9E%E7%9B%AE%E5%BE%A9%E7%BF%92%E5%95%8F%E9%A1%8C)


## 内容
- 分岐(1) if文(その1～基本形～)
  

# 7回目
## 前回の復習の確認
- 正解 12名(-2)
  - +ボーナス 9名(+1)

## 復習問題
- [復習問題](https://github.com/datgm20/gp1/wiki/7%E5%9B%9E%E7%9B%AE%E5%BE%A9%E7%BF%92%E5%95%8F%E9%A1%8C)

## 内容
- 07.md 変数～動的なプログラム～ の続き(u0716)から


# 6回目
## 話題
- [Unityステーション. ユーザコミュニティトーク](https://www.youtube.com/watch?v=S9kKTFABNFA)
  - [unityroomのnaichiさんのツイート](https://twitter.com/naichilab/status/1281553273195913216)

## 前回の復習の確認
- 正解 14名
  - +ボーナス 8名
- フォルダー間違いなどの軽微なミス 3名
- 前回提出したfukuv0709をダウンロードして読み込んでみる
  - フォルダーの登録間違いをするとどうなるか

## 復習問題
- Visual C#の新規プロジェクトを作成して、名前を`fukuv0716`にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm20/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- フォームに以下を設置
  - ラベル(Label)を1つ
  - テキストボックス(TextBox)を2つ置いて、どちらのTextも1を設定
  - タイマー(Timer)を1つ
- タイマーに以下のプログラムを書く
  - 一方のテキストボックスの値をint型に変換して、ラベルのLeftに足す
  - もう一方のテキストボックスの値をint型に変換して、ラベルのTopに足す
- タイマーが動くように設定する
- できたらコミットして、Pushする
- 上記ができた人向けのボーナス課題
  - ボタンを4つ、十字に配置して、ボタンを押したらその方向にラベルの移動方向が変わるようにする

## 内容
- 07.md 変数～動的なプログラム～ からをUnityで実施


# 5回目
## 前回の提出結果
- 正解 8名
  - ＋ボーナス 2名
- ほぼ問題なし 10名
- 前回と今回のどちらか一方でも正解 11名

## 前回の復習
- Visual C#の新規プロジェクトを作成して、名前を`fukuv0709`にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm20/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- 以下のものを作る
  - ラベル(Label)を1つ
  - ボタン(Button)を4つ作って十字に配置
  - ボタンを押した方向にラベルが動くようにする
- できたらコミットして、Pushする

## 内容
- GitHubの左上のオクトキャットアイコンをクリックして、csharp-manual リポジトリーを開く
- 06.md コントロール(Control)～表現を増やす～ から
- [Unityでの物の動かし方](https://docs.google.com/document/d/1Su0trfKxB2iLfGdxt1s7pJr76NFwqwdw-pbDhaCrtvE/)


# 4回目
## 話題
- [Unity. Learn Premium が誰でも無料でご利用できるようになりました](https://blogs.unity3d.com/jp/2020/06/23/learn-premium-is-now-available-to-everyone-at-no-cost-forever/?utm_campaign=unitynews_japan_newsletter_2020-6-JP-June-Newsletter&utm_content=2020-6-JP-Newsletter-game&utm_medium=email&utm_source=Eloqua)
- [Monaca Education. Webフロントエンド開発の学習サービス](https://edu.monaca.io/)

## Unityのインストールが成功した人は、以下から登録
- [PC保有アンケート](https://forms.gle/u4fcc8GzKpDAeaPv9)

## 前回復習の振り返り
- fukuv0625のIssuesに「問題ありませんでした」とある満点の人 **7名**
  - 復習に問題なかった人 **10名**
- 間違い例
  - ボタンが3つ実装されていなかった
  - GitHubに登録するフォルダー間違い
  - 講義中のv0625を最後にコミット＞プッシュしていなかった

操作に慣れて、満点を目指しましょう！！


## エラー時の動作の確認
先週の講義で、エラーなのにプログラムが実行されたり、紹介しているものと違うエラーウィンドウが表示される場合は以下を確認する。

- ツールメニュー＞オプションを選ぶ
- 左の一覧から プロジェクトおよびソリューション の左の三角をクリックして開く
- ビルド/実行 を選択
- 実行時に、ビルドまたは配置のエラーが発生したとき の欄を、 **起動しない** に変更して、OKをクリック


## 復習
- Visual C#の新規プロジェクトを作成して、名前を`fukuv0702`にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm20/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- ボタンを2つ配置する
- ボタンを押すと、ボタンが消える、ボタンの表示が変わるようにする
- できたらコミットして、Pushする


## 内容
- GitHubを開いてSign inしたら、csharp-manual を開く
- 05.md 計算


# 3回目
## 内容
- GitHubを開いてSign inしたら、csharp-manual を開く
- 03.mdをクリックして開く

## 復習
- Visual C#の新規プロジェクトを作成して、名前を`fukuv0625`にする
- ボタンを3つ配置する
- ボタンを押すと、何かを表示したり、動いたり、3つのボタンそれぞれが違う動作をするようにする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm20/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
  - これで提出完了

## 内容
- 新規にプロジェクトを作成して、名前を`v0625`とする
- GitHubにパブリッシュする
- 書く教科書の3から
- 作業が終わったら、[プロジェクトの更新を、GitHubに反映させる](https://github.com/datgm20/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92%E3%80%81GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B) で、最終結果を


# 2回目
## 講義ノート
自分で完成させるC#教科書を作る。

- GitHubを開いて、サインイン
- [書く教科書のオリジナルリポジトリー](https://github.com/tanakaedu/csharp-manual) を右クリックして、新しいタブで開く
- 右上の Fork ボタンをクリック
  - Fork(フォーク)とは
    - GitHubのリポジトリーを、自分のリポジトリーにコピーする作業のこと
    - 参考：GitHubは、オープンソースプロジェクトの開発が主目的のサービスです。
    開発者が公開しているオープンソースのリポジトリーをコピーすることで、元のプロジェクトと切り離して自由に改変することができます。
    手元で開発をして有効な改良ができたら、Pull Request(プルリクエスト=組み込むことを要求)で改良内容を元のプロジェクトに送信します。
    プルリクエストが届いたら、開発元の人は要求内容をチェックして、問題がなければプロジェクトに取り込むことができます。
    この流れで、世界中の各地で、同時に、一つのプロジェクトの開発が行われています。

以上で、自分のGitHub上に書く教科書がコピーされました。必要な項目を自分で書き加えていき、完成させてください。

## 内容
- Visual Studioの基本操作
- 昨日のミニゲームの残り


# 1回目
## 講義ノート
- https://docs.google.com/document/d/16NzK1ESd0MJFnHQ-otKFKyw8mqWHgnl1egtj1usWrug/

## 予定
- GitHubのメール確認・・・昨日、登録できなかった人は、メールアドレスを間違えているので修正を！
- GitHubのSettingsで、名前を設定
- ガイダンス / [シラバス](https://1drv.ms/x/s!Anf4PowESFUjg_tlVWmEGx-XJvimOA?e=qdTo1h)の確認
- Visual Studioを試す
  - 起動 / プロジェクト作成 / ボタンの配置 / メッセージの表示
- Unityを試す
  - アカウント作成 / 起動 / プロジェクト作成 / オブジェクトの作成 / 着色 / メッセージの表示 / マウス操作
- 独習
  - [Paizaラーニング C#](https://paiza.jp/works/cs/primer)
    - アカウントをGitHubで登録する
  - [ドットインストール Unity入門(2018.3.4f1)](https://dotinstall.com/lessons/basic_unity_v2)とUnityを触る / 学習サイトについて
- [タイピング練習](https://www.e-typing.ne.jp/)

## 演習
- タイピング結果を報告する
  - [報告用のスプレッドシート](https://docs.google.com/spreadsheets/d/10VcsR850aqWKN-C6tEuSExmgqET3EMH81KonU-yz7aI/)

