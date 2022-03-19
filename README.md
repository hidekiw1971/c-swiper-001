# compornent（共通部品）

## 概要

- swiper@8(css/js)を使用しています。
- text-rendering: optimizeSpeed;を使用してる場合、注意事項を確認して下さい。

## 仕様

- swiper cdn を使用してます。
- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。

## 後から気付き(未反映分)
- 画像の高さ調整は`.slide-img img`に`height`を設定すると調整可能になる。
- `display: block;`
- `obhect-fit: cover;`
- `height: rem(770);`

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
<img width="405" alt="image" src="https://user-images.githubusercontent.com/99580997/158192436-3d04611f-0af6-477f-8fcd-cf60f32f4996.png">
<img width="779" alt="image" src="https://user-images.githubusercontent.com/99580997/158192523-248722f9-da2d-4266-a195-ce7cc6d72ec1.png">
<img width="1090" alt="image" src="https://user-images.githubusercontent.com/99580997/158192601-a848bc44-2625-45b8-a5f8-a8af77d2bf90.png">

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

- 2022/3/14 swiper@8(css/js)用に改修対応済
- 2022/3/14 初版 作成済（レスポンシブ対応済）
- 2022/3/14 初版 作成中

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
