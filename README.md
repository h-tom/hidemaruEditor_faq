# 秀丸エディタＱ＆Ａ集(第８版)

![Hidemaru Q and A](hide_by2.png)


## はじめに
秀丸エディタＱ＆Ａ集の8版です。
対象は以下になります。

-   秀丸エディタVer.8以降
-   OSはWindows 7以降


配布ファイルは以下の２つありますが、内容は同じです。

- chm(Microsoft HTML Help)形式
- HTML形式

通常は、chm(Microsoft HTML Help)形式 を使用してください。

HTML形式は、ミラーリングや、引用などに使用してください。
(hmindex0.html がトップページになります)

### 履歴

-   [履歴の最後へ](#last_history)

#### 2016/11/13

-   変更
    -   全体を秀丸エディタVer.8を対象にした内容へ変更
    -   @niftyのフォーラムはサービス終了のため、記述を削除
    -   リンク等で接続できない箇所は、リンクを解除
-   新規
    -   [第II部〜知っていると便利な秀丸の機能　あいまい検索](2_fuzzy.html)
    -   [第II部〜知っていると便利な秀丸の機能　変換モジュール](2_convert.html)
    -   [第III部〜秀丸マクロのいろはにほへと　秀丸エディタウィンドウの管理(タブモード編)](3_tabmode.html)
    -   \[HME0097A\] [●ファイルを秀丸エディタで編集したのに、反映されていない](HME0097A.html)
    -   \[HMM0081A\] [●「DLLがロードされてないのにdllfunc関数が使われました」と表示される](HMM0081A.html)

#### 2016/11/19

-   [検索](./2_find.html)
    複数行にマッチする検索についての注意点追加。
-   [正規表現について](./4_regular.html)
    参考文献に「諸説 正規表現」を追加。
-   [HMM0081A](./HMM0081A.html)
    DLLのロード失敗に関して、64bit版での注意点を追加。
-   [Ｑ＆Ａ集その他の原稿の寄稿要領](./youryou.html)
    製作場所を変更。
-   [編集場所について](./hidpatio.html)
    製作場所を変更。
-   画像ファイル(png)を変更。全体のファイルサイズを多少減らす。

#### 2016/11/21

-   [ではでは](./byebye.html)を更新。
-   [HME0001A](./HME0001A.html)を変更。
-   [HME0006A](./HME0006A.html)コミュニテックスのリンク部分修正。

#### 2016/11/22

-   [HME0053A](./HME0053A.html)を更新。画像を追加。

#### 2016/11/23

-   [HME0001A](./HME0001A.html)を更新。「前へ」のリンク先修正
-   [第V部〜マクロから呼び出すＤＬＬの作り方](./make_dll.html)を更新。一部画像を変更。

#### 2016/11/24

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を更新。Ver.8.66が公開されたので変更。
-   [HME0097A](./HME0097A.html)を更新。「次へ」のリンク先修正

#### 2016/11/26

-   [HME0047A](./HME0047A.html)を更新。説明修正。
-   [HME0093A](./HME0093A.html)を更新。画像および説明追加。
-   [HMM0003A](./HMM0003A.html)、[HMM0004A](./HMM0004A.html)を更新。マクロパスの設定方法を修正
-   [HME0051A](./HME0051A.html)を更新。画像を変更。バージョンアップで変更した箇所。
-   説明にある「秀丸」を「秀丸エディタ」へなるべく変更。
    (秀丸ファイラーClassicや、秀丸パブリッシャーに関する記述も追加する予定なので)
    
#### 2016/12/01

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を更新。Ver.8.67が公開されたので変更。

#### 2016/12/04

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を更新。Ver.8.67が公開されたので変更。
-   [編集場所について](./hidpatio.html) 閉鎖の経緯を追加。

#### 2016/12/11

-   [HME0016C](./HME0016C.html)を更新。リンク文字を修正。
-   [HME0016E](./HME0016E.html)を更新。「古い情報なので削除」のスタイルを設定。
-   [HME0018A](./HME0018A.html)を更新。[HME0017A](./HME0017A.html)へのリンクを追加。

#### 2016/12/22

-   [第II部〜知っていると便利な秀丸の機能　置換](2_replace.html)、
    [変換モジュールを使った置換](2_replace.html#SUPPLEMENTATION-3)で変換モジュールの多重化について追記。

#### 2016/12/23

-   8版リリース

-----------------------------------------------------------------------------------------------------------------


#### 2016/12/31

-   [第VI部〜秀丸エディタ拡張モジュール](hmindex6.html) を追加。
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](6_publisher.html) を追加。

#### 2017/01/04

-   [第II部〜知っていると便利な秀丸の機能　ファイルマネージャ枠](2_filemanager.html) を追加。

#### 2017/01/09

-   [第III部〜秀丸マクロのいろはにほへと　マクロ内での「\\」や特殊文字の使い方](3_yenmk.html) を修正。
    chm作成用makeファイル修正。
    
    元のmarkdownファイルは、Shift_JISに含まれない文字を数値文字参照で記述していたが、
    html変換時に文字へ変換されていたため、chm作成用にShift_JIS変換するとき削除されてしまっていた。
    (html変換時に、数値文字参照のままだと思ってた)
    
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](6_publisher.html) を修正。
    画像ファイルを修正。BOXの制限を追加。

#### 2017/01/12

-   [第II部〜知っていると便利な秀丸の機能　ファイルマネージャ枠](2_filemanager.html) を修正。

#### 2017/02/17

-   [第II部〜知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を追加。

#### 2017/02/18

-   [第III部〜秀丸マクロのいろはにほへと　マクロ内での「\\」や特殊文字の使い方](3_yenmk.html) を修正。
    Ver.8.66以降から使える、「Raw文字列リテラル」や、「逐語的リテラル文字列」について追記

#### 2017/02/26

-   [第II部〜知っていると便利な秀丸の機能　アウトプット枠](2_output.html) を追加。

#### 2017/03/05

-   [HME0031A](./HME0031A.html)を更新。説明修正、画像変更。
-   [HME0058A](./HME0058A.html)を更新。説明修正、画像変更。

#### 2017/03/06

-   [HME0058A](./HME0058A.html)を更新。画像変更。

#### 2017/03/07

-   [HME0091A](./HME0091A.html)を更新。誤記修正。

#### 2017/03/12

-   [第III部〜秀丸マクロのいろはにほへと　秀丸エディタウィンドウの管理(タブモード編)](3_tabmode.html)を更新。H1〜4のID属性修正。

#### 2017/04/02

-   [第III部〜秀丸マクロのいろはにほへと　自動起動マクロ](3_autostartmacro.html)を追加。

#### 2017/04/03

-   [第II部〜知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を修正。誤記修正。
-   \[HME0060A\] [●カーソル行を下線で強調表示したい？](HME0060A.html) を修正。
-   \[HME0079A\] [●.hilight に \\t や \\n は使えるか？](HME0079A.html) を修正。

#### 2017/04/10

-   [第II部〜知っていると便利な秀丸の機能　文字数の計算](2_wordcount.html) を追加。

#### 2017/04/16

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](6_publisher.html) を変更。
-   [第II部〜知っていると便利な秀丸の機能　grep/タグジャンプ](2_grep.html)を変更
-   [第V部〜マクロから呼び出すＤＬＬの作り方](make_dll.html)を変更。リンクを修正。
-   \[HME0097A\] [●ファイルを秀丸エディタで編集したのに、反映されていない](HME0097A.html)を修正。

#### 2017/04/17
-   \[HMM0081A\] [●「DLLがロードされてないのにdllfunc関数が使われました」と表示される](./HMM0081A.html)を変更。
    DLLを実行するためのファイルが足りない場合を追加。

#### 2017/04/19
-   [第I部〜秀丸エディタＱ＆Ａ集　Ｑ＆Ａ集の表記について](s_hyouki.html)を変更。
-   [第V部〜マクロから呼び出すＤＬＬの作り方](make_dll.html)を変更。リンクを追加。
-   \[HME0035A\] [●縦書きや段組みなど、きめ細かな設定で印刷したい](HME0035A.html)を変更。

#### 2017/04/20

-   [第II部〜知っていると便利な秀丸の機能　文字数の計算](2_wordcount.html) を変更。

#### 2017/04/25

-   [秀丸エディタの各ＯＳ毎の最新版](s_saisin.html) を変更。
-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](3_macrov8.html)を変更。

