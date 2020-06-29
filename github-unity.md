# UnityのプロジェクトをGitで管理するように設定して、GitHubにPublishする手順

- Unityでプロジェクトを作成しておく
- [Ctrl]+[S]キーでシーンを保存。最初の保存の時は、任意の名前をつける
- [File]メニューから[Save Project]を選択して、プロジェクトを保存
- **GitHub Desktop** を起動する
- *File*メニューから、*Options*をクリック
- GitHub.comがサインイン済みの時は、*Sign out*をクリックする
- *Sign in* ボタンをクリックして、GitHubアカウントでサインイン
- *File*メニューから*New Repository*(リポジトリー)
- *Local path*の*Choose*ボタンをクリック
- *ドキュメント* > *名前のフォルダー* から、登録したいUnityのプロジェクトフォルダーを開いて、フォルダーの選択をクリック
- *Local path*の最後のフォルダー名を選択して、切り取って、*Name*欄に貼り付け
- *Initialize this repository with a README* にチェック
- *Git ignore*欄をクリックして、`un`と入力すると*Unity*が選択されるのでクリックなどして選択
- *Create repository*ボタンをクリック
- 右上の*Publish repository*ボタンをクリック
- *Keep this code private* はチェックしたままにする
- *Publish repository*ボタンをクリック

## 提出用に、教員のアカウントをチームに入れておく
そのままだと提出しても教員から見えないので、以下の手順でリポジトリーに教員を追加する。

- Chromeのシークレットウィンドウを起動
- github.com を開く
- サインインする
- 作成したリポジトリーを開く
- 右の方にある*Settings*をクリック
- 左の方にある*Collaborators*をクリック
- 要求されたらパスワードを入力(要求がなければ次へ)
- *Collaborators*欄のテキストボックスに`tanakaedu`と入力して、表示される`tanakaedu Yu Tanaka*を選択したら、*Add collaborator*ボタンをクリック
- 追加した*Yu Tanaka*の横に表示される*Copy invite link*ボタンをクリックして、URLの隣のボタン(![コピーボタン](images/copy-button.png))をクリックしてコピー
- 指示されたGoogleシートなどに、コピーしたURLを貼り付ける(Ctrl+Vキー)

以上で設定完了です。

# 変更したものを反映させる手順
- Unityの*File*メニューをクリックして、*Save Scenes*を選択してシーンを保存する
- *File*メニューをクリックして、*Save Proejct*を選択してプロジェクトを保存する
- GitHub Desktopに切り替える
- *Changes*タブをクリック
- *Summary*欄に変更した内容を書く(ボタンの追加、完成など)
- *Commit to master*ボタンをクリック
- 右上の*Push origin*ボタンをクリック
