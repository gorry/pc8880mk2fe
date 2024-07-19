
# ◇PC-8880mk�UFE
Notes on creating PC-8880mk�UFE  
PC-8880mk�UFE作成についてのメモ  

## これはなに？
「動作しないPC-8001mk�U」と「動作するがマザーボードのみのPC-8801FE」が当方の手許にありました。せっかくだからニコイチしましょう…ということで、PC-8001mk�Uの筐体にPC-8801FEマザーボードを収めてみることにしました。作られたマシンには「PC-8880mk�UFE」と命名しました。

![pc8880mk2fe](https://github.com/user-attachments/assets/25bbfd8f-cf0f-49ac-aed0-f554fb23eeb1)

この文書は、PC-8880mk�UFEの作成について扱われた技術についてのメモです。

## 構成について
PC-8880mk�UFEは、以下の要素から構成されています。
1. PC-8001mk�Uの筐体
2. PC-8001mk�Uの電源
3. PC-8001mk�Uのキーボード
4. PC-8001mk�Uの内蔵拡張I/Oボックス
5. PC-8801FEのマザーボード
6. 「PC-8001mk�Uのキーボード」と「PC-8801FEのマザーボード」を接続するためのモジュール
7. PC-8801FEのFDD I/Fを外部機器に接続するためのケーブル

## 「PC-8001mk�Uのキーボード」と「PC-8801FEのマザーボード」を接続するためのモジュール
「PC-8001mk�Uのキーボード」と「PC-8801FEのマザーボード」を接続するために、Raspberry Pi Picoでモジュールを作成しています。詳細は以下をご覧ください。
- https://github.com/gorry/p8kbto88

## PC-8801FEのFDD I/Fを外部機器に接続するためのケーブル
PC-8801FEのマザーボードには、2つのFDD I/Fコネクタが実装されています。それぞれDrive1/Drive2用で、20pin 1.27mmピッチのFFCが使用されています。PC-8880mk�UFEでは、筐体外部に用意したFDDをこれらのコネクタに接続するためのケーブルを作成しています。詳細は以下をご覧ください。
- https://github.com/gorry/pc8880mk2fe/tree/main/fddif

ケーブルの筐体外側のコネクタにはMILコネクタ（34ピン）を使用し、FDDエミュレータ「FDX68」を接続する想定となっています。FDX68については、以下をご覧ください。
- http://retropc.net/gimons/fdx68/

FDD実機を接続することも可能です。その場合、第1ドライブはDS0、第2ドライブはDS2のジャンパピンを接続してください。

## 著作権表記

Copyright 2024 Hiroaki GOTO as GORRY

本プロダクトは、自由かつ無償で使用・コピー・配布・変更・流用を行うことができます。また許可なく再配布・出版・販売を行うことができます。  
本プロダクトは、無保証です。使用した、あるいはしなかったことによる一切の責任は使用者にあるものとします。  
本プロダクトは、以下URLを配布先とします。利便性などのためにこれ以外のURLで配布することがありますが、以下が最も正式なものであり、完全な最新のパッケージを得ることができます。  

## 連絡先

https://github.com/gorry/p8kbto88

## [EOF]
