---
layout: default
title: SQLiteFlow
description: SQLiteFlow for iOS release notes.
---

6.5.1 - 2024年10月3日
- バグの修正と安定性の向上。

6.5.0 - 2024年10月2日
- 閲覧。ダウンロードされていないファイルをタップすると、ダウンロードが完了すると、アプリが自動的に開こうとします。
- データエディター。フォントサイズの変更をサポートします。設定-データエディターに移動して変更できます。
- ショートカット。クエリアクションを実行します。クエリが空で、[結果にクエリメッセージを含める] 設定がオンになっていると、クエリ メッセージが結果に含まれない問題を修正しました。
- このバージョンのSQLiteFlowには、iOS 17.0以降が必要です。
- 追加のバグ修正と安定性の改善。

6.4.0 - 2024年07月26日
- クエリエディタは、コンテキストメニューまたは接続された物理キーボード(それぞれホットキーcommand + /、tab、shift + tabを使用)によるコメント、インテントライン、バックインデントラインの切り替えをサポートします。

6.3.9 - 2024年07月10日
- バグの修正と安定性の向上。

6.3.8 - 2024年07月04日
- バグの修正と安定性の向上。

6.3.7 - 2024年05月24日
- バグの修正と安定性の向上。

6.3.6 - 2024年04月30日
- ER図。主キーフィールドにアイコンを追加して、テーブルの主キーを示します。
- ER図。外部キーフィールドにアイコンを追加して、テーブルの外部キーを示します。
- ER図。フィールド名とタイプに異なるテキストスタイルが追加されました。
- ER図。外部キーフィールド、外部キー参照フィールド、またはリレーションパスを選択すると、関連する要素が強調表示されます。
- ER図。テーブルのスキーマ構造を編集するために、テーブルスキーマを開くことをサポートします(テーブル名の横にあるボタンをタップします)。
- ER図。データエディタを開いて(テーブル名を長押しして - 行を選択)、テーブルのデータを編集することができます。
- テーブルスキーマ。式のインデックスの編集をサポートします。
- テーブルスキーマ。部分的なインデックスの編集をサポートします。
- テーブルスキーマ。一部のシナリオでは、alter table SQL プレビューの詳細度を低くする。

6.3.5 - 2024年03月31日
- データベースERダイアグラムの表示をサポートします。メニュー - データベース - ERダイアグラムで表示できます。
- ERダイアグラム。フィールドタイプの非表示と表示の切り替えをサポートします。
- ERダイアグラム。関係推測の有効化をサポート。。この設定が有効な場合、ダイアグラムは、2 つのテーブルが適切なテーブル名とフィールド名を持っている場合、リレーションシップを持つと宣言されていなくても、リレーションシップを持つものとして扱われます。たとえば、Customer テーブルと Invoice テーブル (CustomerID という名前のフィールドを持つ) は、テーブル Invoice に外部キー宣言がない場合でも、リレーションシップを持つものとして扱われます。
- ERダイアグラム。Mermaid markdownとしてのコピーをサポートします。

6.3.4 - 2024年3月21日
- バグの修正と安定性の向上。

6.3.3 - 2024年3月16日
- バグの修正と安定性の向上。

6.3.2 - 2024年3月9日
- バグの修正と安定性の向上。

6.3.1 - 2024年3月7日
- バグの修正と安定性の向上。

6.3.0 - 2024年3月7日
<br/><br/>購入プランを再設計する場合、この更新は既存のユーザーには影響しません。すべてのプランで、ユーザーはアプリのすべての機能を楽しむことができます。
- 2週間のトライアル、無料トライアルはアプリの初回ダウンロード時に自動的に開始され、アプリ内購入は含まれません。無料試用期間が終了すると、アプリはロックされます。
- 従量 制。ユーザーがアプリを楽しむことができる月額サブスクリプション。サブスクリプションの有効期限が切れると、アプリはロックされます。
- 年払いで無制限に。ユーザーがアプリを楽しむことができる年間サブスクリプション。サブスクリプションの有効期限が切れると、アプリはロックされます。
- ライフタイムライセンス。一度購入してください。アプリを所有します。このプランは以前はフルアプリと呼ばれていたため、既存の購入したユーザーはすでにこれを持っているはずです。

6.2.5 - 2024年2月27日
- visionOSに対応しました。
- 追加のバグ修正と安定性の向上。

6.2.2 - 2024年1月15日
- SQLファイルによるデータのインポートをサポートします。
- バグの修正と安定性の向上。

