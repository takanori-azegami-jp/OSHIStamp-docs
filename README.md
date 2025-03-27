# OSHIStamp（おしスタンプ）：YouTube 動画タイムスタンプ作成支援ツール

[日本語](README.md) | [English](README-EN.md)

YouTube 動画のタイムスタンプ作成を支援する無料ツールです。

直感的な操作で簡単にタイムスタンプを作成・編集できるだけでなく、上級者にはショートカットキーを活用したスピーディーな作業も可能です。

推し活をもっと楽しく、便利にするお手伝いをします。ぜひご活用ください！

## 画面イメージ

![alt text](./images/image-screen.png)

## 主な機能

- **タイムスタンプの追加と挿入**

  画視聴中に「＋」ボタンをクリックするだけで、現在のタイムスタンプを最終行に追加できます。

  「|→」ボタンをクリックすればカーソル位置にタイムスタンプを挿入できます。

- **タイムスタンプ形式の変更**

  タイムスタンプは以下の 2 つの形式から選択可能：

  - 短縮形式（例: 2:30, 1:45:15）
  - 完全形式（例: 00:02:30, 01:45:15

  ※ショートカットキーで ±1 秒の調整する場合も、選択した形式が適用されます。

- **タイムスタンプからのジャンプ**

  タイムスタンプのリンクをクリックすると、動画のその時間に移動できます。

  ※タイムスタンプを選択している場合はショートカットキーでその時間に移動できます。

- **動画の早送り、早戻し**

  ボタンで 5 秒単位、ショートカットキーで 1 秒単位のスキップ操作が可能。

- **動画のスクリーンショット**

  動画のスクリーンショットを「PNG 形式」でダウンロードできます。

- **タイムスタンプのコピー**

  ワンクリックで作成したタイムスタンプをクリップボードにコピーできます。

- **再生時間の確認**

  画面上で動画の再生時間をリアルタイムで確認できます。

- **自動保存機能**

  タイムスタンプは自動でローカルストレージに保存され、作業中にデータが消える心配はありません。


- **カラーモード機能**

  ダークモードに対応。　

- **推し画像の表示**

  好きな画像をアップロードして画面に表示することで、推し活のモチベーションをアップ！
  （対応サイズ: 500px × 70px、形式: JPG, PNG, SVG）

- **最小化機能**

  必要のない時は画面を右下に最小化が可能です。

## ショートカットキー（CTRL + SHIFT または ALT）

- **CTRL + SHIFT/ALT + S** ：タイムスタンプの追加
- **CTRL + SHIFT/ALT + F** ：タイムスタンプの挿入
- **CTRL + SHIFT/ALT + →** ：1 秒進む
- **CTRL + SHIFT/ALT + ←** ：1 秒戻る
- **CTRL + SHIFT/ALT + ↑** ：選択したタイムスタンプを+1 秒調整（複数選択可）
- **CTRL + SHIFT/ALT + ↓** ：選択したタイムスタンプを-1 秒調整（複数選択可）
- **CTRL + SHIFT/ALT + Enter** ：カーソル行のタイムスタンプの時間にジャンプ（選択中のタイムスタンプがあればそちらを優先）

## 更新履歴

- バージョン 1.0.0：初回リリース。
- バージョン 1.1.0：ローカライズ対応。（de、en、en_US、es、fr、ja、pt_BR、zh_CN）
- バージョン 1.2.0：ローカライズ対応。（ru）
- バージョン 1.3.0：縦横リサイズ機能を追加、画面サイズの調整、タイムスタンプの後ろに半角スペースを追加。
- バージョン 1.4.0: ショートカットキー「Ctrl + Shift + F」でタイムスタンプを挿入を追加。
- バージョン 1.5.0: ローカライズ対応。（id、it、nl、vi）
- バージョン 1.6.0: 横スクロールバーのガタツキを修正。
- バージョン 1.6.0: 横スクロールバーのガタツキを修正。
- バージョン 1.7.0: 短縮形式のタイムスタンプ追加、挿入、調整を h:m:ss から h:mm:ss 形式に変更。
- バージョン 1.8.0: 動画のスクリーンショット機能を追加、推し画像サイズの幅を変更: 430px→530px
- バージョン 1.9.0: ショートカットの修正（SHIFT または ALT に変更）、ローカライズ対応を変更（en、en_GB、en_US、es、ja、ru、zh_CN、zh_TW）
- バージョン 1.10.0: 全画面表示の時に最小化アイコンを非表示化、推し画像サイズの幅を変更: 530px→490px
- バージョン 1.11.0: カラーモード切替え機能追加（ダークモードに対応）
- バージョン 1.12.0: 購入画面（スパーチャット等）が有効にならない問題を解消、画面全体のUIを見直し、推し画像サイズの幅を変更: 490px→500px、ローカライズ対応を変更（en_US、es、ja、zh_CN、zh_TW）-
- バージョン 1.13.0: 推し画像の表示/非表示の切替え機能を追加
- バージョン 1.14.0: 1行に複数のタイムスタンプがある場合に対応し、CTRL + SHIFT/ALT + Enter の時間ジャンプは選択中のタイムスタンプを優先するように機能追加
- バージョン 1.15.0: タイムスタンプ挿入ボタンを追加、画像の表示/非表示アイコン変更
  
## プライバシーとデータ管理

本ツールはユーザーのデータを一切収集しません。すべてのデータはローカルに保存され、安全に管理されます。

## 免責事項

本ツールを利用した結果として生じた損失や損害について、開発者は一切の責任を負いかねます。あらかじめご了承ください。

## プライバシー

[プライバシーポリシー](https://takanori-azegami-jp.github.io/OSHIStamp-docs/)

## 問い合わせ

- [お問い合わせは、こちらからお願いします](https://github.com/takanori-azegami-jp/OSHIStamp-docs/issues)

  **対応可能言語：日本語、英語**

## 参考サイト

このプロジェクトの開発にあたり、以下のサイトを参考にさせていただきました。

- [piny940 / kokosuko-stamp](https://github.com/piny940/kokosuko-stamp)

---

![alt text](./images/image-logo.png)
