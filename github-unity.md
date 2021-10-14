# UnityのプロジェクトをGitで管理するように設定して、GitHubにPublishする手順

- Unityでプロジェクトを作成しておく
- [Ctrl]+[S]キーでシーンを保存
- [File]メニューから[Save Project]を選択して、プロジェクトを保存
- **GitHub Desktop** を起動する
- *File*メニューから、*Options*をクリック
- GitHub.comがサインイン済みの時は、*Sign out*をクリックする
- *Sign in* ボタンをクリックして、GitHubアカウントでサインイン
- *File*メニューから*New Repository*(リポジトリー)
- *Local path*の*Choose*ボタンをクリック
- *ドキュメント* > *名前のフォルダー* から、登録したいUnityのプロジェクトフォルダーをクリックして、フォルダーの選択をクリック
- *Local path*の最後のフォルダー名を選択して、切り取って、*Name*欄に貼り付け
- *Initialize this repository with a README* にチェック
- *Git ignore*欄をクリックして、`un`と入力すると*Unity*が選択されるのでクリックなどして選択
- *Create repository*ボタンをクリック
- 右上の*Publish repository*ボタンをクリック
- *Keep this code private* はチェックしたままにする
- *Publish repository*ボタンをクリック

## 提出用に、教員のアカウントを登録する
そのままだと提出しても教員から見えないので、以下の手順でリポジトリーに教員を追加する。

- GitHub DesktopのRepositoryメニューからView on GitHubを選択
- Edgeが開いたら、URLをコピーして、Google シークレットウィンドウの新しいタブを開いて、そこのURLに貼り付けて開く
- 右の方にある歯車アイコンの*Settings*をクリック
- 左の方にある*Manage access*をクリック
- GitHubのパスワードを入力
- 緑色の*Add people*ボタンをクリック
- 指示された教員のアカウントを入力して、表示された教員のアカウントをクリックして選択
- *Write*を選択したら、*Add*から始まる緑色のボタンをクリック

以上で設定完了です。

# 変更したものを反映させる手順
- Unityの*File*メニューをクリックして、*Save Scenes*を選択してシーンを保存する
- *File*メニューをクリックして、*Save Proejct*を選択してプロジェクトを保存する
- GitHub Desktopに切り替える
- *Changes*タブをクリック
- *Summary*欄に変更した内容を書く(ボタンの追加、完成など)
- *Commit to master*ボタンをクリック
- 右上の*Push origin*ボタンをクリック