6.2.1 - 2023年11月15日
- 「エクスポート」 で、エクスポート タイプ List を追加します。List 型は、sqlite3 コマンドラインシェルの list 出力モードと同様に動作しますが、BLOB データを空として表示します。「データ エディター」、「クエリ エディター」、および 「クエリ ショートカットの実行」 アクションで使用できます。
- データ エディタ。16バイトのBLOBをUUID文字列として表示することをサポートします。「設定」 - 「データ エディタ」 に移動して有効にすることができます。

6.2.0 - 2023年11月6日
- テーブルへの JSON のインポートをサポートします。
- ショートカット。テーブルへの JSON のインポートをサポートします。iOS 16.4以降が必要です。
- UI の強化。
- ユーザーが「参照」でファイル拡張子を変更できるようにします。

6.1.0 - 2023年10月15日
- 最新バージョンのiOSと互換性のある一連の問題を修正します。
- このバージョンの SQLiteFlow には、iOS 16.1 以降が必要です。

6.0.0 - 2023年4月11日
- データベース差分。 RowID の代わりに主キーを使用して差分とペアリングすることをサポートしており、このオプションはデフォルトで有効になっています。
- ショートカット。 クエリの実行 アクションで、結果からクエリ メッセージを除外するオプションが提供されるようになりました。
- このバージョンの SQLiteFlow には iOS 15.0+ 以降が必要になりました。

5.8.6 - 2022年12月11日
- クエリ エディター。テキストの検索をサポートします。
- 追加のバグ修正と安定性の向上。

5.8.5 - 2022年10月26日
- バグ修正と安定性の向上。

5.8.4 - 2022年10月23日
- バグ修正と安定性の向上。

5.8.3 - 2022年9月20日
- バグ修正と安定性の向上。

5.8.2 - 2022年7月19日
- CSVをートします，ートをサポートする場合の行列の転置。
- CSVをートします，「CSVの最初の行はヘッダーです」が有効で、既存のテーブルにートするように設定されている場合、ヘッダーフィールドの順序がテーブルフィールドの順序と異なる場合は、正しくートできるようになりました。
- CSVをートします，「CSVの最初の行はヘッダーです」が有効で、既存のテーブルにートするように設定されている場合、ヘッダーフィールドがテーブルフィールドのサブセットである場合、データベース制約で許可されている場合、正しくートできるようになりました。

5.8.0 - 2022年6月26日
- バグ修正と安定性の向上。

5.7.2 - 2022年6月11日
- バグ修正と安定性の向上。

5.7.1 - 2022年6月1日
- クエリの編集時にクラッシュする可能性のある問題を修正しました。
- 追加のバグ修正と安定性の向上。

5.7.0 - 2022年5月22日
- データベースの読み込み速度が大幅に向上しました。
- データエディタは、プレビューとしてblobを表示するために画像にブロブを表示するためにアップグレードします。 これにより、ブロブ データは、可能であれば、画像だけでなく、映画、pdf など、その内容に基づいて他の種類のデータも表示できます。
- ビューでフィルターを使用してデータを表示できるデータ エディタ。
- データベースを開くときにテーブルレコード数の表示を有効または無効にすることをサポートします。
- CSVをインポートし、クイックルックによるCSVデータの表示をサポートします。（テスト中に、CSVデータが大きすぎて短時間で表示できない場合、完全なCSVコンテンツではなく簡単なファイル情報として表示されることに注意してください。）

5.3.1 - 2022年3月29日
- バグ修正と安定性の向上。

5.3.0 - 2021年9月29日
- データエディタ、より便利なフィルタ動作。
- クエリ エディターでは、構文の強調表示のカスタマイズをサポートします。
- 追加のバグ修正と安定性の向上。

5.1.2 - 2021年8月18日
- ショートカット，デバイスがロックされているときに「クエリの実行」と「CSV のインポート」を実行して、自動化を目的として便利にします。

5.1.1 - 2021年8月12日
- バグ修正と安定性の向上。

5.1.0 - 2021年8月3日
- UI エンハンスメント。
- クエリ エディターは、Return を入力する際に構文認識インデントをサポートします。
- このバージョンの SQLiteFlow には iOS 14.0+ 以降が必要になりました。
- 追加のバグ修正と安定性の向上。

5.0.5 - 2021年5月21日
- アプリの言語が簡体字中国語に設定されている場合、クエリ エディターの SQL オートコンプリート機能では、Pinyin を使用して特定のテーブル名またはフィールドを検索できるようになりました。

5.0.4 - 2021年5月17日
- コードの自動補完動作の強化。

5.0.3 - 2021年5月16日
- コードの自動補完動作の強化。

5.0.2 - 2021年5月11日
- コードの自動補完動作の強化。
- 追加のバグ修正と安定性の向上。