#### 2017/04/29

-   \[HME0078B\] [●設定を他のパソコンに移行したい](HME0078B.html)を修正。

#### 2017/04/30

-   \[HME0078A\] [●各種設定を移行するためファイルに保存したい](HME0078A.html)を修正。

#### 2017/05/03

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](6_publisher.html) を変更。テンプレートの保存場所の確認方法追加。
-   \[HME0078A\] [●各種設定を移行するためファイルに保存したい](HME0078A.html)を修正。秀丸パブリッシャー追加。
-   [第IV部〜テキスト編集を極める！！　正規表現について](./4_regular.html)を変更。後方一致指定(肯定先読み)を使った、条件の論理積を追加。

#### 2017/05/06

-   [第II部〜知っていると便利な秀丸の機能　複数選択](2_multiselect.html) を追加。

#### 2017/05/07

-   [第III部〜秀丸マクロのいろはにほへと　マクロ登録数の制限突破大作戦](3_moremacro.html) を変更。キーの表記を修正。

#### 2017/05/17

-   [第II部〜知っていると便利な秀丸の機能　カラーマーカー](2_colormarker.html) を追加。

#### 2017/05/19

-   \[HMM0014A\] [●「\¥」の使い方](HMM0014A.html)を修正。Raw文字列リテラル/逐語的リテラル文字列へのリンクを追加。
-   \[HMM0060A\] [●「キーワード」とは？](HMM0060A.html)を修正。ヘルプサイトへのリンクを追加。
-   [第II部〜知っていると便利な秀丸の機能　カラーマーカー](2_colormarker.html) を修正。

#### 2017/05/21

-   [第II部〜知っていると便利な秀丸の機能　あいまい検索](2_fuzzy.html)を修正。

#### 2017/05/23

-   [第II部〜知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を修正。折りたたみと、部分編集の説明と画像を追加。

#### 2017/05/28

-   内容に変更なし。html5の構文チェックの内容を反映。

#### 2017/05/30

-   [秀丸エディタＱ＆Ａ集〜はじめに　このヘルプの内容](s_naiyou.html) を変更。
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](6_publisher.html) を変更。

#### 2017/06/02

-   \[HME0074A\] [●特定のファイルを開くと文字化けする](HME0074A.html)を修正。イメージ部分変更。
-   \[HMM0069A\] [●マクロ処理中にダイアログボックスを出す方法](HMM0069A.html)を修正。

#### 2017/06/06

-   [第III部〜秀丸マクロのいろはにほへと　マクロを実行してみよう](3_macro.html)を修正。【１】導入前の準備を修正。
-   \[HMM0003A\] [●マクロファイルの置き場所](HMM0003A.html)を修正。
-   \[HMM0004A\] [●マクロファイルの管理](HMM0004A.html)を修正。
-   \[HMM0005A\] [●マクロファイル用のフォルダは必須か？](HMM0005A.html)を修正。

#### 2017/06/12

-   [第II部〜知っていると便利な秀丸の機能　文字数の計算](2_wordcount.html) を変更。

#### 2017/06/17

-   \[HME0018B\] [●瞬間起動機能がメモリやシステムリソースを圧迫する](HME0018B.html)を修正。
-   \[HME0026A\] [●スタートアップフォルダが見つからない](HME0026A.html)を修正。
-   \[HME0027A\] [●起動時に秀丸が現れて邪魔だ](HME0027A.html)を修正。
-   \[HME0040A\] [●外部ヘルプファイルの起動方法](HME0040A.html)を修正。
-   \[HME0042A\] [●拡張子が「KEY」のファイルは何？](HME0042A.html)を修正。
-   \[HME0047A\] [●外部ヘルプファイルの起動方法](HME0047A.html)を修正。
-   \[HME0048A\] [●「ワード」や「一太郎」等のファイルを開きたい](HME0048A.html)を修正。
-   \[HME0051A\] [●漢字コードの使い分け](HME0051A.html)を修正。
-   \[HME0065A\] [●改行だけの行を削除したい](HME0065A.html)を修正。
-   \[HMM0014A\] [●「\¥」の使い方](HMM0014A.html)を修正。

#### 2017/06/24

-   8.1版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2017/07/09

