# kadai06_js
JS選手権プロダクト

# ①課題番号-プロダクト名
小学校教科書出典図書検索アプリ

## ②課題内容（どんな作品か）
- Google Books APIを使い、小学校の国語の教科書に掲載されている図書を検索するアプリ
- ISBNを検索した後、カーリル（図書館検索）にジャンプして蔵書のステータスを確認できる
- 2024年4月～2028年3月に採用される三大出版社の国語の教科書の出典元が検索対象（教育出版のみ令和2年度版を掲載）

## ③DEMO
（任意）デプロイしている場合はURLを記入

## ④工夫した点・こだわった点
- htmlのselect プルダウンが冗長になったので、書籍情報をJSONデータを使用することにしました。

## ⑤難しかった点・次回トライしたいこと(又は機能)
- Google Books APIを国立国会図書館サーチAPIに置換したかったのですが、またもやタイムアップとなってしましました。

## ⑥質問・疑問・感想、シェアしたいこと等なんでも
- [質問] 書籍情報をJSONデータで管理することにしたところ、index.htmlを直接開こうとすると、JSONファイルへのアクセスがブロックされてしまいます。
であれば、最初からJSONファイル（.json）なんか使わずにJavaScriptファイル（.js）を利用すればよかったのか、それでもデータの管理や更新の観点からは、JSONファイルを使用する方が望ましいのか、なんだかわからなくなってしまいました。

- [感想] CORSエラーが解決できません！助けて！！！
