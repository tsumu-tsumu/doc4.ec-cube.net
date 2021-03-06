---
title: デバッグモード
keywords: debug
tags: [debug, env]
permalink: debug_mode
forder: i18n

---

## 概要

デバッグモードを有効にすることにより、

エラーページにスタックトレース等の詳細な情報を表示することができます。

また、キャッシュファイルをリクエスト毎に生成するようになります。

## デバッグモードの設定


ec-cubeプロジェクトのルートにある.envファイルを開くと、`APP_DEBUG` という定数があります。

`APP_DEBUG` の設定値を変更することで、デバッグモードを切り替えることができます。

`APP_DEBUG=0` の場合、エラー発生時に最小限の表示となります。

`APP_DEBUG=1` に設定すると、デバッグモードが有効となり、

デバッグモード時にエラーが発生すると以下ような画面が表示されます。

![エラー画面](/images/debug_mode/debug_error.png)

一般的には`APP_ENV＝dev`、`APP_ENV＝test`の時は1を設定し、`APP_ENV＝prod`の場合には0を設定します。