4.8.4 - 2021年4月12日
- ショートカット。インテントを実行すると、SQLiteFlow は実際にジョブを実行する前にオフロードされるデータベースファイル、CSV ファイルなどの必要なファイルのダウンロードを試みます。

4.8.3 - 2021年3月14日
- テーブルを insert ステートメントにエクスポートするときに、列名が適切にエスケープされない問題を修正します。

4.8.2 - 2021年1月10日
- 日本語のサポート。

4.8.1 - Dec 15, 2020
- Bug fixes and stability improvements.

4.8.0 - Dec 14, 2020
- Data Editor, supports export data as insert/update statement.
- Supports dump database to a SQL file.
- Additional bug fixes and stability improvements.

4.6.2 - Nov 30, 2020
- Bug fixes and stability improvements.

4.6.1 - Nov 23, 2020
- Import CSV, now the default value of the option "First Line in CSV is Header" is "on", to make it consistent with the Export CSV feature.
- Import CSV, now supports truncate a table before importing.
- Add Shortcuts support. Now "Run Query" and "Import CSV" are available in the Shortcuts app. This feature requires iOS 14.0 or later.

4.6.0 - Sep 18, 2020
- Supports export data as JSON.
- Supports export data as Markdown.
- This version of SQLiteFlow now requires iOS 13 or later.

4.3.6 - Sep 7, 2020
- Bug fixes and stability improvements.

4.3.5 - Aug 6, 2020
- Data Editor, supports keyboard arrow keys to move selection between cells. Requires iOS 13.4 or iPadOS 13.4.
- Supports recognize SQLite databases with custom extensions if they can appear in Browse.

4.3.4 - Jul 8, 2020
- Filter in Data Editor now supports "!=" and "not contains" operator.

4.3.3 - Jul 3, 2020
- Supports rename table in Table List.
- Supports pick a journal mode (WAL or DELETE) when creating a database.
- Table Schema, supports reorder columns using drag and drop. 
- Table Schema, add support for setting a table to WITHOUT ROWID table.

4.3.2 - Jun 19, 2020
- Bug fixes and stability improvements.

4.3.1 - Jun 9, 2020
- Bug fixes and stability improvements.

4.3.0 - Jun 8, 2020
- Format Query, allow user choose the prefer indent using Spaces or Tabs.
- Format Query, allow user to set indent width. Now the default indent width is 4 to match the default Tab Width which is also 4. The default indent width is 3 in previous versions when the value is not customizable.
- Format Query, allow user to set comma that split column definition style to leading or trailing.
- Text Editing, allow user to set tab width. The default tab width is 4.
- Text Editing, allow user to set the behavior of the Tab key to inserts tab character or inserts spaces.
- The setting ‘Enable Foreign Key Constraints’ now move from Data Editor to Settings - General, so now this setting will affects to Data Editor, Query Editor and Import CSV.
- Import CSV now supports use semicolon(;) as delimiter to import data.

4.2.0 - Apr 28, 2020
- Alter Table now supports show the SQL that altering the table.
- Improve the user experience of Alter Table.
- Improve the inputing experience in Query Editor when a hardware keyboard connected to device. Requires iOS 13.4 or iPadOS 13.4.
- Merge Query Editor and Query Result to same page.
- Additional bug fixes and stability improvements.

4.1.1 - Mar 28, 2020
- Bug fixes and stability improvements.

4.1.0 - Mar 26, 2020
- Supports multiple cells/rows/columns selection in Data Editor & Query Results.
- Supports run selected query in Query Editor.
- Fix an issue that may cause mark external file to Recents list failed.
- Additional bug fixes and stability improvements.

4.0.0 - Jan 1, 2020
- Database List now rename to Browse. 
- Supports open/create local folders, SQLite databases, SQL files, CSV files in Browse.
- Supports open Filter files in Browse.
- Supports open external SQL files, CSV files and Filter files in Browse.
- Supports open external folders in Browse. Requires iOS 13.0 or iPadOS 13.0.
- Supports show recents files.
- Supports show blob data as hex in Query Result.
- Supports long press to show context menu preview for a record in Data Editor and Query Results. Requires iOS 13.0 or iPadOS 13.0.
- Add the ability to enable foreign key constraints in Data Editor.
- Add 'Done' button at the top of screen when editing in Data Editor to trigger saving data.
- Supports copy a row in Data Editor and Query Result.
- Now, filter in Data Editor is file based. 
- Supports tap filter button to open or create a filter file in Data Editor.
- After opened a filter file, users can edit and apply a filter to Data Editor.
- After applied a filter in Data Editor, tap filter button, users can choose 'Edit Filter', 'Remove Filter' or 'Choose Another Filter'.
- Fix an issue that may cause unreadable code imported to table when import CSV data from a file.
- Fix an issue that cause can't copy data record in Query Result.
- Additional bug fixes and stability improvements.

