<h2>text-size-ajustについて</h2>

ウェブのwantedlyのページを見本にスケッチしていたが、fontsizeをpx指定してもそ見本のページとfontsizが一致してレンダリングされないという現象が起きていた。

<h3>原因と思われること</h3>
ウェブをモバイルでレンダリングするときにフォントサイズが小さすぎると、多くのブラウザで自動でフォントを大きくする。

cromeの検証機能で無理やりスマホのサイズにしていたので見本のフォントサイズが自動拡大され、見た目で一致していなかった。<br>
cromeの検証機能で無理やりスマホのサイズにしていたのがまずかったよう

<h3>text-size-ajust</h3>
text-size-ajustは上記のブラウザの挙動を無効化したり、挙動を変更するときに使う。

ドキュメント<br>
https://developer.mozilla.org/ja/docs/Web/CSS/text-size-adjust



