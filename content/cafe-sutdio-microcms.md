+++
title = "親がカフェを始めたので STUDIO と microCMS でサイトを構築した"
date = "2022-12-31"
+++

親がカフェを始めるとのことでその Web サイト制作を依頼された。

自分は Web エンジニアをやっているが得意なのはバックエンド領域であり、フロントエンドはそこまで得意なわけではなく、デザインに関しては完全に素人なので困ってしまった。

フロントエンドの練習がてら Astro とかを使ってみるという選択肢もあったが、自分だけの問題ならともかく親にも関わる話だったので、あまりチャレンジングなことはせず無難にサクサク進めたかった。
そこで [STUDIO](https://studio.design/ja) を使うことにした。

デザインに関しても STUDIO の [テンプレート](https://studio.design/ja/template) を使うことにしてなんとかなった。
必要なコンテンツは料理の写真、地図、営業時間などのオーソドックスなものだけだったので、テンプレートをベースにして困るようなことは特に無かった。

ほぼ全てのコンテンツが滅多に変更され無さそうなので、主に STUDIO のデザインエディタを使って手動でテキストや画像を入力した。
営業時間に関してはたまに変わるとのことで、毎回親から私に変更を依頼するのではなく、親が自分で変更できるようにしたいとのことだった。

普通に考えれば STUDIO の CMS 機能を使うのが手っ取り早いが、STUDIO の管理画面は PC 版の Chrome でしか使えないという制約がある。
STUDIO のような複雑な UI を制御するアプリケーションで、対象のブラウザを絞ってスマホをサポート外とするのは良い判断だと開発者としては思う。
しかし、私の親は日常的に PC を利用するようなタイプではないため、スマホで管理できるようにしてあげたかった。

microCMS の管理画面はスマホをサポートしているため、ここで [microCMS](https://microcms.io/) を使うことにした。
[STUDIO には API 連携機能](https://blog.studio.design/ja/posts/api-integration)があり microCMS との連携がサポートされているため、簡単にこれが実現できた。

ただし、STUDIO の microCMS 連携機能ではリスト形式 API にしか対応しておらず、 オブジェクト形式 API に対応していなかったためそこで少しだけ困惑した。
しかし、リスト形式 API にコンテンツを1つだけ用意するということは可能であり、こうして運用でカバーできるので大した問題にはならなかった。

ドメイン取得には Google Domains を使った。
今までは個人的にドメインを取得して Web サイトを作るときに Route 53 を使っていたが、見聞を広めるためにあえて慣れていない Google Domains を使用した。
フロントエンドの選定とは逆に自分にとっては多少のチャレンジではあるが、この判断で作業時間が2倍になるとかそこまで酷い悪影響は無さそうなので許容した。

Google Domains では HTTP のリダイレクト設定ができるのが便利だった。
具体的にはネイキッドドメインを www 付きのドメインにリダイレクトする設定をするために、この機能が役に立った。

自分が知っている限り Route 53 だけではこれは実現できなくて、 AWS でこれをやろうとすると空の S3 バケットを作って Static Web Hosting のリダイレクト設定をするとか、 CloudFront Functions や Lambda@Edge を使うとか、そういう工夫が必要なはず。
こういう工夫が不必要でシンプルにリダイレクト設定ができて助かった。