3.9.3 - Sep 30, 2019
- Fix an issue that cause unwanted quotes translation after formatting a query in Query Editor.

3.9.2 - Sep 28, 2019
- Fix an issue that could lead the share sheet in Database List show empty.

3.9.1 - Sep 26, 2019
- Supports multiple windows for iPadOS 13.

3.9.0 - Sep 20, 2019
- Supports dark mode for iOS 13.
- Remove the global editing text field in Data Editor, so now you can edit data directly in the data field cell.

3.8.0 - Aug 23, 2019
- Syntax Highlighting & Format Query need to support UPSERT clause and window function for compatible with the future version of iOS.
- Fix an inputing issue when use Pinyin keyboard.
- Additional bug fixes and stability improvements.

3.7.0 - Jul 2, 2019
- Support for Chinese (Simplified), Chinese (Traditional).
- Additional bug fixes and stability improvements.

3.6.0 - Jun 20, 2019
- Hex Editor now supports save blob data to a file.
- Hex Editor now supports drag and drop to import data from another app like Files.
- Hex Editor now supports drag and drop an image to export it to another app like Files.

3.5.0 - Jun 19, 2019
- Supports edit blob as hex.
- Supports show blob as image if possible.
- Supports IS NULL and IS NOT NULL filter in Data Editor
- Supports create sample database.
- Fix an issue that cause load database failed when a database contains virtual table that use an unknown module.

3.4.0 - May 8, 2019
- Supports export table/view data and query result to CSV format.

3.3.0 - Apr 19, 2019
- Supports import CSV data.

3.2.0 - Apr 12, 2019
- [Data Viewer] Supports sort records by tap on column title.
- [Database Statistics] Supports show records count of each table.
- [Database Statistics] Supports show total size of each table
- [Database Statistics] Supports show size of each table's content.
- [Database Statistics] Supports show size of each table's indexes. 
<br/> The feature Database Statistics may help you get more insight about your SQLite databases' data storage information, which may let you see if there're any chances to let SQLite working in a more effective way in your device.
- [Database Diff] Supports generate SQL text that can let you transform a database into another.
- [Database Diff] Supports show a summary of the differences between two databases.

3.1.0 - Apr 4, 2019
- Supports drag and drop to import or export SQLite databases and SQL files.
- Supports use a document picker to import SQLite databases and SQL files.
- Additional bug fixes and stability improvements.

3.0.3 - Mar 21, 2019
- Fix an issue that may cause 'Copy to SQLiteFlow' from Files app have no response.

3.0.2 - Mar 7, 2019
- Fix an issue that may cause duplicate purchase.

3.0.1 - Mar 7, 2019
- Fix an issue that cause loading spinner still shown when Restore Previous Purchase finished.

3.0.0 - Mar 6, 2019
- We offer 2 weeks of free trial now, feel free to come on in and take a try.

2.0.0 - Feb 11, 2019
- Start with version 2.0.0, to execute queries, creating or choosing an SQL file is needed. 
- Supports save queries.
- Supports long press a file item to rename a file.
- Supports long press a file item to duplicate a file.
- Additional bug fixes and stability improvements.

1.3.7 - Jan 11, 2019
- Supports work with SQLiteFlow(macOS) to handle remote import CSV file.

1.3.6 - Nov 7, 2018
- Supports work with SQLiteFlow(macOS) to handle remote database diff.
- Additional bug fixes and stability improvements.

1.3.5 - Sep 27, 2018
- Fix an issue that causes syntax highlighting incorrect when typing block style comment.
- Fix an issue that causes load database library failed when there's another app that declares it owns SQLite database file type.
- Additional bug fixes and stability improvements.

1.3.4 - Aug 22, 2018
- [Alter Table] Fix an issue that causes incorrect input behavior when using Pinyin keyboard.
- [Alter Table] When there's only one field in a table, disable 'Delete' field option, since SQLite does not allow a table has no field.

1.3.3 - Aug 10, 2018
- In table list, each table's row counts supports display in decimal style.

1.3.2 - Aug 9, 2018
- Table list supports display each table's row counts.

1.3.1 - Aug 2, 2018
- Fix an issue that cause unnecessary error 'The folder doesn't exist' appear.
- Fix an issue that cause back button not enabled when go into a folder.

1.3.0 - Jul 28, 2018
- Add 'About'. This feature can let you contact us conveniently.

1.2.1 - Jul 21, 2018
- Database list now supports display folder.

1.1.0 - Jul 4, 2018
- Initial public release.

[Home](/iOS)
