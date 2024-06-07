# ゲームプログラミング1年(2024年度入学生)

- [シラバス](https://drive.google.com/file/d/15r6K_xHBIvoYN_IRygon3yEAR5bgpe9Z/)
- [Google Meet](https://meet.google.com/bwb-njcm-udh)
- [Slack](https://datgm24.slack.com)
- [金曜 講義日程](fri.md)
- [URLなどの報告](https://docs.google.com/forms/d/e/1FAIpQLSdtCrSbaVfK9kttxBd6T577bJhaQ1RXeWdHg7h03dKhlvEm9g/viewform?usp=sf_link)
- [書く教科書の作例](https://github.com/datgm24/csharp-manual)
- その他
  - [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
  - [UnityのプロジェクトをGitで管理するように設定して、GitHubにPublishする手順](https://github.com/datgm22/design/blob/main/github-unity.md)
  - [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)
  - [昨年度の講義資料](https://github.com/datgm23/gp1)

## 参考資料
- [Unityの動作環境](https://am1.jp/tutorials/unity/spec/)
- Unityのインストールは[Cluster](https://creator.cluster.mu/cck-worldcreatetutroial-home/)を開いて、Googleアカウントでサインインして、「Unityを導入する」の手順を参照
  - 2024年度の学校のバージョンはUnity2021.3.4f1
- [Unity Learning Materials](https://learning.unity3d.jp/)
- [Paizaラーニング C#](https://paiza.jp/works/cs/primer)
- [Unityスタッフのブックマーク](https://note.com/unityjapan/m/m5978b902c2b5)
- [ハーバード大学 CS50 の日本語版翻訳プロジェクトのページ](https://cs50.jp/)
- [Koji Kita. 今年もミクシィの22新卒技術研修の資料と動画を公開します！](https://mixi-developers.mixi.co.jp/22-technical-training-5fc362a9dc41)

## 自習可能なゲームエンジン
- [ティラノビルダー](https://b.tyrano.jp/)
- [ティラノスクリプト](https://tyrano.jp/)
- [WOLF RPGエディター](https://www.silversecond.com/WolfRPGEditor/)
- [Mind Render](https://mindrender.jp/)
- [RAPTEX](https://raptex.jp/)
- [GDevelop](https://gdevelop.io/ja-jp)

## 8回目(6/14)

- 指定の座席へ移動

### 復習問題


## 予定
- 書く教科書 配列 / 繰り返し
- ゲ制班:開発キットの紹介と選択
  - 自力で使えそうなゲーム制作ツールを調べて選ぶ。管理者権限が不要なものであること。以下、候補例
    - [ティラノビルダー](https://b.tyrano.jp/)
    - [ティラノスクリプト](https://tyrano.jp/)
    - [WOLF RPGエディター](https://www.silversecond.com/WolfRPGEditor/)
    - [Mind Render](https://mindrender.jp/)
    - [RAPTEX](https://raptex.jp/)
    - [GDevelop](https://gdevelop.io/ja-jp)
  - 今週、来週でツールの選択と使い方の調査、制作するゲーム内容の検討。再来週の28日に調査結果の報告予定

## 7回目(6/7)

### 話題
- [paiza times. 自分はITエンジニアに向いている？適性を知る5つの方法](https://paiza.hatenablog.com/entry/2024/06/04/162103)

### 復習問題
「書く教科書」とGitHubの使い方のドキュメントを参照して、以下の手順に従ってVisual C#プロジェクトを作成して、GitHubで公開せよ。

※自分で作成した書く教科書がない場合は[こちら](https://github.com/datgm24/csharp-manual)を参照する。

1. Visual C#の新規プロジェクトを作成して、名前を`fukuv0607`にする
1. GitHubにPublishする
   - 参考 [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
1. フォームに以下のコントロールを作る
   - ラベル(Label)を1つ作って、フォームの中央辺りに置く。フォントサイズを24程度に大きくする
   - タイマー(Timer)を1つ作って、有効にして、Intervalを`20`にする
1. int型のインスタンス変数`vx`を定義して、`-4`を代入する
1. int型のインスタンス変数`vy`を定義して、`-4`を代入する
1. timer1の処理で、label1.Leftにvx、label1.Topにvyを足す
1. ラベルがフォームの端で跳ね返りるようにする
1. ラベルをクリックしたら、タイマーを止めて、ラベルに自分の氏名を表示する
1. すべて保存して、GitHubに反映させる
   - 参考 [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)

#### おまけ
上記ができて時間が余った人は、以下のようなことにも取り組んでみよう。成果物はGitHubでPushすれば更新される。

- 動くたびにラベルの表示を変化させる
- 跳ね返る時にラベルをスピードアップ
- ラベルに最高速度を設定
- その他、思いついたことを試す


### 内容
- 書く教科書 08.md 演習8-3のおまけから


## 6回目(5/31)

### 話題
- [paiza times. プログラミング初心者がpaizaでBランクをとった話](https://paiza.hatenablog.com/entry/2024/05/30/160000)

### 復習問題
「書く教科書」とGitHubの使い方のドキュメントを参照して、以下の手順に従ってVisual C#プロジェクトを作成して、GitHubで公開せよ。

※自分で作成した書く教科書がない場合は[こちら](https://github.com/datgm24/csharp-manual)を参照する。

1. Visual C#の新規プロジェクトを作成して、名前を`fukuv0531`にする
1. GitHubにPublishする
   - 参考 [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
1. フォームに以下のコントロールを作る
   - ラベル(Label)を1つ作って、フォームの中央辺りに置く
   - ボタン(Button)を2つ作って、上下に並べる
   - タイマー(Timer)を1つ作って、有効にする
1. int型のインスタンス変数`vy`を定義して、15を代入する
3. 上のボタンを押したら、vyに-15を代入する
4. 下のボタンを押したら、vyに15を代入する
5. timer1のプログラムに、label1.Topにvyを足す処理を実装する
6. ラベルをクリックしたら、タイマーを止めて、ラベルに自分の氏名を表示する
7. すべて保存して、GitHubに反映させる
   - 参考 [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)

#### おまけ
上記ができて時間が余った人は、以下のようなことにも取り組んでみよう。成果物はGitHubでPushすれば更新される。

- ボタンを2つ作って、左右に並べる。左を押したら、ラベルが左に動いて、右を押したら、ラベルが右に動くようにする
- 動くたびにラベルの表示を変化させる
- 動く方向に応じて、ラベルの表示を変化させる
- 動く方向に応じて、ラベルの色を変える
- その他、思いついたことを試す


### 内容
- 書く教科書 07.md 変数名から
  - [命名規則](https://am1tanaka.hatenablog.com/entry/2019/12/06/101055)


## 5回目(5/24)

### 復習問題
「書く教科書」とGitHubの使い方のドキュメントを参照して、以下の手順に従ってVisual C#プロジェクトを作成して、GitHubで公開せよ。

※自分で作成した書く教科書がない場合は[こちら](https://github.com/datgm24/csharp-manual)を参照する。

1. Visual C#の新規プロジェクトを作成して、名前を`fukuv0524`にする
1. GitHubにPublishする
   - 参考 [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
1. フォームに以下のコントロールを作る
   - ラベル(Label)を1つ
   - ボタン(Button)を4つ作って十字に配置
1. 各ボタンに、ボタンを押した方向にラベルを`20`ピクセル移動させる処理を実装する
2. ラベルをクリックしたら、ラベルに自分の氏名を表示して、ラベルの文字の色を変える。色は黒以外ならなんでもよい
1. すべて保存して、GitHubに反映させる
   - 参考 [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)

![画面例](https://raw.githubusercontent.com/datgm21/gp1/main/image.png)

画面例

#### おまけ
上記ができて時間が余った人は、以下のようなことにも取り組んでみよう。成果物はGitHubでPushすれば更新される。

- 動く方向に応じて、ラベルの表示を変化させる
- 動く方向に応じて、ラベルの色を変える
- その他、思いついたことを試す


### 内容
- 書く教科書 06.mdから
  - コントロールの表現を増やす
  - 変数(1)


## 4回目(5/17)

### 復習問題
「書く教科書」を参照して、以下の手順に従ってVisusl C#プロジェクトを作成して、Visual StudioのスクリーンショットをSlackに貼り付けよ。

※自分で作成した書く教科書がない場合は[こちら](https://github.com/datgm24/csharp-manual)を参照する。

1. Visual C#の新規プロジェクトを作成して、名前を`fukuv0517`にする
1. ボタンを3つ配置する
1. 1つ目のボタンに「氏名」と表示する。そのボタンをクリックすると、そのボタンの表示が自分の名前に変わるようにする
1. 2つ目のボタンに「消える」と表示する。そのボタンをクリックすると、そのボタンが消えるようにする
2. 3つ目のボタンに「表示する」と表示する。そのボタンをクリックすると、2つ目のボタンを表示する。2つ目のボタンが、すでに表示されていたら、なにも起きなくてよい

完成したら、以下の要領で、Slackに貼り付けて送信する。

1. [Slack](https://datgm24.slack.com)を開いて、Googleアカウントでログインする
2. プログラムを開始して、1つ目のボタンを押す
3. C#のプログラムが見えるようにウィンドウを移動させて、画面のスクリーンショットを撮ってSlackの自分のチャンネルに貼り付ける

#### スクリーンショットの撮り方

1. Windowsキー + Shiftキー + Sキーを押してスクリーンショットメニューを表示して、**全画面表示の領域切り取り**をクリック
2. Slackの「#times_自分の名前」を選択する
3. 送信欄をクリックして選択して、Ctrlキー + Vキーで貼り付ける
4. メッセージを送信する


#### おまけ
上記ができて時間が余った人は、以下のようなことにも取り組んでみよう。

- 新しいボタンを作って、クリックすると色が変わるようにする
- ラベルを作って、クリックすると表示が変わるようにする
- その他、思いついたことを実装

### 内容
- 前回のプロジェクト（cs0510）を開いて、GitHubにパブリッシュする
  - [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- 書く教科書 04.mdの(name)から


## 3回目(5/10)

### 復習問題
前回作成した「書く教科書」を参照して、以下の手順に従ってVisusl C#プロジェクトを作成して、Visual StudioのスクリーンショットをSlackに貼り付けよ。

※自分で作成した書く教科書がない場合は[こちら](https://github.com/datgm24/csharp-manual/blob/master/01.md)を参照する。

1. 書く教科書の手順に従ってVisual Studioを起動する
1. 新しいC#のプロジェクトを`fukuv0510`という名前で作成する
1. ボタンを2つ置く
1. 1つ目のボタンを押したら、自分の氏名をメッセージボックスで表示
1. 2つ目のボタンを押したら、モニターのシールに`A601-00`というように書かれている文字列を、メッセージボックスで表示

完成したら、以下の要領で、Slackに貼り付けて送信する。

1. [Slack](https://datgm24.slack.com)を開いて、Googleアカウントでログインする
2. プログラムを開始して、1つ目のボタンを押して、メッセージを表示する
3. C#のプログラムが見えるように、メッセージを移動させて、画面のスクリーンショットを撮ってSlackの自分のチャンネルに貼り付ける
4. 2つ目のボタンも同様にスクリーンショットを撮って、Slackに貼り付けて送信する

#### スクリーンショットの撮り方

1. Windowsキー + Shiftキー + Sキーを押してスクリーンショットメニューを表示して、**全画面表示の領域切り取り**をクリック
2. Slackの「#times_自分の名前」を選択する
3. 送信欄をクリックして選択して、Ctrlキー + Vキーで貼り付ける
4. メッセージを送信する

### 予定
- 書く教科書01の復習と続き
  - Visual Studioの基本操作 / 問題の解消
  - [書く教科書の作例](https://github.com/datgm24/csharp-manual)
- 確認
  - [Paizaラーニング C#](https://paiza.jp/works/cs/primer)

### 内容
- 書く教科書01の復習と続き
  - Visual Studioの基本操作 / 問題の解消
  - [書く教科書の作例](https://github.com/datgm23/csharp-manual)
- Unityの動作確認
- 独習
  - [Unity Learning Materials](https://learning.unity3d.jp/)
  - [Paizaラーニング C#](https://paiza.jp/works/cs/primer)
    - アカウントをGitHubで登録
  - プログラミング関連の良質な記事が日々増えているので、よいサイトを探してみてください！


## 2回目(4/26)

### 話題
- [unity1week online共有会 #15. Yamasho: 備忘録のススメ](https://www.youtube.com/watch?v=wmF1z5Epr1g&t=2825s)

### 内容
- 書く教科書
  - 目的
    - あとで自習するための手順を残すこと
    - 習ったことを質問せずに済むようにすること
  - 要点
    - 教員のメモを写す必要はない
    - わかりきっていることは省略してよいし、教員の説明がわかりにくければ自分流に書けばよい
    - 入力例は後ほど公開するので、間に合わなくても気にせずに講義が進みはじめたら講義に集中する
- [キー入力の練習](https://docs.google.com/document/d/1olAvmpehNVCLBdf329Ubas7FgygtEqyk5j9nyE-rTEI/edit#heading=h.ykvnuvatyepj)

## 1回目(4/19)
- ガイダンス
  - [プログラミングを学ぶ前に](https://docs.google.com/presentation/d/1mIIrnua1nf2yCiXA6KMkTUOylzPIxiUCeqQEdtHdPhc/)
  - GmailアカウントとGitHubアカウントを作成していない場合は[こちら](https://docs.google.com/document/d/16MW6maMYvt8m-60RM5wU_LzJ5r-3Hm0WTnxoBGDzxIA/)
- [講義メモ](https://docs.google.com/document/d/1olAvmpehNVCLBdf329Ubas7FgygtEqyk5j9nyE-rTEI/)
  - Visual C# / Unity

