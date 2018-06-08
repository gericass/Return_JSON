# WebAPIサーバを建てて見よう！  
## ゴール
- 下記の条件を満たしていること  
- ブラウザ(ChromeとかMicrosoft Edgeとか)のURLに、下記アドレスを入力
> http://127.0.0.1:5000/ (:5000は変わる可能性あり)
- 実行結果  
> {"Result":"Hello World"}  

## 備考
- 利用する言語は問いません
- 手順も問いませんので、結果だけ同様でしたら構いません
- 高橋さんは、取り組まなくても大丈夫です

## ダウンロード方法【重要】  
- ページ右側の[Clone or Download]のURLをコピー
- 下記コマンドを実行
> git clone さっきのURL

## 課題の進め方【重要】
- Return_JSONフォルダの中に、自分のローマ字表記のフォルダを作成(ex. Ryo_Tozawa)
- ブランチを作成
> git branch Ryo_Tozawa
- ブランチを切る
> git checkout Ryo_Tozawa
- 作成したファイルのみをGit管理に追加
> git add Ryo_Tozawa
- Ryo_Tozawaの中で、課題のプログラムを作成（※作成したフォルダの外は絶対に汚さないように）

## 提出方法【重要】
- 増えたファイルを追加
> git add * (必ず作成したファイル内で実行)
- コミット
> git commit -m "clone前からの変更点を記載"
- プッシュ
> git push (git pushではダメだこっちのコマンドを打てとエラーが出る場合あり)
- 無事プッシュが成功したらGitHubのホームページを確認
> ページ左側のBranch: masterを押した時、自分のBranchがあれば成功！
- プルリクエスト
> ページ上部のPull Requestを選択し、New pull requestで、masterにがちゃんこする旨を記載しよう
- 管理者(今回は戸澤)が、がちゃんこして課題終了です！

## 何か困ったら
- 使う言語を決めたら戸澤に一言相談してくれると、開発用ソフトを一緒に探します！