-   [第II部〜知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を追加。

#### 2017/07/10

-   [第II部〜知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。

#### 2017/07/14

-   [第II部〜知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。
-   markdown -> html 変換makefileを変更。
    chm作成用にUTF-8 -> Shift_JIS変換するとき、半角カナが全角カナに変換されていたのを修正。
    
    -   [第II部〜知っていると便利な秀丸の機能　あいまい検索](2_fuzzy.html)
    -   [第II部〜知っていると便利な秀丸の機能　変換モジュール](2_convert.html)

#### 2017/07/21

-   [第II部〜知っていると便利な秀丸の機能　検索](2_find.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。
-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](3_macrov8.html)を修正。V.8.73を追加。

#### 2017/07/31

-   [第II部〜知っていると便利な秀丸の機能　検索](2_find.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。

#### 2017/08/11

-   [秀丸スペルチェックアドイン](6_spellcheck.html) を追加。

#### 2017/08/12

-   [秀丸スペルチェックアドイン](6_spellcheck.html) を修正。
-   \[HME0006A\] [●質問したい時にはどうするの？](HME0006A.html)コミュニテックスのリンク部分修正。

#### 2017/08/14

-   \[HMM0032A\] [●「検索での表示」の設定による動作の違い](HMM0032A.html)を修正。タイトル変更および、説明を追加。
-   \[HMM0041A\] [●文字列型変数の扱う文字列の限界](HMM0041A.html)を修正。
-   \[HMM0044A\] [●文字列型変数中の半角小文字を大文字に](HMM0044A.html)を修正。
-   \[HMM0045A\] [●文字列型変数中の半角大文字を小文字に](HMM0045A.html)を修正。

#### 2017/08/20

-   [第II部〜知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を修正。
-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](3_com_object.html) を追加。

#### 2017/08/21

-   [第II部〜知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を修正。
-   [第II部〜知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。誤記修正。
-   [第IV部〜テキスト編集を極める！！　正規表現について](4_regular.html)を修正。誤記修正。

#### 2017/08/22

-   [第IV部〜テキスト編集を極める！！　タグ付き正規表現とは?](4_tagreg.html)を修正。

#### 2017/08/26

-   [第III部〜秀丸マクロのいろはにほへと　秀丸マクロで文字列を編集する](3_string.html)を修正。

#### 2017/08/29

-   [第II部〜知っていると便利な秀丸の機能　検索](2_find.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　置換](2_replace.html)を修正。

#### 2017/08/30

-   [秀丸スペルチェックアドイン](6_spellcheck.html) を修正。

#### 2017/09/06

-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](3_com_object.html) を修正。

#### 2017/09/13

-   [第II部〜知っていると便利な秀丸の機能　複数選択](2_multiselect.html) を修正。
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](6_publisher.html) を修正。

#### 2017/09/17

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](2_custom.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　変換モジュール](2_convert.html)を修正。

#### 2017/09/21

-   [第II部〜知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。

#### 2017/09/23

-   [第III部〜秀丸マクロのいろはにほへと　マクロのデバッグについて](3_debug.html)を追加。

#### 2017/10/01

-   [第II部〜知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。

#### 2017/10/09

-   [秀丸エディタの各ＯＳ毎の最新版](s_saisin.html) を変更。
-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](3_macrov8.html)を変更。
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸エディタ持ち出しキット](6_takeout.html)を追加。

#### 2017/10/15

-   \[HME0016C\] [●表示できない記号がある](./HME0016C.html)を更新。画像を変更。

#### 2017/11/01

-   Markdown → html 変換に使用している pandoc をバージョンアップ。
    仕様変更に伴い各部を修正

#### 2017/11/03

-   Markdown → html 変換に使用している pandoc をバージョンアップ。
    仕様変更に伴い各部を修正その２

-   \[HME0052A\] [●テキストファイルは常に秀丸で開きたい](./HME0052A.html)を更新。画像を追加。


#### 2017/11/04

-   Markdown → html 変換に使用している pandoc をバージョンアップ。
    仕様変更に伴い各部を修正その３


#### 2017/11/07

-   Markdown → html 変換に使用している pandoc をバージョンアップ。
    仕様変更に伴い各部を修正その４

-   \[HME0065A\] [●改行だけの行を削除したい](./HME0065A.html)を更新。リンクを追加。
-   \[HME0087A\] [●異なるフォルダの秀丸が実行されているので起動できません](./HME0087A.html)を更新。

#### 2017/11/08

-   Markdown → html 変換に使用している pandoc をバージョンアップ。
    仕様変更に伴い各部を修正その５

#### 2017/11/12

-   \[HME0083A\] [●検索/置換の「選択した範囲内のみ」の動作](./HME0083A.html)を更新。
-   [第IV部〜テキスト編集を極める！！　正規表現について](./4_regular.html)を更新。JRE.3D.DLLについて追記。

#### 2017/11/19

-   [第II部〜知っていると便利な秀丸の機能　変換モジュール](./2_convert.html)を修正。

#### 2017/11/23

-   [第III部〜秀丸マクロのいろはにほへと　マクロ内での「\\」や特殊文字の使い方](./3_yenmk.html)を修正。
-   \[HMM0003A\] [●マクロファイルの置き場所](./HMM0003A.html)を更新。
-   \[HMM0029A\] [●マクロファイルの存在確認](./HMM0029A.html)を更新。
-   \[HMM0041A\] [●文字列型変数の扱う文字列の限界](./HMM0041A.html)を更新。
-   \[HMM0076A\] [●重複行の削除](./HMM0076A.html)を更新。
-   [第V部〜マクロから呼び出すＤＬＬの作り方](./make_dll.html)を更新。

#### 2017/11/24

-   \[HMM0024A\] [●サブルーチンからの戻り値($$return,##return)をそのまま使う](./HMM0024A.html)を修正。
-   \[HMM0043A\] [●(無題)秀丸からのマクロ実行](./HMM0043A.html)を修正。
-   \[HMM0047A\] [●特定のファイルを開く](./HMM0047A.html)を修正。
-   \[HMM0056A\] [●複数のウィンドウ間を移動したい](./HMM0056A.html)を修正。
-   \[HMM0058A\] [●setactivehidemaru 文の引数](./HMM0058A.html)を修正。


#### 2017/11/25

-   以下のページのマクロ部分を修正。コードブロックの場合に不要なエスケープがあったので修正。
    
    -   [第III部〜秀丸マクロのいろはにほへと　マクロを実行してみよう](./3_macro.html)
    -   [第III部〜秀丸マクロのいろはにほへと　秀丸マクロで文字列を編集する](./3_string.html)
    -   [第III部〜秀丸マクロのいろはにほへと　秀丸エディタVer.3.00 マクロ関連の変更履歴](./3_macrov3.html)
    -   [第III部〜秀丸マクロのいろはにほへと　マクロ登録数の制限突破大作戦](./3_moremacro.html)
    -   [第III部〜秀丸マクロのいろはにほへと　サブルーチンについて](./3_sub.html)
    -   [第III部〜秀丸マクロのいろはにほへと　秀丸エディタウィンドウの管理](./3_window.html)
    -   [\[HMM0016A\] [●openfile のオプションでの注意項目](./HMM0016A.html)
    -   [\[HMM0018A\] [●openfile の /(x,y,cx,xy) オプションでのマクロの動作時の注意](./HMM0018A.html)
    -   [\[HMM0046A\] [●keypressed文による分岐のスケルトン](./HMM0046A.html)
    -   [\[HMM0075A\] [●浮動小数点数版秀丸との互換性](./HMM0075A.html)
    -   [\[HMM0077A\] [●マクロでの文字列の比較](./HMM0077A.html)

-   [第III部〜秀丸マクロのいろはにほへと　秀丸エディタVer.8 マクロ関連の変更履歴](./3_macrov8.html)の誤記修正
-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html)を変更。

#### 2017/11/26

-   [第III部〜秀丸マクロのいろはにほへと　秀丸エディタウィンドウの管理](./3_window.html)で画像を変更。

#### 2017/12/05

-   [第I部〜秀丸エディタＱ＆Ａ集　Ｑ＆Ａ集の表記について](./s_hyouki.html)を修正。設定について追記。
-   [第I部〜秀丸エディタＱ＆Ａ集　よくある質問](./yokuaru.html)を修正。行がつながってしまっていた箇所があったので修正。
-   \[HME0016C\] [●表示できない記号がある](./HME0016C.html)を修正。
-   以下のページで、設定画面の「上級者向け設定」がチェックされていないと表示されない項目がある事を追記。
    -   [\[HME0031A\] [●文字コードの設定がヘン？ ](./HME0031A.html)
    -   [\[HME0051A\] [●漢字コードの使い分け](./HME0051A.html)
    -   [\[HME0074A\] [●特定のファイルを開くと文字化けする](./HME0074A.html)
-   \[HME0081A\] [●秀丸でハイパーリンク ](./HME0081A.html) の画像を変更。

#### 2017/12/09

-   [第II部〜知っていると便利な秀丸の機能　grep/タグジャンプ](./2_grep.html)を更新
-   [第IV部〜テキスト編集を極める！！　正規表現について](./4_regular.html)を修正。

#### 2017/12/10

-   [第III部〜秀丸マクロのいろはにほへと　マクロのデバッグについて](./3_debug.html)を更新。

#### 2017/12/11

-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html) を修正。

#### 2017/12/17

-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html) を修正。
-   id属性に「日本語」が使われている箇所があったので、各部を修正。

#### 2017/12/19

-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を更新。

#### 2017/12/20

-   \[HME0003A\] [●「送金登録作業」の手順](./HME0003A.html)を更新。
-   \[HME0004A\] [●パスワードを忘れた/紛失した](./HME0004A.html)を更新。

#### 2017/12/23

-   \[HME0006A\] [●質問したい時にはどうするの？](./HME0006A.html)を更新。
-   \[HMM0032A\] [●「検索での表示」の設定による動作の違い](./HMM0032A.html)を更新。
-   8.2版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2018/01/11

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を修正。(Windows 8/8.1のメインストリームサポート終了)
-   [第III部〜秀丸マクロのいろはにほへと　マクロ内での「\\」や特殊文字の使い方](./3_yenmk.html)を修正。

#### 2018/01/20

-   \[HME0041A\] [●速いはずの秀丸が遅い!?](./HME0041A.html)を修正。
-   \[HME0051A\] [●漢字コードの使い分け](./HME0051A.html)を修正。

#### 2018/01/22

-   \[HME0027A\] [●起動時に秀丸が現れて邪魔だ](./HME0027A.html)を変更。

#### 2018/01/23

-   \[HME0041A\] [●速いはずの秀丸が遅い!?](./HME0041A.html)を修正。

#### 2018/01/25

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を変更。

#### 2018/01/28

-   スタイルシートの対応、表記の統一など、各部を修正。

#### 2018/01/29

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を変更。64bit版を対象にした説明である事を追記。
-   [はじめに　このヘルプの内容](./s_naiyou.html)を修正。対象OSと秀丸エディタのバージョンを追加。

#### 2018/01/30

-   \[HME0083A\] [●検索/置換の「選択した範囲内のみ」の動作](./HME0083A.html)を修正。

#### 2018/02/04

-   [第II部〜知っていると便利な秀丸の機能　アウトライン解析の枠](./2_outline.html) を修正。

#### 2018/03/02

-   へプルファイルサイト、過去ログサイトのURLを変更

#### 2018/03/04

-   \[HME0053A\] [●「常駐秀丸の終了」がわかりません](./HME0053A.html)を修正。

#### 2018/03/10

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。

#### 2018/03/18

-   へプルファイルサイト、過去ログサイトのURLを変更(http → https へ)
-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。

#### 2018/03/25

-   \[HME0097A\] [●ファイルを秀丸エディタで編集したのに、反映されていない](./HME0097A.html)を修正。

#### 2018/03/26

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。

#### 2018/03/28

-   サイトー企画のwebサイトのURLを変更(http → https へ)

#### 2018/04/04

-   \[HME0095A\] [●検索した単語を全て強調表示したい](./HME0095A.html)を変更。


#### 2018/04/07

-   \[HME0051A\] [●漢字コードの使い分け](./HME0051A.html)を修正。
-   [第III部〜秀丸マクロのいろはにほへと　マクロを実行してみよう](./3_macro.html)を修正。新ダイアログ追加。

#### 2018/04/09

-   [第III部〜秀丸マクロのいろはにほへと　マクロを実行してみよう](./3_macro.html)を修正。ストアアプリ版について追記。

#### 2018/04/11

-   [第III部〜秀丸マクロのいろはにほへと　マクロを実行してみよう](./3_macro.html)を修正。マクロ登録について追記。

#### 2018/04/15

-   \[HME0094A\] [●TeXとの連携](./HME0094A.html) を修正。

#### 2018/04/23

-   [第IV部〜テキスト編集を極める！！　起動オプションを使ってみよう](./4_cmdlin.html)を修正。バッチファイル修正。
    (for文の箇所をコマンドプロンプトで実行させると、終了まで待機しないので start で終了待ちするように修正)

#### 2018/04/25

-   [第IV部〜テキスト編集を極める！！　起動オプションを使ってみよう](./4_cmdlin.html)を修正。誤記修正。
-   [秀丸エディタＱ＆Ａ集　第VI部〜秀丸エディタ拡張モジュール](./hmindex6.html)のページの「titleタグ」を修正。
    それに伴い各部を修正。

#### 2018/04/29

-   [第II部〜知っていると便利な秀丸の機能　変換モジュール](./2_convert.html) を修正。
-   [第II部〜知っていると便利な秀丸の機能　カラーマーカー](./2_colormarker.html) を修正。

#### 2018/04/30

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　ファイルマネージャ枠](./2_filemanager.html) を修正。
-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。

#### 2018/05/01

-   [第II部〜知っていると便利な秀丸の機能　複数選択](./2_multiselect.html) を修正。
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。

#### 2018/05/02

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸スペルチェックアドイン](./6_spellcheck.html) を修正。

#### 2018/05/03

-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　grep/タグジャンプ](./2_grep.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　単語補完](./2_wordcomplete.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　アウトライン解析の枠](./2_outline.html)を修正。
-   [第III部〜秀丸マクロのいろはにほへと　自動起動マクロ](./3_autostartmacro.html)を修正。
-   [第III部〜秀丸マクロのいろはにほへと　ビット演算を極める](./3_bit.html)を修正。
-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html)を修正。
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸エディタ持ち出しキット](./6_takeout.html)を修正。

#### 2018/05/04

-   [第III部〜秀丸マクロのいろはにほへと　マクロ登録数の制限突破大作戦](./3_moremacro.html)を修正。
-   [第III部〜秀丸マクロのいろはにほへと　秀丸マクロで文字列を編集する](./3_string.html)を修正。
-   [第III部〜秀丸マクロのいろはにほへと　サブルーチンについて](./3_sub.html)を修正。

#### 2018/05/05

-   [第IV部〜テキスト編集を極める！！　正規表現について](./4_regular.html)を修正。
-   \[HME0003A\] [●「送金登録作業」の手順](./HME0003A.html)を修正。
-   \[HME0004A\] [●パスワードを忘れた/紛失した](./HME0004A.html)を修正。
-   \[HME0005A\] [●パスワードを書いても良いの？](./HME0005A.html)を修正。
-   \[HME0006A\] [●質問したい時にはどうするの？](./HME0006A.html)を修正。
-   \[HME0007A\] [●問い合わせ時の必要事項](./HME0007A.html)を修正。
-   \[HME0010A\] [●会議室では誰が回答してくれるの？](./HME0010A.html)を修正。
-   \[HME0011A\] [●アンインストール方法\[秀丸エディタ\]](./HME0011A.html)を修正。
-   \[HME0020A\] [●正規表現の上検索がヘン!?](./HME0020A.html)を修正。
-   \[HME0037A\] [●TOVER31.COMの実行方法は？](./HME0037A.html)を修正。
-   \[HME0044A\] [●出力（Excelの表にすぐ利用できる形の出力）](./HME0044A.html)を修正。
-   \[HME0055A\] [●複数パソコンに同じ「キー割り当て」をしたい](./HME0055A.html)を修正。
-   \[HME0059A\] [●行と行の間隔を変えたい](./HME0059A.html)を修正。
-   \[HME0083A\] [●検索/置換の「選択した範囲内のみ」の動作](./HME0083A.html)を修正。
-   \[HME0085A\] [●grepで文字コードの自動認識](./HME0085A.html)を修正。
-   \[HME0090A\] [●IEのHTML編集用エディタに秀丸を使いたい](./HME0090A.html)を修正。

#### 2018/05/07

-   [第III部〜秀丸マクロのいろはにほへと　マクロを実行してみよう](./3_macro.html)を修正。マクロパスに環境変数が使えることを追記。

#### 2018/05/09

-   \[HMM0008A\] [●マクロ登録方法](./HMM0008A.html)を修正。新しい登録ダイアログについて追記。

#### 2018/05/11

-   \[HME0097A\] [●ファイルを秀丸エディタで編集したのに、反映されていない](./HME0097A.html)を修正。「VirtualStore」の場所を追記。

#### 2018/05/13

-   \[HMM0003A\] [●マクロファイルの置き場所](./HMM0003A.html)を修正。
-   \[HMM0076A\] [●重複行の削除](./HMM0076A.html)を修正。マクロの説明を追加。

#### 2018/05/14

-   \[HMM0051A\] [●version キーワードの使い道は？](./HMM0051A.html)を修正。

#### 2018/05/22

-   \[HME0098A\] [●ファイルの改行コードを変更したい](./HME0098A.html)を修正。

#### 2018/05/24

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を修正。Ver.8.81へ対応。

#### 2018/06/04

-   [第II部〜知っていると便利な秀丸の機能　変換モジュール](./2_convert.html) を修正。
-   [第III部〜秀丸マクロのいろはにほへと　HMJRE.DLLを使う場合の注意点](./3_hmjre.html) を追加。

#### 2018/06/09

-   スタイルシートを変更
-   [第III部〜秀丸マクロのいろはにほへと　HMJRE.DLLを使う場合の注意点](./3_hmjre.html) を修正。

#### 2018/06/17

-   [第III部〜秀丸マクロのいろはにほへと　HMJRE.DLLを使う場合の注意点](./3_hmjre.html) を修正。

#### 2018/06/23

-   8.3版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2018/08/04

-   [第II部〜知っていると便利な秀丸の機能　CSV/TSVモード](./2_csv_tsv.html) を追加。

#### 2018/08/08

-   各ページで、“〜”となっている箇所を、\"〜\" となるように修正。

#### 2018/08/09

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を修正。Ver.8.83へ対応。
-   [第III部〜秀丸マクロのいろはにほへと　秀丸エディタVer.8 マクロ関連の変更履歴](./3_macrov8.html)を修正。

#### 2018/08/12

-   [第II部〜知っていると便利な秀丸の機能　CSV/TSVモード](./2_csv_tsv.html) を修正。区切り文字の表示について追記。

#### 2018/08/13

-   スタイルシート修正
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸スペルチェックアドイン](./6_spellcheck.html) を修正。

#### 2018/08/14

-   [第II部〜知っていると便利な秀丸の機能　単語補完](./2_wordcomplete.html)を修正。「辞書ファイルの種類」による違いを追記。

#### 2018/08/15

-   [第II部〜知っていると便利な秀丸の機能　複数選択](./2_multiselect.html) を修正。
-   「最新版」の日付とバージョン番号を記載しているページを、バージョンアップ時に更新するように修正。

#### 2018/09/24

-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を更新。クイック全置換の内容を追加。

#### 2018/10/02

-   [第II部〜知っていると便利な秀丸の機能　grep/タグジャンプ](./2_grep.html)を修正。除外するファイル、フォルダについて追記。

#### 2018/11/10

-   [第II部〜知っていると便利な秀丸の機能　grep/タグジャンプ](./2_grep.html)を修正。古い記述を削除。

#### 2018/11/12

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を修正。Ver.8.85へ対応。

#### 2018/11/14

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を修正。Ver.8.86へ対応。

#### 2018/11/15

-   [第III部〜秀丸マクロのいろはにほへと　秀丸エディタVer.8 マクロ関連の変更履歴](./3_macrov8.html)を修正。

#### 2018/11/23

-   [第I部〜秀丸エディタＱ＆Ａ集　Ｑ＆Ａ集の表記について](./s_hyouki.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。「ファイルタイプ別の設定」について追記。
-   [第II部〜知っていると便利な秀丸の機能　CSV/TSVモード](./2_csv_tsv.html) を修正。

#### 2018/11/25

-   \[HME0072A\] [●「その他」→「ファイルタイプ別の設定」で設定した内容が反映されない](./HME0072A.html)を修正。
-   \[HME0073A\] [●拡張子別や、grepの結果で秀丸の設定を変更する](./HME0073A.html)を修正。

#### 2018/11/26

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を修正。Ver.8.87へ対応。

#### 2018/12/04

-   [第II部〜知っていると便利な秀丸の機能　grepして置換](./2_grepreplace.html) を追加。

#### 2018/12/16

-   [第I部〜秀丸エディタＱ＆Ａ集　Ｑ＆Ａ集の表記について](./s_hyouki.html)を修正。(markdownの表記方法を変更しただけで内容は変更なし)

#### 2018/12/23

-   8.4版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2019/01/04

-   \[HME0007A\] [●問い合わせ時の必要事項](./HME0007A.html)を修正。
-   \[HMM0026A\] [●setsearchのフラグ](./HMM0026A.html)を修正。フラグ2の内容を修正。


#### 2019/01/12

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。画像変更と説明追加。
-   \[HME0040A\] [●バックアップファイルを作りたくない](./HME0040A.html)を修正。「動作環境」の説明追加。
-   \[HME0051A\] [●漢字コードの使い分け](./HME0051A.html)を修正。`# coding: utf-8`の記述について追加。

#### 2019/01/27

-   [第II部〜知っていると便利な秀丸の機能　強調表示](./2_highlight.html)を新規追加。

#### 2019/01/29

-   \[HME0091A\] [●ファイルタイプ別の設定の方法](./HME0091A.html)を更新。カスタマイズへのリンクを追加。
-   \[HME0092A\] [●コメント行やキーワードを色付けして表示するには](./HME0092A.html)を更新。強調表示へのリンクを追加。

#### 2019/02/03

-   \[HME0096A\] [●\[EOF\]の色を変えるには](./HME0096A.html)に追記。改行文字を共通である事を追記。
-   \[HME0098A\] [●ファイルの改行コードを変更したい](./HME0098A.html)を変更。画像変更。


#### 2019/02/11

-   [第II部〜知っていると便利な秀丸の機能　ファイルマネージャ枠](./2_filemanager.html) を修正。参考用マクロを追加。
-   [第II部〜知っていると便利な秀丸の機能　強調表示](./2_highlight.html)を修正。参考用マクロを追加。
-   [第III部〜秀丸マクロのいろはにほへと　自動起動マクロ](3_autostartmacro.html)の画像変更。誤記修正。

#### 2019/02/24

-   [第II部〜知っていると便利な秀丸の機能　強調表示](./2_highlight.html)を修正。

#### 2019/03/08

-   [第I部〜秀丸エディタＱ＆Ａ集　Ｑ＆Ａ集の表記について](./s_hyouki.html)を修正。
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。

#### 2019/03/10

-   [第III部〜秀丸マクロのいろはにほへと　秀丸マクロで文字列を編集する](./3_string.html)を修正。

#### 2019/03/12

-   \[HME0003A\] [●「送金登録作業」の手順](./HME0003A.html)を修正。
-   \[HME0049A\] [●「ワード」や「一太郎」等のファイルにgrep](./HME0049A.html)を修正。
-   \[HME0055A\] [●複数パソコンに同じ「キー割り当て」をしたい](./HME0055A.html)を修正。

#### 2019/03/16

-   markdown(pandoc)の記述方法を変更。その為、ほぼ全ページ更新したが、内容は変わっていない。

#### 2019/03/17

-   [第II部〜知っていると便利な秀丸の機能　あいまい検索](2_fuzzy.html)を修正。

#### 2019/03/18

-   [第II部〜知っていると便利な秀丸の機能　カラーマーカー](./2_colormarker.html) を修正。

#### 2019/03/19

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。

#### 2019/04/07

-   [第II部〜知っていると便利な秀丸の機能　カラーマーカー](./2_colormarker.html) を修正。画像を変更。
-   [第II部〜知っていると便利な秀丸の機能　強調表示](./2_highlight.html)を修正。「hilightファイル直接指定モード」を追加。

#### 2019/04/25

-   [第II部〜知っていると便利な秀丸の機能　強調表示](./2_highlight.html)を修正。「hilightファイル直接指定モード」を修正。

#### 2019/04/27

-   [第III部〜秀丸マクロのいろはにほへと　外部プログラムの実行について](./3_run.html)を新規追加

#### 2019/04/30

-   [第III部〜秀丸マクロのいろはにほへと　秀丸マクロで文字列を編集する](./3_string.html)を修正。
-   [第III部〜秀丸マクロのいろはにほへと　外部プログラムの実行について](./3_run.html)を修正。
-   \[HMM0082A\] [●カーソルのある行の内容を文字列型変数に取り込む方法](./HMM0082A.html)を新規追加。
-   markdown(pandoc)の記述方法を変更。内容は変わっていない。

#### 2019/05/01

-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　grep/タグジャンプ](./2_grep.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　grepして置換](./2_grepreplace.html)を修正。

#### 2019/05/04

-   内容に変更なし。html5構文チェックの内容を反映。

#### 2019/06/01

-   [第II部〜知っていると便利な秀丸の機能　自動保存](./2_autosave.html)を新規追加。

#### 2019/06/07

-   [第II部〜知っていると便利な秀丸の機能　強調表示](./2_highlight.html)を修正。

#### 2019/06/08

-   [第III部〜秀丸マクロのいろはにほへと　外部プログラムの実行について](./3_run.html)を修正。
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。
-   \[HME0007A\] [●問い合わせ時の必要事項](./HME0007A.html)を修正。

#### 2019/06/10

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。

#### 2019/06/12

-   [第I部〜秀丸エディタＱ＆Ａ集　よくある質問](./yokuaru.html)を修正。
-   [第I部〜秀丸エディタＱ＆Ａ集　機能別Ｑ＆Ａ](./qa_kinou.html)を修正。
-   [第I部〜秀丸エディタＱ＆Ａ集　質問番号順Ｑ＆Ａ](./qa_order.html)を修正。

#### 2019/06/16

-   [第II部〜知っていると便利な秀丸の機能　強調表示](./2_highlight.html)を修正。

#### 2019/06/18

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。リンクを追加。

#### 2019/06/19

-   [第II部〜知っていると便利な秀丸の機能　カラーマーカー](./2_colormarker.html) を修正。

#### 2019/06/22

-   8.5版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2019/06/30

-   \[HMM0073A\] [●文字列をバイト単位ではなく文字単位で扱う](./HMM0073A.html)を修正。


#### 2019/07/07

-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html)を修正。

#### 2019/07/28

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を修正。表記修正。

#### 2019/09/03

-   \[HME0025A\] [●起動するとともに常駐させたい](./HME0025A.html)を変更。
-   \[HME0027A\] [●起動時に秀丸が現れて邪魔だ](./HME0027A.html)を変更。

#### 2019/09/04

-   \[HME0099A\] [●秀丸エディタのバージョンアップ方法](./HME0099A.html)を新規追加。

#### 2019/09/13

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を修正。バージョンダイアログの説明追加。

#### 2019/09/14

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。ストアアプリ版では使用できないことを追記。

#### 2019/09/20

-   [第II部〜知っていると便利な秀丸の機能　grep/タグジャンプ](./2_grep.html)を修正。

#### 2019/09/23

-   \[HME0025A\] [●起動するとともに常駐させたい](./HME0025A.html)を修正。
-   \[HME0027A\] [●起動時に秀丸が現れて邪魔だ](./HME0027A.html)を修正。
-   \[HME0061A\] [●空白行を削除したい](./HME0061A.html)を修正。
-   \[HME0062A\] [●空白行を改行だけの行にしたい](./HME0062A.html)を修正。
-   \[HME0063A\] [●行頭の空白を削除したい](./HME0063A.html)を修正。
-   \[HME0064A\] [●行末の空白を削除したい](./HME0064A.html)を修正。
-   \[HME0065A\] [●改行だけの行を削除したい](./HME0065A.html)を修正。

#### 2019/09/29

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を修正。Ver.8.89へ対応。
-   [第II部〜知っていると便利な秀丸の機能　CSV/TSVモード](./2_csv_tsv.html) を修正。セル内改行について追記。

#### 2019/10/15

-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html)を修正。リンクや内容修正。

#### 2019/10/29

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。Ver.5.00対応。

#### 2019/11/02

-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html)を修正。
-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。

#### 2019/11/11

-   以下のページの外部へのリンク先を修正。
    -   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html)
    -   [第III部〜秀丸マクロのいろはにほへと　マクロのデバッグについて](./3_debug.html)
    -   [第III部〜秀丸マクロのいろはにほへと　外部プログラムの実行について](./3_run.html)
    -   [第V部〜マクロから呼び出すＤＬＬの作り方](./make_dll.html)

