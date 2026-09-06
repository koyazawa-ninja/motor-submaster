# モーターサブマスター / MOTOR SUBMASTER

ニンジャスレイヤーTRPG向けのファンメイド AI活用支援ツールです。

## Web version

GitHub PagesのHTTPS公開版はこちらから利用できます。

https://koyazawa-ninja.github.io/motor-submaster/

このrepositoryは生成済みWeb配布専用です。ブラウザで `index.html` を開くか、上記GitHub Pagesの公開URLから利用します。

アプリはlocal-firstです。貼り付けたシナリオやMapSpecデータを、アプリ自身がapplication backendへ送信することはありません。AIとの受け渡しも、利用者がClipboardまたは保存した指示書を選んで外部サービスへ渡す経路だけです。

## Distribution-only repository

このrepository内のapplication filesは、private source repository `koyazawa-ninja/trpg-sheet-map-compiler` から生成された配布artifactです。ここでapplication filesを直接編集しないでください。正本はprivate repositoryであり、このrepositoryは第二の開発sourceではなく、distribution-only targetです。public repositoryからprivate sourceへ逆同期しません。

生成内容のprovenanceとpayload hashは `distribution-manifest.json`、third-party runtime noticesは `THIRD_PARTY_NOTICES.txt` にあります。

## 利用・再配布

MOTOR SUBMASTERは友人やプレイグループへの共有も歓迎します。作者が公開した公式配布物は、内容を変更せず無料であれば共有・再配布できます。公式配布物の内容の改変、改変版の公開・再配布、再販売・有料配布は許可していません。

この条件はMOTOR SUBMASTER作者が権利を有する部分に適用されます。第三者製コンポーネントにはそれぞれ本来のライセンスが適用され、本条件によってその権利を狭めません。第三者製コンポーネントのライセンス・著作権表示等は `THIRD_PARTY_NOTICES.txt` を確認してください。

MOTOR SUBMASTERを利用して利用者が作成したMapSpec、XLSXその他の生成物、および作者がフリー素材として案内している同梱サンプルマップについて、MOTOR SUBMASTER作者は追加の利用制限を設けません。第三者IP、外部AIサービス、利用者が入力した素材等に別の権利・規約がある場合は、それらに従ってください。

ニンジャスレイヤーおよびニンジャスレイヤーTRPG等の権利は各権利者に帰属します。この配布条件はそれら第三者IPについて新たな利用許諾を与えるものではありません。二次創作としての利用は各権利者が公開するガイドライン等に従ってください。

MOTOR SUBMASTERは現状有姿で提供され、特定目的への適合性や無停止・無不具合を保証するものではありません。重要なデータは利用者自身でも保存・確認してください。
