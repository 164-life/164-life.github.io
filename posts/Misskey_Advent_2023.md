## Misskey Fork の話

 

> この記事はMisskey Advent Calendar 2023の最終日(12/25)の記事です。

## はじめに
どうも、こんにちは。ありすと言います。
今回はMisskey Forkの話などをしていきたいと思います。

## お前誰
名前は ありす「別名　Luna」です。
FreelyNext代表で
[Loverskey](https://lovers.1641project.jp)と [Miraiskey](https://github.com/FREELYNEXT/miraiskey)の運営などをしています。
この記事で何かおかしい点や間違えなどを見つけましたら
master@164-67.sbs までよろしくお願いします。

## Misskey Forkの話
ということで、今回は2023年でとても人気/話題になったForkの話と私個人の感想を交えながら話していきます。
※ マイナーなものも紹介していきます。

## [CherryPick](https://github.com/kokonect-link/cherrypick)
CherryPickは2021年から[NoriDev](https://github.com/noridev)氏によってカスタマイズ/メンテナンスされている Misskey Forkですね。
NoriDev氏は自身で [KOKONECT.LINK](https://kokonect.link) / [BETA.KOKONECT.LINK](https://beta.kokonect.link) を運営されており
人気を集めているMisskey Forkになります。

### 機能
通常のMisskeyに加えて

 1. モデレーション機能の強化
 2. Google Translator Platform / Cloud Translation への対応
 3. フォントサイズ機能などの強化
 4. ノートの編集機能/連合機能
 5. グループ機能/チャット機能の復活

などがされています。

### 感想
私も使ったことがありますが、機能も多く、使いやすいと感じました。
かなりお勧めできる Forkです。

### 使われているインスタンス

 - https://kokonect.link
 - https://beta.kokonect.link
 - https://universe.noridev.moe
 - https://stella.place
 ..etc

## [Sharkey](https://git.joinsharkey.org/Sharkey/Sharkey)
Sharkeyは Transfemというチームが開発している 最近人気のMisskey Forkです。
公式インスタンスは [shonk](https://shonk.social) とAmeilaさんが運営している https://transfem.social/ ですね。

公式サイト: https://joinsharkey.org/

私も昔ここのチームの1人でした。

### Transfem とは
Transfemは Sharkeyなどを開発し運営しているグループになります。
主に Mar0xy さん Amelia Yukii さんで構成されています。

### 機能
通常のMisskeyに加えて

 1. Mastodon APIへの対応
 2. 編集機能／連合機能への対応
 3. バックグラウンド画像を設定できる機能
 4. 投稿インポート機能の強化

などが強化されています。

### 感想
CherryPickと比較すると少し機能がないですが、Mastodon APIがあるのが強いですね....
Mastodon APIがあって、最新がいい人におすすめです。

### 使われているインスタンス

 - https://transfem.social
 - https://shonk.social
 - https://sha.bal.ovh
 - https://sakurajima.social
 ..etc

## [るみすきー](https://github.com/SINtyanneru/rumisskey)
るみすきーは 2023年から [るみさん](https://github.com/SINtyanneru) が開発している Misskey Forkになっております。
この Fork は、 https://ussr.rumiserver.com のためだけに開発された Misskey Forkになっており変更点はあまりないことが特徴です。
現在Maintenanceは主に [ありす](https://github.com/164-life) がプルリクエスト経由で行っています。
まだまだこれからのForkなので、機能追加に期待したいです。

## [Nexkey](https://github.com/nexryai/nexkey)
Nexkeyは 2023年から [Nexryai](https://github.com/nexryai)氏が開発している [Misskey v12 LTS](https://github.com/atsu1125/misskey-v12/) ベースの Misskey Forkとなっております。

### 機能
通常のMisskeyに加えて

 1. v13のデザインの改善を取り込み （cherry-picked from [Taiyme Fork](https://github.com/taiyme/misskey)）
 2. Sonicによる検索と過去投稿のインデックス機能を実装
 3. v13で実装された一部機能の実装
 4. インスタンスティッカーやエントランス画面周りの改善
 5. リアクションミュート実装
 6. 配信モード実装
 7. オンラインユーザーを常時表示
 8. 検索をexploreに統合
 9. パスワードハッシュをargon2に
 10. 脆弱性のある依存関係の更新 

などがされています。

### 感想
Misskey v12 から強化がされており、日常使いでは、問題ない Forkだといえます。そして 古いデバイスでも使えるのでいいと思います。
Misskey v12がいい方や、軽いMisskeyがいい方、V13の機能をあまり使わない方などにおすすめできる Forkです。

### 使われているインスタンス

 - https://social.sda1.net
 ..etc

## [Firefish](https://git.joinfirefish.org/firefish/firefish) (旧 Calckey)
皆さんお馴染みの Firefish ですね。
Firefish は  [Kainoa Kanter](https://git.joinfirefish.org/t1c)氏 を中心としたチームで開発されており、Misskey v12ベースの Misskey Forkです。
開発メンバーの中には 日本人のメンバーの方もおり、昔から活発な Misskey Forkですね。
あと、[Sharkey](https://git.joinsharkey.org/Sharkey/Sharkey) と仲がいいのも特徴です。

### 機能
通常のMisskey と比べて

-   UI/UXの改善（特にモバイル）
-   編集機能/連合機能
-   コンテンツのインポート
-   通知の改善
-   サーバーセキュリティの向上
-   アクセシビリティの向上
-   スレッドの改善
-   推奨サーバーのタイムライン
-   OCR画像キャプション
-   新しく改良されたグループ
-   より良い入門チュートリアル
-   Mastodon クライアント/アプリとの互換性
-   ユーザー情報をバックフィルする
...etc
が強化されています。

### 感想
Firefishは Calckey時代も含め 昔からある Misskey Forkですが、機能の強化のし過ぎで、Misskey v12の面影がなくなっていると感じました。
それでも、Misskeyの部分は残っていると感じますし、特別使いづらいということもありません。
なので、Mastodon APIが欲しい人 や Misskey v12がいい方におすすめできる Misskey Forkです。

### 使われているインスタンス

 - https://firefish.social
 - https://calckey.jp (年内終了)
 - https://himagine.club
 - https://misskey.pm
...etc

## [Miraiskey](https://github.com/FREELYNEXT/miraiskey)
Miraiskeyは FreelyNext というチームが開発している Sharkey ベースの Misskey Forkとなっております。
これはまだ開発途中となっているので今後に期待しててください！！
これを機に知っていただけると嬉しいです。

### FreelyNextとは
FreelyNextは [ありす](https://github.com/16467)を中心として、結成されたチームであり、 Misskey Fork 開発 運営 などを主に活動しているチームです。

## あとがき
今回は 今年 話題になった Misskey Fork やマイナーな Misskey Forkを紹介しました。
通常の [Misskey](https://github.com/misskey-dev/misskey) もいいですが、Misskey Forkにはこんなのがあるんだ。と Misskey や Misskey Forkを選ぶ範囲を広げていただき、少しでも興味を持ってくれるといいなと思います。