#### 2019/11/14

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。Ver.5.01対応。
-   [秀丸エディタの最新版](./s_saisin.html)を修正。題名変更「秀丸エディタの各ＯＳ毎の最新版」->「秀丸エディタの最新版」

#### 2019/11/17

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。

#### 2019/11/20

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸スペルチェックアドイン](./6_spellcheck.html) を修正。

#### 2019/11/21

-   [第II部〜知っていると便利な秀丸の機能　CSV/TSVモード](./2_csv_tsv.html) を修正。
-   [第III部〜秀丸マクロのいろはにほへと　マクロのデバッグについて](./3_debug.html)のリンク先を修正。

#### 2019/11/29

-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を修正。
-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。
-   \[HME0083A\] [●検索/置換の「選択した範囲内のみ」の動作](./HME0083A.html) を修正。

#### 2019/12/05

-   \[HME0004A\] [●パスワードを忘れた/紛失した](./HME0004A.html)を修正。

#### 2019/12/09

-   [第I部〜秀丸エディタＱ＆Ａ集　Ｑ＆Ａ集の表記について](./s_hyouki.html)を修正。

#### 2019/12/11

-   \[HMM0034A\] [●rollup等の動き](./HMM0034A.html) を修正。
-   \[HMM0070A\] [●入力チェック、変数チェックを簡単に行う方法](./HMM0070A.html) を修正。

