---
title: Photo Uploader
---

# Photo Uploader

Photo Uploader は、作者が自分の写真をバックアップするために作った、個人用の Windows デスクトップアプリです。一般には配布していません。

カメラから取り込んだ写真の原本を作者の Synology NAS に保存し、縮めた写真を作者の Google フォトへアップロードして、両方に届いたことを確かめます。

## Google フォトの利用

このアプリは Google Photos Library API を使い、次の2つの権限だけを求めます。

| 権限 | 使い道 |
|---|---|
| `photoslibrary.appendonly` | 写真・動画を Google フォトへ追加する |
| `photoslibrary.readonly.appcreateddata` | このアプリが追加した写真が、まだ Google フォトにあるかを確かめる |

Google から受け取った情報の扱いは [プライバシーポリシー](privacy.html) をご覧ください。

ソースコードと問い合わせ先: <https://github.com/beex-okamura>
