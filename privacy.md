---
title: Photo Uploader プライバシーポリシー
---

# プライバシーポリシー

- アプリ: Photo Uploader（作者が個人で使う Windows デスクトップアプリ）
- 制定日: 2026-11-02

## 1. アクセスする Google ユーザーデータ

このアプリは Google Photos Library API を通じて、次の2つの権限だけを求めます。

| 権限 | アクセスするもの | 使い道 |
|---|---|---|
| `photoslibrary.appendonly` | なし（追加のみ） | 利用者の写真・動画を、利用者の Google フォトへ追加する |
| `photoslibrary.readonly.appcreateddata` | このアプリが追加した写真の ID・ファイル名などの情報 | 追加した写真が Google フォトにまだあるかを確かめる |

このアプリが追加していない写真、アルバム、アカウントの情報（名前・メールアドレスなど）にはアクセスしません。

## 2. 保存のしかた

- ログインで得た更新用トークンは、利用者の PC の Windows 資格情報マネージャーにだけ保存します。アクセストークンはアプリの実行中にメモリにだけ持ちます。
- 写真の ID などの記録は、利用者の PC の中のファイル（`%LOCALAPPDATA%\PhotoUploader\`）にだけ保存します。
- このアプリはサーバーを持たず、作者を含むほかの誰にも、Google ユーザーデータを送信・共有・販売しません。広告や分析にも使いません。

## 3. 削除のしかた

- アプリのアクセスは、Google アカウントの「サードパーティ製のアプリとサービス」（<https://myaccount.google.com/connections>）からいつでも取り消せます。
- PC に残る記録とトークンは、`%LOCALAPPDATA%\PhotoUploader\` のフォルダと、資格情報マネージャーの `PhotoUploader/Google/RefreshToken` を消すと削除されます。

## 4. Google API サービスのユーザーデータに関するポリシー

このアプリが Google API から受け取った情報の使用と他のアプリへの転送は、[Google API サービスのユーザーデータに関するポリシー](https://developers.google.com/terms/api-services-user-data-policy)（限定使用の要件を含む）に従います。

## 5. 問い合わせ先

<https://github.com/beex-okamura>
