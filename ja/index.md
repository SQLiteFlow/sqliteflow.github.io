---
layout: default
title: SQLiteFlow
description: Mac 用の SQLite エディタ
---

## 紹介
SQLiteFlowは、直感的で安定した信頼性の高いMacとiOS用のSQLiteエディタです。

## プラットフォーム
macOS 14.0+ / [iOS 17.0+](iOS)

## ダウンロード
バージョン 6.7.0 | 2025-07-20 | <a href="ReleaseNotes" target="_blank">リリースノート</a>
<br/><br/>[![Download](macOS/DownloadOnTheMacAppStore.svg)](macappstores://itunes.apple.com/app/id1378587993)


## 機能

**クエリ エディター**

- 複数のクエリの実行。
- 構文の強調表示をカスタマイズします。
- SQL のオートコンプリート。
- クエリを書式設定します。
- カスタム スタイルを使用してクエリをコピーします。
- 最近のクエリ セッションを貼り付けます。
- クエリを説明します。

*クエリ エディター - 複数クエリの実行*
![Editor](macOS/Editor.png)

*クエリ エディター - カスタム スタイルを使用したクエリのコピーと設定*
![Editor - CopyWithCustomStyle](macOS/CopyWithCustomStyle.png)

**データ エディタ**

- テーブルデータの表示、編集、追加
- 便利なデータフィルタを使用してテーブルデータを表示します。
- BLOB を 16 進数として編集し、可能であれば画像として BLOB を表示します。
- JSONB を JSON として編集します。
- データをCSV、JSON、Markdownにコピーします。可能であれば、挿入ステートメントまたは更新ステートメントにデータをコピーします。

*データ エディタ*
![](macOS/DataEditor.png)

**テーブル スキーマ**

- テーブルフィールド、インデックス、外部キー、チェックの表示、編集、追加。
- トリガーを表示します。
- DDL を表示します。
- テーブルを変更するためのクエリをプレビューします。

*テーブルの変更 - フィールド*
![Alter Table - Fields](macOS/AlterTable.png)

*テーブルの変更 - プレビュー*
![Alter Table - Preview](macOS/AlterPreview.png)

**インポート**
- CSV データのインポートをサポートします。
- JSON データのインポートをサポートします。
- SQLファイルによるデータのインポートをサポートします。

*CSV テキストからインポート*
![Import - Import from CSV Text](macOS/ImportFromCSV.png)

**ダークモード**
- macOS 10.14+のダークモードをサポートしています。

**データベース統計**
- テーブル数と各テーブルのレコード数を表示します。
- 各テーブルの合計サイズ、各テーブルの内容のサイズ、各テーブルのインデックスのサイズを表示します。

*データベース統計*
![Database Statistics](macOS/Statistics.png)

**ERダイアグラム**
- フィールドタイプの非表示と表示の切り替えをサポートします。
- 関係推測の有効化をサポート。
- Mermaid markdownとしてのコピーをサポートします。

**データベースの差分**
- データベースを別のデータベースに変換できる SQL テキストの生成をサポートします。
- 2 つのデータベース間の相違点の概要を示すサポート。
![Database Diff](macOS/DatabaseDiff.png)

**リモート接続**
- SQLiteFlow(iOS)がインストールされているiPhoneまたはiPadでオープンリモートSQLiteデータベースをサポートしています。ユースケースの1つは、iPhoneまたはiPadのクエリパフォーマンスの問題をMacから直接デバッグできることです。

*リモート接続*
![Open Remote Database](macOS/RemoteConnect.png)

**データベースのアタッチ**
- 開いているデータベースをコードなしでアタッチします。これは非常に便利な機能で、ATTACH DATABASE コマンドの作成に時間を節約できます。

*開いているデータベースをアタッチする*
![UI - Attach Database](macOS/AttachDatabase.png)

**ドラッグ アンド ドロップ**
- ドラッグアンドドロップしてデータベースとSQLスクリプトを開きます。
- 複数のウィンドウを作成します。

**インサイド エクスプローラー**
- SQLiteデータベースファイル、ジャーナルファイル、WALファイル、WALインデックスファイルのデータ構造を表示します。

*インサイド エクスプローラー*
![Inside Explorer](macOS/InsideExplorer.png)

**データベース ファイル名またはディレクトリの変更を処理する**
- たとえば、これは、SQLiteFlowは、iOSシミュレータでSQLiteデータベースと友好的に動作することができます。

**REGEXP 演算子**
- 環境設定で'REGEXP演算子'が有効になっている場合、ローカルデータベースのREGEXPオペレータをサポートします。

**データベースの暗号化**
- SQLCipher ライブラリによって暗号化された暗号化された SQLite データベースを処理できます。

**アクセスシミュレータ**
- アップルシミュレータへのアクセスをサポートしています。そのため、ユーザーはアプリを開発するときに、アプリのドキュメント ディレクトリをより簡単に開くことができます。

**ショートカット**
- 「クエリの実行」アクションをサポートします。
- 「CSV のインポート」アクションをサポートします。
- 「JSON のインポート」アクションをサポートします。(macOS 14.0以降が必要です。)

**Load Extension**
- SQLite ロード拡張をサポートします。

**LLDB Co-worker**
- sfopenコマンドをサポート。デバッグされたデバイスに元々あった一時ローカルデータベースのコピーを開くことができます。
- sfsaveコマンドをサポート。一時ローカルデータベース(元々sfopenコマンドで作成されたもの)をデバッグされたデバイスにコピーできます。

**言語**
- [English](/) \| [简体中文 (Chinese, Simplified)](/zh-Hans) \| [繁體中文 (Chinese, Traditional)](/zh-Hant) \|日本語 (Japanese)

## サポートまたはお問い合わせ
ご質問や機能のリクエストをお持ちですか? <a href="https://github.com/SQLiteFlow/SQLiteFlow-Issues/issues" target="_blank">問題を作成</a>して自由に感じてください。

