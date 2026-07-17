※ English version is available below. Please scroll down if you prefer English.

## Developer Philosophy
理念全文はこちら  
→ [Developer Philosophy & Ethical Statement](PHILOSOPHY.md)

製品マニュアルはこちら  
→ [📥 TsAI_Pose_engine_manual.pdf をダウンロード](https://github.com/ts-ai-kobo/ts_ai_kobo_activator_public/releases/download/v1.0.0/TsAI_Pose_Engine_manual.pdf)


🟦 購入前の重要なご案内
本製品をご検討いただく際は、製品マニュアルと以下の内容を必ずご確認ください。
内容にご同意いただけない場合は、購入はお控えください。
本製品は安売りを行いません。理解し、同意いただける方のみご購入ください。

🟦 アクティベーションIDとDRMワンタイムインストーラーについて
本製品は、正規ユーザー様のみが安全にご利用いただけるよう、
PC環境とアクティベーションIDを照合する専用DRMを採用しています。

お客様からお知らせいただいたアクティベーションIDをもとに、
世界に一つだけの DRM ワンタイムインストーラーを作成し、
ご指定のメールアドレスへ一度だけ配信します。

DRMワンタイムインストーラーは「一度だけ実行できる鍵」であり、
発行された PC 環境でのみ動作します。

PC変更  
複数台利用  
コピー・複製  

これらは一切できません。

DRMの仕組みに不安がある場合や、
動作原理をご理解いただけない場合は、購入をおすすめいたしません。
本製品は、DRM仕様をご理解いただける方のみを対象としています。

🟦 右ペインの「Activator ダウンロードリンク」について
本説明ページの右側にある **Releases セクション** からダウンロードしてください。
DRMワンタイムインストーラーに必要なアクティベーションIDを発行するための
Activatorを事前にダウンロードできるリンクを掲載しています。

購入前に以下をご確認いただけます：

- Activator が正常にダウンロードできるか  
- セキュリティソフトで誤検出されないか  
- 実行形式に不安がないか  

これらを事前に確認し、少しでも不安がある方は購入されなくて構いません。
本製品は「理解し、納得した方だけが購入する」ことを前提としています。

🟦 インストーラーの受信と実行手順
購入時にお知らせいただいたアクティベーションIDとメールアドレス宛に、
DRMワンタイムインストーラーを送信いたします。

受信できているかご確認ください  
迷惑メールフォルダもご確認ください  

インストーラーを実行すると、DRMが  
C:\ProgramData\ts_ai_kobo にインストールされます。

DRMは一度限りの照合処理を行い、
正規ライセンス保持者であることを確認します。

🟦 正規ユーザー様はこの項目は読み飛ばして構いません
転売行為・不正利用について  
正規ユーザー様の保護のため、
転売行為・複製・複数PCへの導入などの不正利用は固く禁止しております。

以下のような事例は、不正行為とみなす場合があります。

- 他のPCへ誤って導入した  
- 複数PCへコピーしようとした  
- 複数のDRMワンタイムインストーラーを実行しようとした  
- DRM照合を回避しようとした  

不正と判断された場合、

- DRMワンタイムインストーラーの再発行  
- 返金対応  
- 再購入  

はいずれもできません。

本製品は「正しく使う意思のある方」にのみ提供しております。
ご理解のほどよろしくお願いいたします。

# はじめに
1. GitHub Releases ページから ts_ai_kobo_runtime.zip をダウンロードしてください。  
2. このリポジトリ右側の Releases セクションにあります。  
   上部の緑色の Code ボタンからのダウンロードは使わないでください。正しく動作しません。  
3. ZIP を展開してください。  
4. 展開したフォルダ内の ts_ai_kobo_runtime.exe を実行してください。  
5. フォルダ構成を変更すると動作しません。

Windows SmartScreen により「PC が保護されました」と表示される場合があります。
これは本アプリが新規に作成された実行ファイルであり、
コード署名が付与されていないために表示される一般的な警告です。

「詳細情報」→「実行」を選択することでご利用いただけます。
本アクティベーションID発行ツールは完全オフラインで動作し、外部通信・自己複製・常駐などの
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

ts_ai_kobo_runtime.zip のハッシュ値  
SHA256    4d2b804796bbcd124c31930dd2e2510cfc1d142b11b4af28d9cb779b50088013

ts_ai_kobo_runtime.exe のハッシュ値  
SHA256    45c573f395d656148999d8f2efd9cdfeac675dc640dfc6ed982f31a5aa6c730f

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
- ProgramData に nonce.json（設定ファイル）を書き込みます  

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

🟦 Important notice before purchase  
Before considering the purchase of this product, please make sure to read the product manual and the information below.  
If you do not agree with the contents, please refrain from purchasing.  
This product will not be sold at a discount. It is intended only for those who understand and agree with these terms.

🟦 About the Activation ID and DRM One-Time Installer  
This product uses a dedicated DRM system that verifies your PC environment and Activation ID  
to ensure that only legitimate users can use it safely.

Based on the Activation ID you provide,  
a **unique DRM One-Time Installer** (only one in the world for that ID) will be created  
and sent once to the email address you specify.

The DRM One-Time Installer is a **“key that can be executed only once”**  
and works **only on the PC environment for which it was issued**.

- Changing PCs  
- Using on multiple PCs  
- Copying or duplicating  

None of these are allowed.

If you feel uneasy about this DRM mechanism,  
or if you do not understand how it works, we do **not** recommend purchasing.  
This product is intended only for users who understand and accept the DRM specifications.

🟦 About the “Activator download link” in the right pane  
Please download from the **Releases section** on the right side of this repository page.  
There you will find a link to download the **Activator**,  
which is used to generate the Activation ID required for the DRM One-Time Installer.

Before purchasing, you can check:

- Whether the Activator downloads correctly  
- Whether your security software falsely detects it as malware  
- Whether you feel comfortable with the executable format  

If you feel even slightly uneasy after these checks, you do not need to purchase.  
This product is offered on the premise that **only those who understand and are satisfied** proceed to buy.

🟦 Receiving and running the installer  
The DRM One-Time Installer will be sent to the email address you provided at the time of purchase,  
together with your Activation ID information.

- Please confirm that you have received the email  
- Also check your spam/junk folder  

When you run the installer, the DRM will be installed to:  
`C:\ProgramData\ts_ai_kobo`

The DRM performs a one-time verification process  
to confirm that you are the legitimate license holder.

🟦 Legitimate users may skip this section  
### About resale and unauthorized use  
To protect legitimate users,  
resale, duplication, and installation on multiple PCs are strictly prohibited.

The following cases may be treated as unauthorized use:

- Installing on a different PC than intended  
- Attempting to copy to multiple PCs  
- Attempting to run multiple DRM One-Time Installers  
- Trying to bypass DRM verification  

If such behavior is judged as unauthorized:

- Reissuing the DRM One-Time Installer  
- Refunds  
- Repurchasing  

will **not** be possible in any case.

This product is provided **only to those who intend to use it correctly**.  
Thank you for your understanding.

# Getting started

1. Download `ts_ai_kobo_runtime.zip` from the GitHub **Releases** page.  
2. It is located in the **Releases** section on the right side of this repository page.  
   Do **not** use the download from the green **Code** button at the top; it will not work correctly.  
3. Extract the ZIP file.  
4. Run `ts_ai_kobo_runtime.exe` inside the extracted folder.  
5. Do not change the folder structure; the application will not work if you do.

Windows SmartScreen may display “Windows protected your PC”.  
This is a common warning shown for newly created executables  
that do not yet have a code-signing certificate.

You can proceed by selecting **“More info” → “Run anyway”**.  
This Activation ID generation tool works completely offline and does not perform  
any external communication, self-replication, or resident/background behavior  
commonly associated with malware, so you can use it with confidence.

# ts_ai_kobo Activator (pre-purchase safety check)

This application generates a unique key (Activation ID)  
to issue a license for **one specific PC** only.  
It is designed to prevent duplication and unauthorized use of the product  
and to ensure that only legitimate purchasers can use it safely.

This repository publishes `Activator.exe` as a **pre-purchase check tool**,  
so that you can verify on your own PC  
whether any virus or malware detection occurs before buying the product.

The product itself and the internal DRM logic are **not** included here.  
Only the safety-check tool is provided.

Hash values for `ts_ai_kobo_runtime.zip`  
SHA256    `4d2b804796bbcd124c31930dd2e2510cfc1d142b11b4af28d9cb779b50088013`

Hash values for `ts_ai_kobo_runtime.exe`  
SHA256    `45c573f395d656148999d8f2efd9cdfeac675dc640dfc6ed982f31a5aa6c730f`

---

## ✔ Why the Activator is published (important)

Modern security software relies heavily on heuristic (behavior-based) detection,  
which can sometimes flag normal applications as malware  
depending on the specific operations they perform.

The ts_ai_kobo Activator is designed with the following safe characteristics:

- Completely offline operation  
- No transmission of personal information  
- No self-replication  
- No resident/background processes  
- No encryption routines  
- Writes only `nonce.json` (a configuration file) to `ProgramData`  

However, due to differences in user environments and security software settings,  
it is impossible to guarantee that false positives will **never** occur.

Therefore, to allow users to verify safety in their own environment **before purchase**,  
we publish **Activator.exe** so that anyone can freely download it  
and perform a pre-check.

This provides the following benefits:

- Users can confirm that no virus detection occurs before purchasing  
- Users can buy with greater confidence  
- It helps prevent trouble or complaints caused by false positives  
- It avoids misunderstandings such as “I was forced to install dangerous software”  

This publication is a measure for **user protection and transparency**.

---

## ✔ If a virus alert is triggered

The Activator operates completely offline and does not perform  
any behavior typical of malware, such as sending personal information,  
self-replication, or running as a resident process.  

However, due to differences in security software settings and environments,  
false positives may still occur.

If a detection alert appears, please follow these steps:

1. Update your security software to the latest version  
2. Scan `Activator.exe` again  
3. If necessary, use an exclusion/allowlist setting  
4. Contact the seller with the detection details (we will review them)  
5. Use your security software’s false-positive report form  

---

## ✔ If you feel uneasy, please refrain from purchasing (important)

Although the Activator is designed with a safe structure,  
false positives from security software may **not** be completely avoidable  
depending on the user’s environment.

For that reason:

**If you feel uneasy about safety, or are highly sensitive to security software behavior,  
please refrain from purchasing.**

This is a measure to prevent user anxiety; it is not a forced restriction.

---

## ✔ What this tool can do

- Generate an Activation ID for ts_ai_kobo products  
- Allow the seller to create a dedicated installer based on the generated ID  
- Operate completely offline without sending any personal information  

---

## ✔ What this tool cannot do

- Install the product  
- Launch the product  
- Change the license  
- Disable or remove DRM  
- Download the product itself  

---

## ✔ How to use

1. Download `Activator.exe`  
2. Run it, read the explanation to the end, and check the agreement box  
3. Click “Generate Activation ID”  
4. Copy the displayed ID and send it to the seller  
5. Wait for the dedicated installer to be sent back to you  

---

## ✔ Important notes

- This tool uses information in the folder `C:\ProgramData\ts_ai_kobo`  
- If you delete, move, or modify this folder, the product may not work correctly  
- Resale and reverse engineering are prohibited  
- Use of this application is governed by the license agreement and does not waive any copyrights  

---

## ✔ About the product itself

This repository does **not** contain the product, DRM logic, or encryption nodes.  
A dedicated installer will be provided after purchase.

---

## ✔ Contact

For questions about the product, please contact us via the sales page.

