# ミアビータ会員専用ページの作成

## DEMO

  - デプロイしている場合はURLを記入（任意）

## 紹介と使い方

  - 自社サービスの会員専用のページを作成

  - if分岐を使ってキャリアのお悩み診断を作成
  
  キャリアのお悩み診断をクリックすると、チェックリストが表示され、診断するのボタンを押すとチェック項目に該当する解決策のヒントが提示される

  *将来的に、複数チェックがされた場合、解決ヒントをスライド形式で表示させたい
  
  - 診断ボタンを押すと、2秒後にサービスのご案内が表示される

  - 有料会員向けの機能として今回２つを作成
  
  ①人生に影響を与えた本と名言
  
  クリックするとランダムに本と名言が表示される
  
  ②１日１問人生を変える質問

＊将来的には、有料会員向けの機能は支払いをしている人だけがみれるようにしたい。

あとは、ここをできるところまで
- 個別サポートの専門家を条件に合わせてMax３名までレコメンド表記

  


## 工夫した点

  - デザインはシンプルに、サイトカラーやフォントに合わせてデザインを作成
  
  - その代わり、ヘッダー部分に動きをもたせてキャリア診断へと誘導

  - キャリア診断のボタンがボブボブするのはお気に入り♡

  - お申し込みにつながるよう、上から下へ動線を意識して表示を設計



## 苦戦した点

  - 今回一番苦労したのは、キャリア診断の表示がうまくできずに、１日以上費やしてしまった。。。最終的には、スライダー表記をするのをやめて、配列を使って表示する方法に着地。ただし、診断ボタンを複数回クリックすると何個も診断結果がでてしまったり、それを解消しようとすると診断ボタンが消えてしまったり。一つ変更を加えると、他の部分がおかしくなるの連続で苦労した。

## 参考にした web サイトなど

  - デザイン参考

  https://choooodoii.com/

  - JSでできること
  
  https://school.dhw.co.jp/course/web/contents/r_JavaScript-cando.html


  - 【JS】addEventListener（イベント処理を実行するメソッド）の使い方
  
  https://qiita.com/mzmz__02/items/873118fbd8723c44956d

  - jQueryの$(document).ready()とは？意味や使い方をご紹介（JavaScriptの実行準備が可能になるまで処理を保留）
  
  https://rainbow-engine.com/jquery-document-ready/

  - JavaScriptのsetTimeoutとsetIntervalを理解しマスターする
  
  https://techplay.jp/column/548

  - アロー関数について
  
  https://www.javadrive.jp/javascript/function/index9.html

- CSSのposition:absolute;とは？要素を思いのままに配置する方法

https://www.sejuku.net/blog/53016

- 【CSS】transformで思い通りのアニメーションを再現

https://web-camp.io/magazine/archives/87247

- CSSアニメーションまとめ

https://b-risk.jp/blog/2021/01/anim-reference/

- jQueryの基本 - $(document).ready

https://qiita.com/8845musign/items/88a8c693c84ba63cea1d

- jQery】チェックボックスcheckboxの変更を監視・検知する：change()

https://office54.net/iot/jquery/checkbox-change-detect

- チェックボックスを使った診断テストのコートについて（by チャッピー）

https://chat.openai.com/c/45279b07-4a05-4db1-8a4a-285f8a3ef9f7

- .prop("checked") は、チェックボックスがチェックされているかどうかを判断するメソッドです。チェックされている場合、true を返し、そうでない場合は false を返します。

- .append() は、指定された要素内の最後にコンテンツを追加するjQueryメソッドです。ここでは、yarigai 変数に格納されているテキストを、<p> タグで囲んで result__text 要素に追加しています。

- HTMLで特殊文字のエスケープ処理を行う方法【初心者向け】

「&lt;」と「&gt;」はそれぞれHTML文書で「<」「>」文字を表すための記法

https://magazine.techacademy.jp/magazine/12553

- spanタグとは

https://seolaboratory.jp/64959/

https://gmotech.jp/semlabo/seo/blog/span/#:~:text=span%E3%82%BF%E3%82%B0%E3%81%A8%E3%81%AFHTML,%E9%9A%9B%E3%81%AB%E6%B4%BB%E7%94%A8%E3%81%97%E3%81%BE%E3%81%99%E3%80%82

- サポーター検索（食べログ参照）

https://tabelog.com/