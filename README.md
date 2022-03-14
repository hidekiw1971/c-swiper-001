# compornent（共通部品）

## 概要

- swiper@8(css/js)を使用しています。
- text-rendering: optimizeSpeed;を使用してる場合、注意事項を確認して下さい。

## 仕様

- swiper cdn を使用してます。
- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。

## 注意事項

- swiper v7 以降を使用する場合、rest.css の以下の部分をコメントにする。表示されない為。
- body {
- min-height: 100vh;
- // text-rendering: optimizeSpeed;
- line-height: 1.5;
- }

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> swiper をコピペ。

## イメージ画像

- xxx

## portfolio url:

- https://c-0024.wtb.cfbx.jp/

## 参考にしたサイト

- Swiper+CSS のみ！ズームアップしながらフェードインで切り替わるスライダーの実装方法
- https://wemo.tech/2961
- 【2022 年最新】簡単にスライドが使える Swiper.js の使い方
- https://noanavi.com/web/swiper-js-2021/
- swiper official
- https://swiperjs.com/

## 更新履歴

- 2022/3/14 初版作成完了（レスポンス対応済）
- 2022/3/14 初版 作成済（レスポンシブ対応済）
- 2022/3/14 初版 作成中

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
