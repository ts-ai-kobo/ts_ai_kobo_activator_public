※ English version is available below. Please scroll down if you prefer English.

## Developer Philosophy
理念全文はこちら  
→ [Developer Philosophy & Ethical Statement](PHILOSOPHY.md)

# はじめに
1. GitHub Releases ページから ts_ai_kobo_runtime.zip をダウンロードしてください。
2. この画面の右ペインの中にあります。
   ここの上にある緑色のCodeの中にあるダウンロードは使わないでください。正しく動作しません。
3. ZIP を展開してください。
4. 展開したフォルダ内の ts_ai_kobo_runtime.exe を実行してください。
5. フォルダ構成を変更すると動作しません。

Windows SmartScreen により「PC が保護されました」と表示される場合があります。
これは本アプリが新規に作成された実行ファイルであり、
コード署名が付与されていないために表示される一般的な警告です。

「詳細情報」→「実行」を選択することでご利用いただけます。
本アプリは完全オフラインで動作し、外部通信・自己複製・常駐などの
マルウェアが好む挙動は一切ありませんのでご安心ください。

# ts_ai_kobo Activator（事前安全確認用）

このアプリは、あなたのPC１台にだけライセンスを発行するための
固有の鍵（アクティベーションID）を生成する仕組みです。
製品の複製や不正利用を防ぎ、正規の購入者のみが安全に利用できるようにする目的で設計されています。

このリポジトリは、ts_ai_kobo 製品をご購入いただく前に  
お使いの PC でウイルス判定が出ないか確認していただくための  
事前チェック用アクティベーター（Activator.exe）を公開しています。

製品本体や DRM の内部構造は含まれておらず、  
安全性確認のためのツールのみを公開しています。

te_ai_cobo_runtime.zipのハッシュ値
SHA256    4d2b804796bbcd124c31930dd2e2510cfc1d142b11b4af28d9cb779b50088013

ts_ai_kobo_runtime.exeのハッシュ値
AHA256    45c573f395d656148999d8f2efd9cdfeac675dc640dfc6ed982f31a5aa6c730f

---

## ✔ なぜ Activator を公開しているのか（重要）

近年のセキュリティソフトはヒューリスティック判定（挙動ベースの自動判定）が強化されており、  
正常なアプリケーションであっても、特定の処理内容によって誤ってウイルス判定される場合があります。

ts_ai_kobo の Activator は以下のように安全な構造で設計されています：

- 完全オフライン動作  
- 個人情報の送信なし  
- 自己複製なし  
- 常駐なし  
- 暗号化処理なし  
- ProgramData に書き込むのは nonce.json（設定ファイル）のみ  

しかし、ユーザーの環境によってはセキュリティソフトの設定差により  
誤検出が発生する可能性を完全にゼロにすることはできません。

そのため、購入前にユーザー自身の環境で安全性を確認していただけるよう、  
**Activator.exe を公開し、誰でも自由にダウンロードして事前チェックできるようにしています。**

これにより、

- 購入前にウイルス判定が出ないことをユーザー自身が確認できる  
- 安心して購入できる  
- 誤検出によるトラブルやクレームを防止できる  
- 「危険なソフトをインストールさせられた」という誤解を防げる  

というメリットがあります。

本公開は、ユーザー保護と透明性のための措置です。

---

## ✔ 万一ウイルス判定が出た場合の対応

本 Activator は完全オフライン動作であり、個人情報の送信・自己複製・常駐などの  
マルウェアが好む挙動を一切含んでいません。  
しかし、セキュリティソフトの設定や環境差により、誤検出が発生する可能性があります。

誤検出が発生した場合は、以下の手順を行ってください。

1. セキュリティソフトを最新の状態に更新する  
2. Activator.exe を再度スキャンする  
3. 必要に応じて除外設定を利用する  
4. 販売者へ検出内容をご連絡いただく（確認を行います）  
5. セキュリティソフトの誤検出報告フォームをご利用いただく  

---

## ✔ 不安な方は購入をお控えください（重要）

本 Activator は安全な構造で設計されていますが、  
セキュリティソフトの誤検出は **ユーザー環境によって完全に防ぎきれない場合があります**。

そのため、

**安全性に不安がある方、セキュリティソフトの挙動に敏感な方は、購入をお控えください。**

これは、ユーザーの不安を取り除くための措置であり、強制ではありません。

---

## ✔ このツールでできること

- ts_ai_kobo 製品のアクティベーションIDを生成します  
- 生成された ID を販売者へ送ることで、専用インストーラーが作成されます  
- 個人情報の送信は一切ありません（完全オフライン動作）

---

## ✔ このツールでできないこと

- 製品のインストール  
- 製品の起動  
- ライセンスの変更  
- DRM の解除  
- 製品本体のダウンロード  

---

## ✔ 使い方

1. Activator.exe をダウンロード  
2. 実行して説明文を最後まで読み、同意チェックを入れる  
3. 「アクティベーションIDを生成」を押す  
4. 表示された ID をコピーして販売者へ送信  
5. 専用インストーラーの返信をお待ちください

