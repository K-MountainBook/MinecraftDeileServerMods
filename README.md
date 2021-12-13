# 2021/12/11：<br>log4j2の脆弱性に対する対策が取れてないので<br>現在サーバ停止中です。
対策が取れ次第再開いたします。
# マインクラフトでいるサーバMOD設定済みファイル

Configured mods config file for Deile's Minecraft Server users

## なんぞねこれ？ (what is this）

マインクラフトでいるサーバ用に設定されたmodの設定ファイル群です。  
mod本体は格納されていません。~ライセンス関連調べるの面倒だから仕方ないね~

## 対象サーバ

forge 1.16.3 - 34.1.0

## 何が入っているの？(what is it contains?)

    MinecraftDeileServerMods
    ├─conf--------------------------modsに含まれるmod用のconfigファイル
    ├─mods
    | └─requiremods.txt-------------必要なmodとそのversionを記載したテキストファイル
    └─README.md---------------------このファイル

## 使い方(manual)

1. [リポジトリ（このページ）](https://github.com/K-MountainBook/MinecraftDeileServerMods) のページへ行って、Codeボタンを押す
1. Downlad ZIPを押下して、zipファイルをダウンロードする
1. 解凍して、中身をサーバの環境のforgeフォルダ内にに上書きコピーする
1. Enjoy!!
![ENJOYPARROT](https://cultofthepartyparrot.com/parrots/tripletsparrot.gif)

## マインクラフトでいるサーバについて(about Deile's Minecraft Server)

友人限定の未公開のサーバです。  
参加したい方は[Twitter](https://twitter.com/deilechang)まで。  
またこの公開内容に問題がある場合も、同様にTwitterへご連絡ください。  

update:2020/10/09 - forgeのバージョンを更新  
update:2020/12/16 - TwitterのアカウントをNonNSFW垢へ変更  
update:2021/03/31 - 安定性保持のため月曜AM5:00にサービスが再起動させるように変更
update:2021/12/12 - log4j2の脆弱性に対する対策が取れてないので、サーバ停止
