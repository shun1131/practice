# practice

- githubの使い方を知るために上げた練習用レポジトリです
- Markdownの記法も合わせて学習していければ

***

# issueの使い方
GitHubでの課題管理はIssueを使って行うことができます。Issueには作られた順番にそれぞれ番号が振られていて、GitHub内では「**#課題番号**」と記述することで、対象番号のIssueへリンクが自動的に付与されます。また、Pull Requestにも1つの課題番号が振られます。**複数のPull Requestを1つのIssueにリンクすることで、確認が容易に行えます。**   

## (issueの書式)
```
## 概要
ここにIssueの概要を書く
What・Whyもここに書くと良いと思う

## 変更点
- [ ]
  - [ ]
  - [ ]
- [ ]

## 追加タスク
- [ ]
- [ ]
- [ ]

### 関連課題
---
関連する課題があればここにリンク形式で載せる（Backlog）

### 親課題
---
親の課題があればここにリンク形式で載せる（Backlog）

#### 備考
---
別途記載する必要があれば書く
```

## (issueの書式例)
```
## 概要
このIssueは、ABCアプリiOS版（Ver 1.2.3）実装タスクの一覧です。
クライアントからの新機能追加の要望によって、ABCユーザーが他の複数ABCユーザーと交流するための機能を実装します。

既に #120, #123 で 1 : 1　（アプリユーザー：フレンド）のユーザー交流が出来る機能が実装されています。
今回の対応で、新たに 1 : n のユーザー交流が実現できるようにする予定です。

## 変更点
- [x] [ABC-543](http://backlog/view/abc-543) 複数ユーザー交流機能の実装
  - [x] フレンド選択UIの改修
    - [x] UISpecとレイアウトを合わせる #130 #131
    - [x] ダミー画像を正規の画像に差し替える #132
  - [x] フレンド選択 / 非選択の状態管理を追加 #133
  - [x] 選択済みのフレンドが退会済みだった時のエラーを追加
    - [x] 表示するエラー文言を先方に確認 [ABC-543](http://backlog/view/abc-543)
    - [x] エラーアラートの共通クラスに退会エラーを実装 #134
- [x] [ABC-544](http://backlog/view/abc-544) 各スタート画面でのフレンド選択UIを新UIに変更 #135

## 追加タスク
- [x] [ABC-545](http://backlog/view/abc-545) お気に入りフレンドのソート順変更
- [ ] [ABC-547](http://backlog/view/abc-547) ~~iOS 9対応~~
- [x] [ABC-548](http://backlog/view/abc-548) A端末でのバグを修正

### 親課題
---
[ABC-539 iOSアプリ Version 2.1 アップデート 要望一覧](http://backlog/view/abc-539)

### 関連課題
---
[ABC-540 iOSアプリ Version 2.1 アップデート 改修要望案](http://backlog/view/abc-540)
[ABC-541 iOSアプリ Version 2.1 アップデート 改修要望スケジュール](http://backlog/view/abc-541)
[ABC-542 iOSアプリ Version 2.1 アップデート 納品物一覧](http://backlog/view/abc-542)

#### 備考
---
[ABC-547](http://backlog/view/abc-547) iOS 9対応　については、修正コストが当初の予想以上にかかるため、次期バージョンで対応することになりました。[ABC-560 iOS 9対応時の不具合について](http://backlog/view/abc-560)
```

## (実際の見た目)
## 概要
このIssueは、ABCアプリiOS版（Ver 1.2.3）実装タスクの一覧です。
クライアントからの新機能追加の要望によって、ABCユーザーが他の複数ABCユーザーと交流するための機能を実装します。

既に #120, #123 で 1 : 1　（アプリユーザー：フレンド）のユーザー交流が出来る機能が実装されています。
今回の対応で、新たに 1 : n のユーザー交流が実現できるようにする予定です。

## 変更点
- [x] [ABC-543](http://backlog/view/abc-543) 複数ユーザー交流機能の実装
  - [x] フレンド選択UIの改修
    - [x] UISpecとレイアウトを合わせる #130 #131
    - [x] ダミー画像を正規の画像に差し替える #132
  - [x] フレンド選択 / 非選択の状態管理を追加 #133
  - [x] 選択済みのフレンドが退会済みだった時のエラーを追加
    - [x] 表示するエラー文言を先方に確認 [ABC-543](http://backlog/view/abc-543)
    - [x] エラーアラートの共通クラスに退会エラーを実装 #134
- [x] [ABC-544](http://backlog/view/abc-544) 各スタート画面でのフレンド選択UIを新UIに変更 #135

## 追加タスク
- [x] [ABC-545](http://backlog/view/abc-545) お気に入りフレンドのソート順変更
- [ ] [ABC-547](http://backlog/view/abc-547) ~~iOS 9対応~~
- [x] [ABC-548](http://backlog/view/abc-548) A端末でのバグを修正

### 親課題
---
[ABC-539 iOSアプリ Version 2.1 アップデート 要望一覧](http://backlog/view/abc-539)

### 関連課題
---
[ABC-540 iOSアプリ Version 2.1 アップデート 改修要望案](http://backlog/view/abc-540)
[ABC-541 iOSアプリ Version 2.1 アップデート 改修要望スケジュール](http://backlog/view/abc-541)
[ABC-542 iOSアプリ Version 2.1 アップデート 納品物一覧](http://backlog/view/abc-542)

#### 備考
---
[ABC-547](http://backlog/view/abc-547) iOS 9対応　については、修正コストが当初の予想以上にかかるため、次期バージョンで対応することになりました。[ABC-560 iOS 9対応時の不具合について](http://backlog/view/abc-560)


# Pull Requestの方法
pullRequestを出すときは、commitにメッセージを残すことでそのブランチがマージされた時点で一緒にissueもcloseしてくれる。
#### 書き方
`$ git commit -m "fix #10"`

「fix」の部分は`close`や`closed`、`fixed`などを使うことも可能。

##### もしcommit時に書き忘れた場合は、、、
pull requestのコメント挿入箇所で`closed #10`みたいな感じで入力してそれをコメントに残しておけばおk！
