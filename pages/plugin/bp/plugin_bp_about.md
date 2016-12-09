---
title: プラグインベストプラクティスとは
keywords: plugin handler spec
tags: [plugin, spec]
sidebar: home_sidebar
permalink: plugin_bp_about
folder: plugin/bp
---
---

EC-CUBE3では標準機能では存在しない機能を拡張できるようにプラグイン機構を用意しています。

プラグインを作成しようとしたときに最初に戸惑う内容として、

- どんなことがプラグインでできるのか
- どのようにプラグインを作成すれば良いのか
- プラグインでは何をしてもいいのか

が主にあげられます。

今回これらの内容を元に、プラグインを作成する上で指標となるように、

- どのようにプラグインを作成すれば良いのか
- プラグインでできること、難しいこと
- プラグインで何をできるのか

という内容をまとめました。

このプラクティスに書いていることは、既存のプラグインに対して必ずしも従う必要はありません。  
必ずしもこれらの推奨案に従わなくても良いですが今後の拡張性を考えた場合、準拠したほうが望ましい内容もあります。
新しくプラグインを作成したときの参考にしてください。

__参考資料__

- [プラグイン仕様書](http://downloads.ec-cube.net/src/manual/v3/plugin.pdf){:target="_blank"}