#### 2019/12/12

-   \[HMM0004A\] [●マクロファイルの管理](./HMM0004A.html) を修正。
-   \[HMM0012A\] [●登録したマクロがメニューにない](./HMM0012A.html) を修正。
-   \[HMM0033A\] [●insertreturnの上書き/挿入MODEでの動き](./HMM0033A.html) を修正。
-   \[HMM0041A\] [●文字列型変数の扱う文字列の限界](./HMM0041A.html) を修正。
-   \[HMM0047A\] [●特定のファイルを開く](./HMM0047A.html) を修正。

#### 2019/12/15

-   \[HME0087A\] [●異なるフォルダの秀丸が実行されているので起動できません](./HME0087A.html) を修正。

#### 2019/12/17

-   \[HMM0012A\] [●登録したマクロがメニューにない](./HMM0012A.html) を修正。画像追加。

#### 2019/12/18

-   [第III部〜秀丸マクロのいろはにほへと　マクロを実行してみよう](3_macro.html)を修正。画像変更。
-   \[HMM0012A\] [●登録したマクロがメニューにない](./HMM0012A.html) を修正。画像変更。

#### 2019/12/21

-   [第III部〜秀丸マクロのいろはにほへと　秀丸マクロで文字列を編集する](3_string.html)を修正。
-   \[HME0099A\] [●秀丸エディタのバージョンアップ方法](./HME0099A.html)を修正。
-   8.6版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2019/12/25

