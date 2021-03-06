# nginx実践入門 サンプルコード

[![Build Status](https://travis-ci.org/wdpress/nginx_Practical_Guide.svg?branch=master)](https://travis-ci.org/wdpress/nginx_Practical_Guide)

Web+DB PRESS plusシリーズ nginx実践入門のサンプルコードです。
サンプルコードは実際に利用できる形に近づけるため、紙面の都合上省略している部分も含まれています。

サンプルコードは筆者らが動作確認を行っていますが、不具合があった場合は本書Webページよりお問い合わせをお願い致します。

- [書籍内容に関するお問い合わせ](https://gihyo.jp/site/inquiry/book?ISBN=978-4-7741-7866-0)

## 目次

実行方法は各章のREADME.mdをご覧下さい。

- 第1章 nginxの概要とアーキテクチャ (第1章のサンプルコードはありません)
- [第2章 インストールと起動](//github.com/wdpress/nginx_Practical_Guide/tree/master/ch2)
- [第3章 基本設定](//github.com/wdpress/nginx_Practical_Guide/tree/master/ch3)
- [第4章 静的なWebサイトの構築](//github.com/wdpress/nginx_Practical_Guide/tree/master/ch4)
- [第5章 安全かつ高速なHTTPSサーバの構築](//github.com/wdpress/nginx_Practical_Guide/tree/master/ch5)
- [第6章 Webアプリケーションサーバの構築](//github.com/wdpress/nginx_Practical_Guide/tree/master/ch6)
- [第7章 大規模コンテンツ配信サーバの構築](//github.com/wdpress/nginx_Practical_Guide/tree/master/ch7)
- [第8章 Webサーバの運用とメトリクスモニタリング](//github.com/wdpress/nginx_Practical_Guide/tree/master/ch8)
- [第9章 Luaによるnginxの拡張──Embed Lua into nginx](//github.com/wdpress/nginx_Practical_Guide/tree/master/ch9)
- [第10章 OpenResty──nginxベースのWebアプリケーションフレームワーク](//github.com/wdpress/nginx_Practical_Guide/tree/master/ch10)

## 本書について

<img src="https://raw.githubusercontent.com/wdpress/nginx_Practical_Guide/master/ch4/images/images/nginx.jpg" width="200">

[nginx実践入門](http://gihyo.jp/book/2016/978-4-7741-7866-0)


- [Amazon.co.jpで購入](http://www.amazon.co.jp/o/ASIN/4774178667)
- [オムニ7 - セブンネットショッピングで購入](http://7net.omni7.jp/detail/1106617458)
- [hontoで購入](http://honto.jp/netstore/pd-book_27615435.html)
- 電子書籍(PDF): [Gihyo Digital Publishingで購入](https://gihyo.jp/dp/ebook/2016/978-4-7741-7936-0)

```
2016年1月16日発売
久保達彦，道井俊介　著
A5判／304ページ
定価（本体2,770円＋税）
ISBN 978-4-7741-7866-0
```

## 動作確認環境

本書で利用しているソフトウェアは、執筆時点（2015 年10 月）の最新である次のバージョンで動作確認を行っています。

- Debian GNU/Linux 8（jessie）
- nginx 1.9.5※
- OpenResty 1.9.3.1
- Fluentd 0.12.16
- PCRE 8.37
- zlib 1.2.8
- OpenSSL 1.0.2d
- GD 2.1.1

※第10章「OpenResty──nginxベースのWebアプリケーョンフレームワーク」ではOpenResty にバンドルされているnginxを利用しているため、利用しているOpenRestyのバージョンによるものとします。

環境や時期により、手順・画面・動作結果などが異なる可能性があります。
サンプルコードの内容に基づく運用結果について、著者、ソフトウェアの開発元および提供元、株式会社技術評論社は一切の責任を負いかねますので、あらかじめご了承ください。
サンプルコードに記載されている会社名・製品名は、一般に各社の登録商標または商標です。本書、サンプルコード中では、TM、©、®マークなどは表示しておりません。

## ライセンス

See [LICENSE file](//github.com/wdpress/nginx_Practical_Guide/blob/master/LICENSE).

Copyright 2015-2016 Shunsuke Michii, Tatsuhiko Kubo. All Rights Reserved.
