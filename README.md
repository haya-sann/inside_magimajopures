# 魔法×戦士 マジマジョピュアーズ！ おもちゃ解析

格安でLCDを備えたおもちゃが出回っているとの情報。

解析結果をまとめておきます。

詳細は [Twitter #マジョカアイリスハック](https://twitter.com/search?q=%23%E3%83%9E%E3%82%B8%E3%83%A7%E3%82%AB%E3%82%A2%E3%82%A4%E3%83%AA%E3%82%B9%E3%83%8F%E3%83%83%E3%82%AF) を参照。


## マジョカアイリス 解析

https://www.takaratomy.co.jp/products/magimajopures/toy/25/


LCD自体は 640x48px の解像度だが、搭載されているLCDドライバは内部で 320x96px で保持している。

そのため、640x48pxで用意したバッファを展開する必要がある。