-   \[HMM0083A\] [●外部DLLのロードに失敗する](./HMM0083A.html)を新規追加。
-   \[HMM0081A\] [●「DLLがロードされてないのにdllfunc関数が使われました」と表示される](./HMM0081A.html)を修正。

#### 2019/12/28

-   \[HMM0083A\] [●外部DLLのロードに失敗する](./HMM0083A.html)を修正。
-   \[HMM0081A\] [●「DLLがロードされてないのにdllfunc関数が使われました」と表示される](./HMM0081A.html)を修正。
-   \[HME0001A\] [●パスワードが来ない](./HME0001A.html)を修正。リンク先を HMM0083A に変更。

#### 2020/01/03

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。Ver.8.90対応。

#### 2020/01/05

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。Ver.8.90を追加。


#### 2020/01/08

-   \[HME0040A\] [●バックアップファイルを作りたくない](./HME0040A.html)を変更。Ver8.89以降の変更に対応。

#### 2020/01/12

-   \[HME0052A\] [●テキストファイルは常に秀丸で開きたい](./HME0052A.html)を変更。持ち出しキット使用時にはボタンが無効化されることを追記。

#### 2020/01/14

-   \[HMM0083A\] [●外部DLLのロードに失敗する](./HMM0083A.html)を修正。

