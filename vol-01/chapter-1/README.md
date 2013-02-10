# chapter1 イントロダクション

## 1-1 jsとは？

### 概要

Netscape Cが作ったbrowser向けscript

1. 95年：装飾過剰/browser毎の動作差異等であまり良いイメージ無し
1. 97年：ECMAScriptで標準化。徐々にbrowser毎の動作違いを解消。
1. 05年：ajaxの登場。google maps/documentで流行
1. 06年,07年：jquery等のライブラリ普及。敷居が下がる。
1. 09年,10年：node.js登場。server side言語として注目
1. 09年,10年：coffee scriptでラッピング。rubyやpythonのように気軽に書ける。
1. 最近その１：html5とset。desktopアプリ並みのwebアプリ？
1. 最近その２：backbone.js等jsもMVCで整理していく方向性。



### 特徴

1. script言語
1. インタプリタ型
1. ブラウザ上で動作

## 1-2 環境

### browser

FFかchrome
- FF：firebug plugin
- chrome：デベロッパーツール
 - chrome canary（デベロッパーツールの機能が増えている）
 - https://www.google.com/intl/ja/chrome/browser/canary.html

### 開発環境

- SublimeText2：（有料）フロントエンジニア全般に去年あたりから流行っているエディタ。
 - メリット：ファイル移動早い。カスタマイズ性高い。プラグイン開発が加熱していて、それら組み合わせると一通り何でもできる。
 - デメリット：IDEと比べるとやや機能が少なめか？(pluginで自由に追加できるが入れないとただのエディタ。)

- WebStorm：（有料）JSに特化したIDE。これもそこそこ流行っている。（ちゃんと使った事ないので、詳しい人いたら教えて。）
 - メリット：補完がよく出来ているとかなんとか。JSに特化しているらしい。
 - デメリット：frontだけcodingするengineerはいいけど、ruby等backendのengineerは、IDE２つ切り替えて使わないと行けないんじゃない？

- Aptana Studio 3：Eclipseベース
 - メリット：一通りの機能はあり、長年親しまれたeclipseベースなので、取っ付き易いかも。無料。
 - デメリット：高機能すぎて分かり辛い？重くて玉に落ちる？昔からあるけど、なぜかイマイチ流行らない。

- Vim/Emacs：昔からある伝統的なエディタ。
 - メリット：pluginでカスタマイズが無限に出来る。テキスト編集が得意。特に、vi(vim)はunixに必ずあるので、何かと助けられる。
 - デメリット：キーバインディングや編集モードの考え方等、覚えなくてはいけない事が幾つかあり、敷居高いかも。


初めてなら、sublimeが一番いいかも。なんか、主流になりつつあるような。


### おまけ

- jsHint
- node.js
 - インストールしておくと何かと便利。
 - $ node //1行単位でjs実行して確認できる。