---

## ✔ 注意事項（重要）

- このツールは **C:\ProgramData\ts_ai_kobo** フォルダの情報を使用します  
- フォルダを削除・移動・改変すると製品が正常に動作しません  
- 転売・リバースエンジニアリングは禁止されています  
- 本アプリの使用は「利用許諾」に基づくものであり、著作権を放棄するものではありません

---

## ✔ 製品本体について

このリポジトリには製品本体・DRMロジック・暗号化ノードは含まれていません。  
購入後に専用インストーラーが提供されます。

---

## ✔ お問い合わせ

製品に関するご質問は販売ページよりお問い合わせください。



## English Manual

## Developer Message (English Version)

Below is the English version of the developer message.  
This section explains the philosophy, purpose, and safety considerations behind the ts_ai_kobo Activator.

---

## Introduction
Please download **ts_ai_kobo_runtime.zip** from the **GitHub Releases** page.  
It is located in the right-hand pane of this repository.

Do **not** use the green “Code → Download ZIP” button above.  
That ZIP does not contain the correct runtime structure and will not work properly.

1. Download ts_ai_kobo_runtime.zip from Releases  
2. Extract the ZIP  
3. Run **ts_ai_kobo_runtime.exe** inside the extracted folder  
4. Do not change the folder structure — the application will not function if modified

Windows SmartScreen may display “This PC is protected” because this executable is newly created and does not yet have a code-signing certificate.  
Click **“More info” → “Run anyway”** to proceed.

This application operates **fully offline**, performs **no external communication**, does **not self-replicate**, and does **not remain resident**.  
It does not exhibit any behavior associated with malware.

---

## About the ts_ai_kobo Activator (Pre‑Purchase Safety Check)

This application generates a **unique Activation ID** tied to your PC.  
It is used to issue a license that allows only your machine to run the product, preventing unauthorized copying or misuse.

This repository provides the Activator so that users can **verify that their security software does not falsely flag the application** before purchasing the product.

The product itself, DRM logic, and internal mechanisms are **not included** here.  
Only the safety-check tool is published.

**SHA256 hash of ts_ai_kobo_runtime.zip**  
4d2b804796bbcd124c31930dd2e2510cfc1d142b11b4af28d9cb779b50088013

**SHA256 hash of ts_ai_kobo_runtime.exe**  
45c573f395d656148999d8f2efd9cdfeac675dc640dfc6ed982f31a5aa6c730f

---

## Why the Activator Is Publicly Available
Modern security software relies heavily on heuristic (behavior-based) detection.  
Even safe applications may be incorrectly flagged depending on their internal operations.

The ts_ai_kobo Activator is designed with safety in mind:

- Fully offline operation  
- No transmission of personal data  
- No self-replication  
- No resident processes  
- No encryption routines  
- Writes only a single file (nonce.json) to ProgramData  

However, heuristic detection varies by environment, and **false positives cannot be completely eliminated**.

To protect users and ensure transparency, the Activator is published so that anyone can freely test it in their own environment **before purchasing**.

This allows users to:

- Confirm that no virus warnings occur  
- Purchase with confidence  
- Avoid misunderstandings or unnecessary support issues  
- Prevent concerns such as “I was forced to install something dangerous”

This publication is for **user protection and transparency**.

---

## If a Virus Warning Occurs
Although the Activator contains no malicious behavior, false positives may occur depending on your security software.

If this happens:

1. Update your security software  
2. Scan the Activator again  
3. Add an exclusion if necessary  
4. Contact the seller with the detection details  
5. Submit a false-positive report to your security vendor  

---

## If You Feel Uncertain, Please Do Not Purchase
While the Activator is designed to be safe,  
**false positives cannot be completely prevented** due to differences in user environments.

If you feel uneasy about this,  
**please refrain from purchasing the product.**  
This is to ensure your peace of mind.

---

## What This Tool Can Do
- Generate an Activation ID for your PC  
- Allow the seller to create a personalized installer  
- Operate entirely offline without sending any personal data  

---

## What This Tool Cannot Do
- Install the product  
- Launch the product  
- Modify licenses  
- Remove DRM  
- Download the product itself  

---

## How to Use
1. Download Activator.exe  
2. Run it and read the explanation to the end  
3. Check the agreement box  
4. Click “Generate Activation ID”  
5. Send the displayed ID to the seller  
6. Wait for your personalized installer  

---

## Important Notes
- The tool relies on the folder **C:\ProgramData\ts_ai_kobo**  
- Deleting, moving, or modifying this folder will break the product  
- Resale and reverse engineering are prohibited  
- Use of this application is governed by the license agreement; copyright is not waived  

---

## About the Product
This repository does **not** contain the product itself, DRM logic, or encryption nodes.  
A personalized installer will be provided after purchase.

---

## Contact
For product-related questions, please contact the seller through the official sales page.