#### 2020/02/02

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。Ver.5.02対応。

#### 2020/02/05

-   [第II部〜知っていると便利な秀丸の機能　自動保存](./2_autosave.html)を修正。Ver.8.90対応のオプション追加に対応。
-   \[HMM0081A\] [●「DLLがロードされてないのにdllfunc関数が使われました」と表示される](./HMM0081A.html)を修正。
-   全htmlを一度削除し、ファイルを再作成(markdown(pandoc) --> html変換)

#### 2020/02/11

-   \[HMM0076A\] [●重複行の削除](./HMM0076A.html)を修正。マクロをチョット修正。
-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。Ver.8.90βの内容を追加。

#### 2020/02/14

-   各部の画像を、Ver8.90に変更
-   \[HME0092A\] [●コメント行やキーワードを色付けして表示するには](./HME0092A.html)を修正。

#### 2020/02/16

-   各部の画像を、Ver8.90に変更および、画像を共通化。

#### 2020/02/22

-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。設定次第で、ボタンのキャプションが変わることを追記。

#### 2020/02/23

-   [第II部〜知っていると便利な秀丸の機能　CSV/TSVモード](./2_csv_tsv.html) を修正。Ver.8.91対応。

#### 2020/02/24

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。Ver.8.91対応。

#### 2020/03/01

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。Ver.8.91対応。

#### 2020/03/03

-   [第II部〜知っていると便利な秀丸の機能　複数選択](./2_multiselect.html)を修正。

#### 2020/03/05

-   \[HME0035A\] [●縦書きや段組みなど、きめ細かな設定で印刷したい](./HME0035A.html)を修正。

#### 2020/03/06

-   \[HME0054A\] [●他のエディタと同じキー操作を再現したい](./HME0054A.html)を修正。
-   \[HME0055A\] [●複数パソコンに同じ「キー割り当て」をしたい](./HME0055A.html)を修正。

#### 2020/03/10

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。

#### 2020/03/20

-   [第III部〜秀丸マクロのいろはにほへと　マクロを実行してみよう](./3_macro.html)を修正。キー割り当て部分変更。

#### 2020/05/07

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸スペルチェックアドイン](./6_spellcheck.html) を修正。Ver.1.03へ。

#### 2020/05/14

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。ストアアプリ版の説明を追加。

#### 2020/05/26

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。Ver.5.03対応。

#### 2020/05/31

-   [第II部〜知っていると便利な秀丸の機能　強調表示](./2_highlight.html)を修正。「カラーマーカーで色付けするマクロの例」を修正。

#### 2020/06/01

-   \[HMM0081A\] [●「DLLがロードされてないのにdllfunc関数が使われました」と表示される](./HMM0081A.html)を修正。

#### 2020/06/04

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。「一覧表作成」部分を修正。
-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。Ver.8.92βの内容を追加。
-   目次、各ページのタイトル、chmファイルのキーワードが一致していない箇所があったので、修正。

#### 2020/06/09

-   [第II部〜知っていると便利な秀丸の機能　秀丸のカスタマイズ](./2_custom.html)を修正。画像が抜けていたので追加。

#### 2020/06/11

-   \[HME0052A\] [●テキストファイルは常に秀丸で開きたい](./HME0052A.html)を変更。説明を変更。画像を追加。

#### 2020/06/13

-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。画像を変更。
-   [第II部〜知っていると便利な秀丸の機能　grep/タグジャンプ](./2_grep.html)を修正。補助メニューの説明を追加。

#### 2020/06/20

-   \[HMM0076A\] [●重複行の削除](./HMM0076A.html)を修正。誤記修正。
-   8.7版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2020/06/23

-   [秀丸エディタの最新版](./s_saisin.html)を修正。英語版は「Ver.8.92が最終になる予定」と追記。

#### 2020/06/24

-   秀丸エディタがVer.8.93になったので、各部を修正。

#### 2020/07/05

-   [秀丸エディタの最新版](./s_saisin.html)を修正。言語の切替について追記。
-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。Ver.8.94βの内容を追加。

#### 2020/07/07

-   [編集場所について](./hidpatio.html)を修正。

#### 2020/07/11

-   [秀丸エディタの最新版](./s_saisin.html)を修正。英語版からの設定移行を追記。

#### 2020/07/12

-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。「選択した範囲」の説明を修正。
-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を修正。「選択した範囲」の説明を修正。

#### 2020/07/19

-   \[HME0083A\] [●検索/置換の「選択した範囲」の動作](./HME0083A.html) を修正。

#### 2020/07/25

-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。画像を変更。
-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を修正。画像を変更。

#### 2020/08/01

-   [秀丸エディタの最新版](./s_saisin.html)を修正。表示言語の切替を独立した内容へ。
-   [第II部〜知っていると便利な秀丸の機能　表示言語の切替](./2_language.html)を新規追加
-   \[HME0098A\] [●ファイルの改行コードを変更したい](./HME0098A.html)を修正。「上書き保存」した場合は「エンコードの種類の指定」の設定が反映されることを追記

#### 2020/08/02

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。Ver.8.94β6までの内容を追加。

#### 2020/08/08

-   [第II部〜知っていると便利な秀丸の機能　表示言語の切替](./2_language.html)修正。公式へのリンクを追加。

#### 2020/08/09

-   \[HME0007A\] [●問い合わせ時の必要事項](./HME0007A.html)を修正。

#### 2020/08/14

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。誤記修正。

#### 2020/09/06

-   [第III部〜秀丸マクロのいろはにほへと　外部プログラムの実行について](./3_run.html)を修正。

#### 2020/09/07

-   [第II部〜知っていると便利な秀丸の機能　ファイルマネージャ枠](./2_filemanager.html) を修正。誤記修正。

#### 2020/09/14

-   [第II部〜知っていると便利な秀丸の機能　アウトプット枠](./2_output.html)を修正。Windows 98/MEでは使用できないことを追記。

#### 2020/09/22

-   [第II部〜知っていると便利な秀丸の機能　プログラム実行](./2_program.html)を追加。
-   [第III部〜秀丸マクロのいろはにほへと　外部プログラムの実行について](./3_run.html)を修正。
-   [第IV部〜テキスト編集を極める！！　プログラム実行を利用したテキストの加工](./4_run.html)を追加。

#### 2020/09/23

-   各ページの書式をなるべく統一するように変更。

#### 2020/09/26

-   [第III部〜秀丸マクロのいろはにほへと　外部プログラムの実行について](./3_run.html)を修正。
-   誤記修正。

#### 2020/09/27

-   [第II部〜知っていると便利な秀丸の機能　アウトプット枠](./2_output.html)を修正。「プログラム実行」へのリンクを追加。

#### 2020/10/10

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。
-   Ver.8.94が正式版になったので、β版の記述を修正。
-   [第II部〜知っていると便利な秀丸の機能　CSV/TSVモード](./2_csv_tsv.html) を修正。「指定した列のみ検索対象にしたい場合」を修正。

#### 2020/10/17

-   [第II部〜知っていると便利な秀丸の機能　他の秀丸エディタと内容比較](./2_compfile.html)を新規追加。

#### 2020/10/25

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。Ver.8.95 の内容を追加。

#### 2020/10/27

