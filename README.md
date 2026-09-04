# モーターサブマスター / MOTOR SUBMASTER

ニンジャスレイヤーTRPG向けのファンメイド AI活用支援ツールです。

## Web version

このrepositoryは生成済みWeb配布専用です。ブラウザで `index.html` を開くか、GitHub Pagesの公開URLから利用します。

アプリはlocal-firstです。貼り付けたシナリオやMapSpecデータを、アプリ自身がapplication backendへ送信することはありません。AIとの受け渡しも、利用者がClipboardまたは保存した指示書を選んで外部サービスへ渡す経路だけです。

## Distribution-only repository

このrepository内のapplication filesは、private source repository `koyazawa-ninja/trpg-sheet-map-compiler` から生成された配布artifactです。ここでapplication filesを直接編集しないでください。正本はprivate repositoryであり、このrepositoryは第二の開発sourceではなく、distribution-only targetです。public repositoryからprivate sourceへ逆同期しません。

生成内容のprovenanceとpayload hashは `distribution-manifest.json`、third-party runtime noticesは `THIRD_PARTY_NOTICES.txt` にあります。

## License

この配布はMOTOR SUBMASTER自身に新たなlicenseを付与しません。third-party runtime dependency noticesだけを `THIRD_PARTY_NOTICES.txt` に記載します。
