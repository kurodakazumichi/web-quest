# README

## Apache(Mac)
`sudo apachectl restart`

## SASSの監視コマンド
`sass --watch ./src/sass:./css --no-cache --sourcemap=none`

- --wacth 変更を監視するフォルダの指定
- --no-cache  キャッシュを作らない設定
- --sourcemap=none  mapファイルを作らない設定

## TypeScriptの監視コマンド

`tsc --outDir ./js/ --watch ./src/ts/page01.ts`

- --out 出力ファイル名の指定
- --watch 変更を監視するフォルダを指定