-   [第II部〜知っていると便利な秀丸の機能　デスクトップ保存と復元](./2_desktop.html)を新規追加。

#### 2020/10/31

-   [秀丸エディタの最新版](./s_saisin.html)を修正。サポート期間へのリンクを変更。
-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。Ver.8.95 の内容を修正。
-   全体を見直し、表記、誤記修正。

#### 2020/11/03

-   [第IV部〜テキスト編集を極める！！　起動オプションを使ってみよう](./4_cmdlin.html)を修正。「送る」を開く方法を追記。
-   [第III部〜秀丸マクロのいろはにほへと　サブルーチンについて](./3_sub.html)を修正。章の表記を他と合わせる。

#### 2020/11/08

-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。Ver.8.94以降、「選択した範囲」がBOX選択でも有効になる事を追記。
-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を修正。Ver.8.94以降、「選択した範囲」がBOX選択でも有効になる事を追記。

#### 2020/11/09

-   [第II部〜知っていると便利な秀丸の機能　デスクトップ保存と復元](./2_desktop.html)を修正。

#### 2020/11/23

-   全体を見直し、表記、誤記修正。

#### 2020/12/05

-   全体を見直し、表記、誤記修正。

#### 2020/12/09

-   [秀丸エディタの最新版](./s_saisin.html)を修正。Windows10 のサポートバージョンを変更。

#### 2020/12/11

-   chm版で、[既に対応済みの過去のトラブル](./qa_trbl.html)と[改版履歴](./updated.html)が変だったのを修正。

#### 2020/12/13

-   全体を見直し、表記、誤記修正。
-   外部リンクに、「rel="noopener"」を追加。
-   pandoc のバージョンアップや、外部リンクの変更に伴い、全ファイルを再出力。

#### 2020/12/14

-   \[HME0017A\] [●知らない秀丸がメモリー上に残っている](./HME0017A.html) を修正。画像変更。
-   \[HME0047A\] [●外部ヘルプファイルの起動方法](./HME0047A.html) を修正。リンク先変更。

#### 2020/12/23

-   chm の設定変更。「進む」ボタン追加。「検索」で拡張全文検索を設定。
-   8.8版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2020/12/29

-   バージョンを修正。(8.8 --> 8.9)
-   \[chm\]ファイル名変更(Table of Contents.hhc --> hmfaq.hhc)に伴い、設定を修正。

#### 2020/12/30

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。誤記修正。

#### 2021/01/01

-   [第III部〜秀丸マクロのいろはにほへと　マクロ内での「\\」や特殊文字の使い方](./3_yenmk.html)を修正。「補足」を追加。
-   [第IV部〜テキスト編集を極める！！　起動オプションを使ってみよう](./4_cmdlin.html)を変更。誤記修正。

#### 2021/01/03

-   CSSの調整。

#### 2021/01/23

-   \[chm\]キーワードファイル(hmfaq.hhk)を修正。ダブルクオートの閉じ忘れの修正。
-   [第II部〜知っていると便利な秀丸の機能　縦書き](./2_vertical.html)を新規追加。

#### 2021/01/25

-   CSSの調整。

#### 2021/01/30

-   [第II部〜知っていると便利な秀丸の機能　文字数の計算](2_wordcount.html) を修正。Ver.8.96で追加された「カーソル移動単位」を追記。
-   [HME0016B](./HME0016B.html)で使っている画像を変更。

#### 2021/02/03

-   秀丸エディタがVer.8.96になったので、各部を修正。

#### 2021/02/07

-   CSSの調整。
-   [第IV部〜テキスト編集を極める！！　起動オプションを使ってみよう](./4_cmdlin.html)を変更。「【５】補足」のインデントがおかしかったのを修正。

#### 2021/02/20

-   \[HMM0084A\][●フォルダにある複数のファイルにマクロを実行したい](./HMM0084A.html)を新規追加。
-   [第IV部〜テキスト編集を極める！！　起動オプションを使ってみよう](./4_cmdlin.html)を変更。

#### 2021/02/28

-   \[HMM0084A\][●フォルダにある複数のファイルにマクロを実行したい](./HMM0084A.html)を修正。
-   \[chm\]キーワードファイル(hmfaq.hhk)を修正。

#### 2021/03/01

-   秀丸エディタがVer.8.97になったので、各部を修正。

#### 2021/03/02

-   [第II部〜知っていると便利な秀丸の機能　文字数の計算](2_wordcount.html) を修正。Ver.8.97での変更に対応。

#### 2021/03/06

-   [第II部〜知っていると便利な秀丸の機能　文字数の計算](2_wordcount.html) を修正。

#### 2021/03/11

-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を修正。クイック全置換を修正。

#### 2021/03/29

-   CSSの調整。

#### 2021/03/31

-   \[HMM0084A\][●フォルダにある複数のファイルにマクロを実行したい](./HMM0084A.html)を修正。

#### 2021/04/29

-   全体を見直し、表記、誤記修正。

#### 2021/05/04

-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html)を修正。

#### 2021/05/06

-   [第II部〜知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。画像を変更。行単位の場合、コメントの記述が出来ることを追記。

#### 2021/05/19

-   \[HME0100A\][●範囲選択中にスクロースさせると範囲選択が広がってしまう](HME0100A.html)を新規追加。

#### 2021/05/22

-   [第III部〜秀丸マクロのいろはにほへと　秀丸マクロで文字列を編集する](./3_string.html)を修正。


#### 2021/06/03

-   \[chm\]pandoc のオプション変更に伴い、全html再出力

#### 2021/06/09

-   「FULLWIDTH TILDE」と「WAVE DASH」が混在していたので、「WAVE DASH」に統一

#### 2021/06/10

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を変更。Ver.8.98βの内容を追加。

#### 2021/06/13

-   [第III部〜秀丸マクロのいろはにほへと　COMオブジェクト操作関連](./3_com_object.html)を修正。戻り値が配列の場合について追記。

#### 2021/06/27

-   8.9版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2021/06/28

-   秀丸エディタがVer.8.98になったので、各部を修正。

#### 2021/07/15

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。「編集中のフォント」について追記。

#### 2021/07/28

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。バージョン情報を修正。

#### 2021/08/07

-   \[HME0047A\][●外部ヘルプファイルの起動方法](./HME0047A.html)を修正。リンク先変更。

#### 2021/08/09

-   秀丸エディタが Ver.8.99.1 になったので、各部を修正。
-   [第II部〜知っていると便利な秀丸の機能　置換](./2_replace.html)を修正。
-   \[HME0083A\][●検索/置換の「選択した範囲」の動作](./HME0083A.html)を修正。

#### 2021/08/15

-   [第II部〜知っていると便利な秀丸の機能　アウトライン関連  見出し・折りたたみ・部分編集](./2_outline_functions.html)を新規追加(「アウトライン解析の枠」から分離)。

#### 2021/10/06

-   [第VI部〜秀丸エディタ拡張モジュール　秀丸パブリッシャー](./6_publisher.html)を修正。バージョン情報を修正。
-   [第III部〜秀丸マクロのいろはにほへと　setcompatiblemode文 について](./3_setcompatiblemode.html)を新規追加。

#### 2021/10/09

-   秀丸エディタが Ver.8.99.2 になったので、各部を修正。
-   [第II部〜知っていると便利な秀丸の機能　検索](./2_find.html)を修正。サブメニューの画像変更。マクロ使用時の注記を追記。

#### 2021/11/03

-   [第II部〜知っていると便利な秀丸の機能　他の秀丸エディタと内容比較](./2_compfile.html)を修正。マクロ関連を追記。

-----------------------------------------------------------------------------------------------------------------
[<span id="last_history">履歴の先頭へ</span>](#history)
