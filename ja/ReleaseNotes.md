---
layout: default
title: SQLiteFlow
description: SQLiteFlow for Mac release notes.
---

6.5.1 - 2024年10月23日
- クエリエディター。現在、一部のデータベース関連 UI は、データベース スキーマを変更する可能性のあるクエリを実行した後、自動的に更新されます。
- SQLite version 3.47.0 (2024-10-21) をサポートします。
- 追加のバグ修正と安定性の改善。

6.5.0 - 2024年10月2日
- クエリエディター。クエリプランの説明と説明は、ユーザー選択テキストを尊重するようになりました。
- テーブルを変更します。ポップアップメニュー項目から項目を選択しても、インデックス列の編集が効果がない可能性がある問題を修正しました。
- 購入プラン。アプリの起動時に購入プランページが予期せず表示される可能性がある問題を修正します。
- エクスプローラーの内部。データベースファイルを開くと、一時データベースジャーナルファイルが自動的にメインファイルにフラッシュされなくなります。
- エクスプローラーの内部。アプリのクラッシュを引き起こす可能性のある問題を修正します。
- ショートカット。クエリアクションを実行します。クエリが空で、[結果にクエリメッセージを含める] 設定がオンになっていると、クエリ メッセージが結果に含まれない問題を修正しました。
- 追加のバグ修正と安定性の改善。

6.4.2 - 2024年9月13日
- バグ修正と安定性の向上。

6.4.1 - 2024年9月13日
- データエディタは、フィルタファイルとしての読み込みと保存をサポートします。
- データエディタは、列の表示設定の変更をサポートします。macOS 14.0 以降が必要です。
- ALTER View は、CREATE VIEW ステートメントの前に DROP VIEW ステートメントを付加して、ビューの変更をより便利にします。
- データベースリスト、データベースの場所のトグルをサポートします。現在、デフォルト値はオフに設定されていますが、ローカルデータベース名を右クリックして[データベースの場所を表示]でオンにすることができます。アプリにシミュレーターのアクセス許可がある場合、シミュレーター フォルダー上のデータベースには、ファイル パスではなくシミュレーターの相対位置情報が表示されることがあります。
- SQLCipher ライブラリをバージョン 4.6.1 に更新します。

6.4.0 - 2024年8月13日
- SQLite version 3.46.1 (2024-08-13) をサポート。

6.3.9 - 2024年7月8日
- バグ修正と安定性の向上。

6.3.8 - 2024年5月24日
- SQLite version 3.46.0 (2024-05-23) をサポート。
- 追加のバグ修正と安定性の向上。

6.3.7 - 2024年4月30日
- データベースリストは、外部キーフィールドアイコンの表示をサポートします。
- SQLite Version 3.45.3 (2024-04-15) をサポート。
- SQLCipher ライブラリをバージョン 4.5.7 に更新します。

6.3.6 - 2024年4月15日
- ER図。主キーフィールドにアイコンを追加して、テーブルの主キーを示します。
- ER図。外部キーフィールドにアイコンを追加して、テーブルの外部キーを示します。
- ER図。フィールド名とタイプに異なるテキストスタイルが追加されました。
- ER図。外部キーフィールド、外部キー参照フィールド、またはリレーションパスを選択すると、関連する要素が強調表示されます。
- ER図。テーブルのスキーマ構造を編集するために、テーブルスキーマを開くことをサポートします(テーブル名の横にあるボタンをクリックします)。
- ER図。データエディタを開いて(テーブル名を右クリックして - 行を選択)、テーブルのデータを編集することができます。
- テーブルスキーマ。式のインデックスの編集をサポートします。
- テーブルスキーマ。部分的なインデックスの編集をサポートします。
- テーブルスキーマ。一部のシナリオでは、alter table SQL プレビューの詳細度を下げます。

6.3.3 - 2024年3月31日
- データベースERダイアグラムの表示をサポートします。メニュー - データベース - ERダイアグラムで表示できます。
- ERダイアグラム。フィールドタイプの非表示と表示の切り替えをサポートします。
- ERダイアグラム。関係推測の有効化をサポート。。この設定が有効な場合、ダイアグラムは、2 つのテーブルが適切なテーブル名とフィールド名を持っている場合、リレーションシップを持つと宣言されていなくても、リレーションシップを持つものとして扱われます。たとえば、Customer テーブルと Invoice テーブル (CustomerID という名前のフィールドを持つ) は、テーブル Invoice に外部キー宣言がない場合でも、リレーションシップを持つものとして扱われます。
- ERダイアグラム。Mermaid markdownとしてのコピーをサポートします。
- アクセスシミュレータは、存在する場合は、アプリグループのコンテナフォルダを開くことをサポートします。

6.3.2 - 2024年3月21日
- バグ修正と安定性の向上。

6.3.1 - 2024年3月18日
- SQLite version 3.45.2 (2024-03-12) をサポート。

6.3.0 - 2024年3月10日
<br/><br/>購入プランを再設計する場合、この更新は既存のユーザーには影響しません。すべてのプランで、ユーザーはアプリのすべての機能を楽しむことができます。このバージョンの SQLiteFlow には、macOS 13.0 以降が必要です。
- 2週間のトライアル、無料トライアルはアプリの初回ダウンロード時に自動的に開始され、アプリ内購入は含まれません。無料試用期間が終了すると、アプリはロックされます。
- 従量 制。ユーザーがアプリを楽しむことができる月額サブスクリプション。サブスクリプションの有効期限が切れると、アプリはロックされます。
- 年払いで無制限に。ユーザーがアプリを楽しむことができる年間サブスクリプション。サブスクリプションの有効期限が切れると、アプリはロックされます。
- ライフタイムライセンス。一度購入してください。アプリを所有します。このプランは以前はフルアプリと呼ばれていたため、既存の購入したユーザーはすでにこれを持っているはずです。

6.2.6 - 2024年1月31日
- SQLite Version 3.45.1 (2024-01-30) をサポート。

6.2.5 - 2024年1月20日
- バージョン 4.5.6 に SQLCipher ライブラリを更新します。

6.2.4 - 2024年1月16日
- JSONB Editor、データエディタとクエリ結果でJSONBをJSONとして表示することをサポート
- JSONB エディターは、データ エディターで JSON として JSONB を編集できます。
- Hex Editorは、Hex値をCコードとしてコピーすることをサポートします。
- SQLファイルによるデータのインポートをサポートします。
- SQLite Version 3.45.0 (2024-01-15) をサポート。
- バグの修正と安定性の向上。

6.2.3 - 2023年11月29日
- SQLite Version 3.44.2 (2023-11-24) をサポート。

6.2.2 - 2023年11月22日
- SQLite Version 3.44.1 (2023-11-22) をサポート。

6.2.1 - 2023年11月15日
- [エクスポート] で、エクスポート タイプ List を追加します。List 型は、sqlite3 コマンドラインシェルの list 出力モードと同様に動作しますが、BLOB データを空として表示します。[データ エディター]、[クエリ エディター]、および [クエリ ショートカットの実行] アクションで使用できます。

6.2.0 - 2023年11月4日
- Version 3.44.0 (2023-11-01) をサポート。
- テーブルへの JSON のインポートをサポートします。
- ショートカット。テーブルへの JSON のインポートをサポートします。(JSONファイルからインポートする場合、ショートカットアプリのバグにより、ファイルに「.json」ファイル拡張子を付けることはできません)。macOS 14.0以降が必要です。
- テーブルスキーマ、データエディタ、統計、フォントと色の設定、ロード拡張設定。「+」ボタンにホットキー⇧⌘Nを付けます。「-」ボタンにホットキー⌫(削除)を与えます。
- データベースリスト。⌥-テーブル名/ビュー名をダブルクリックするか、⌥-テーブル名/ビュー名を返すことで、テーブルスキーマ/ビューの変更ページを開くことができます。
- アクセスシミュレーター。一部のシミュレーターが表示されない可能性がある問題を修正します。
- このアップデートにより、互換性の問題によりツールバーの設定がリセットされる場合があります。
- このバージョンの SQLiteFlow には、macOS 12.0 以降が必要です。

6.1.0 - 2023年10月15日
- SQLite Version 3.43.2 (2023-10-10) をサポート。

6.0.9 - 2023年10月7日
- バグ修正と安定性の向上。

6.0.8 - 2023年9月28日
- バグ修正と安定性の向上。

6.0.7 - 2023年9月17日
- 開いているデータベースをアプリの起動間で保持することをサポートします。[設定]-[一般]に移動して有効にすることができます。
- 追加のバグ修正と安定性の向上。

6.0.6 - 2023年9月12日
- SQLite Version 3.43.1 (2023-09-11) をサポート。
- バージョン 4.5.5 に SQLCipher ライブラリを更新します。

6.0.5 - 2023年8月25日
- SQLite Version 3.43.0 (2023-08-24) をサポート。
- 追加のバグ修正と安定性の向上。

6.0.4 - 2023年8月21日
- SQLite ロード拡張をサポートします。

6.0.3 - 2023年5月17日
- SQLite Version 3.42.0 (2023-05-16) をサポート。
- バージョン 4.5.4 に SQLCipher ライブラリを更新します。

6.0.2 - 2023年4月11日
- データベース差分。 RowID の代わりに主キーを使用して差分とペアリングすることをサポートしており、このオプションはデフォルトで有効になっています。
- ショートカット。 クエリの実行 アクションで、結果からクエリ メッセージを除外するオプションが提供されるようになりました。

6.0.1 - 2023年3月22日
- SQLite version 3.41.2 (2022-03-22) をサポート。

6.0.0 - 2023年3月6日
- バグ修正と安定性の向上。

5.9.9 - 2023年3月2日
- クエリエディタは、クエリを実行するデータベースの選択をサポートします。

5.9.8 - 2023年2月25日
- クエリ エディター。複数行が選択されている場合に、Tab キーを押して複数行のインデントを挿入できます。
- クエリ エディター。Shift-Tabキーを押して、選択した行のインデントを削除することをサポートします。
- SQLite version 3.41.0 (2023-02-21) をサポート。

5.9.6 - 2023年2月14日
- LLDB Co-worker。sfopenコマンドをサポート。デバッグされたデバイスに元々あった一時ローカルデータベースのコピーを開くことができます。
- LLDB Co-worker。sfsaveコマンドをサポート。一時ローカルデータベース(元々sfopenコマンドで作成されたもの)をデバッグされたデバイスにコピーできます。
設定-「LLDB Co-worker」に移動して、設定方法を確認します。

5.9.3 - 2023年1月28日
- バグ修正と安定性の向上。

5.9.2 - 2023年1月26日
- データ エディタ。16バイトのBLOBをUUID文字列として表示することをサポートします。[設定] - [データ エディタ] に移動して有効にすることができます。

5.9.1 - 2023年1月9日
- SQLite version 3.40.1 (2022-12-28) をサポート。
- 追加のバグ修正と安定性の向上。

5.9.0 - 2022年12月26日
- バージョン 4.5.3 に SQLCipher ライブラリを更新します。
- このバージョンの SQLiteFlow には、macOS 11.0 以降が必要です。
- 追加のバグ修正と安定性の向上。

5.8.6 - 2022年12月1日
- タブバーのタイトルの機能強化。
- 一部のホットキーに不要な追加のShift修飾子が必要になる可能性があるホットキーの問題を修正します。
- SQLite version 3.40.0 (2022-11-16) をサポート。
- 追加のバグ修正と安定性の向上。

5.8.5 - 2022年10月2日
- SQLite バージョン 3.39.4 (2022-09-29) をサポート。

5.8.4 - 2022年9月28日
- SQLite バージョン 3.39.3 (2022-09-05) をサポート。

5.8.3 - 2022年8月12日
- SQLite バージョン 3.39.2 (2022-07-21) をサポート。
- バージョン 4.5.2 に SQLCipher ライブラリを更新します。

5.8.2 - 2022年7月19日
- CSVをートします，ートをサポートする場合の行列の転置。
- CSVをートします，「CSVの最初の行はヘッダーです」が有効で、既存のテーブルにートするように設定されている場合、ヘッダーフィールドの順序がテーブルフィールドの順序と異なる場合は、正しくートできるようになりました。
- CSVをートします，「CSVの最初の行はヘッダーです」が有効で、既存のテーブルにートするように設定されている場合、ヘッダーフィールドがテーブルフィールドのサブセットである場合、データベース制約で許可されている場合、正しくートできるようになりました。

5.8.1 - 2022年6月26日
- シンプルで便利なユーティリティJSONフォーマッタを夏の贈り物として追加してください。これはこのユーティリティの初期バージョンであり、「メインメニュー - ツール」または「ツールバーのカスタマイズ」からアクセスできます。ご質問やアドバイスがございましたら、お問い合わせください。
- SQLite バージョン 3.39.0 (2022-06-25) をサポート。

5.7.4 - 2022年6月11日
- バグ修正と安定性の向上。

5.7.3 - 2022年6月10日
- バグ修正と安定性の向上。

5.7.2 - 2022年6月2日
- クエリの編集時にクラッシュする可能性のある問題を修正しました。
- 追加のバグ修正と安定性の向上。

5.7.1 - 2022年05月21日
- UI を使用して新しいテーブルを作成するときにクラッシュする問題を修正しました。

5.7.0 - 2022年05月16日
- データベースの読み込み速度が大幅に向上しました。
- データエディタは、プレビューとしてblobを表示するために画像にブロブを表示するためにアップグレードします。 これにより、ブロブ データは、可能であれば、画像だけでなく、映画、pdf など、その内容に基づいて他の種類のデータも表示できます。
- ビューでフィルターを使用してデータを表示できるデータ エディタ。

5.6.9 - 2022年05月07日
- SQLite バージョン 3.38.5 (2022-05-06) をサポート。

5.6.8 - 2022年04月28日
- SQLite バージョン 3.38.3 (2022-04-27) をサポート。
- バージョン 4.5.1 に SQLCipher ライブラリを更新します。

5.6.7 - 2022年03月26日
- SQLite バージョン 3.38.2 (2022-03-26) をサポート。

5.6.6 - 2022年03月24日
- バグ修正と安定性の向上。

5.6.5 - 2022年03月13日
- SQLite バージョン 3.38.1 (2022-03-12) をサポート。

5.6.4 - 2022年02月27日
- SQLite バージョン 3.38.0 (2022-02-22) をサポート。

5.6.3 - 2022年01月12日
- バグ修正と安定性の向上。

5.6.2 - 2022年01月06日
- SQLite バージョン 3.37.2 (2022-01-06) をサポート。

5.6.1 - 2022年01月05日
- SQLite バージョン 3.37.1 (2021-12-30) をサポート。

5.6.0 - 2021年11月29日
- SQLite バージョン 3.37.0 (2021-11-27) をサポート。

5.5.0 - 2021年11月26日
- ショートカットの追加のサポート今すぐ「クエリを実行」と「CSV のインポート」は、ショートカット アプリで利用できます。
- 追加のバグ修正と安定性の向上。

5.4.0 - 2021年11月12日
- バージョン 4.5.0 に SQLCipher ライブラリを更新します。
- このバージョンの SQLiteFlow には、macOS 10.15 以降が必要です。
- 追加のバグ修正と安定性の向上。

5.3.0 - 2021年9月20日
- データベースリストは、テーブルのみでフィルタアイテムをサポートするか、テーブルフィールドのみでアイテムをフィルタします。
- データベースリストは、テーブルフィールドの名前を変更するには、フィールド名を右クリックをサポートしています。(SQLite 3.25.0 以降が必要です)。
- データエディタで、テキストセルのコンテキストメニューに「テキストとして編集」を追加し、ユーザーがポップオーバーテキストエディタを表示してセルのコンテンツをテキストとして編集できるようにします。
- エクスポートは、エクスポート結果をクリップボードに直接コピーすることをサポートしています。
- ユーザーがウィンドウ タブを選択すると、データベース リストで選択した項目が、タブのコンテンツに基づいて同期されます (必要に応じて)。
- アップルシミュレータへのアクセスをサポートしています。そのため、ユーザーはアプリを開発するときに、アプリのドキュメント ディレクトリをより簡単に開くことができます。

5.2.4 - 2021年8月23日
- バグ修正と安定性の向上。

5.2.3 - 2021年8月23日
- バグ修正と安定性の向上。

5.2.2 - 2021年8月12日
- 表示テーブルとビューの数は、データベースリストでサポートされています。

5.2.0 - 2021年6月21日
- クエリ エディターは、Return を入力する際に構文認識インデントをサポートします。
- 追加のバグ修正と安定性の向上。

5.1.0 - 2021年6月6日
- データベースリストのテーブルフィールド情報を表示できます。現在、情報にはフィールド名、フィールドタイプ、NULL 制約、および主キー制約が含まれています。
- 手動で特定の明暗の外観をサポートしています。

5.0.8 - 2021年6月21日
- SQLite バージョン 3.36.0 (2021-06-18) をサポート。

5.0.6 - 2021年5月24日
- バグ修正と安定性の向上。

5.0.5 - 2021年5月21日
- アプリの言語が簡体字中国語に設定されている場合、クエリ エディターの SQL オートコンプリート機能では、Pinyin を使用して特定のテーブル名またはフィールドを検索できるようになりました。

5.0.4 - 2021年5月17日
- コードの自動補完動作の強化。

5.0.3 - 2021年5月16日
- コードの自動補完動作の強化。

5.0.2 - 2021年5月11日
- コードの自動補完動作の強化。
- 追加のバグ修正と安定性の向上。

5.0.1 - 2021年5月6日
- バグ修正と安定性の向上。

5.0.0 - 2021年5月4日
- データエディタのフィルタ機能に演算子「SQL」を追加します。
- SQLCipher ライブラリによって暗号化された暗号化された SQLite データベースを処理できます。
- 追加のバグ修正と安定性の向上。

4.9.2 - 2021年4月20日
- バグ修正と安定性の向上。

4.9.1 - 2021年4月20日
- SQLite バージョン 3.35.5 (2021-04-19) をサポート。

4.9.0 - 2021年3月28日
- SQLite バージョン 3.35.3 (2021-03-26) をサポート。
- クエリエディタは、ユーザーが選択した文字列が接頭辞"SELECT"を持っている場合は、右クリックメニューからビューを作成をサポートしています。
- データエディタは、データエディタにフローティング行ヘッダーを追加し、それは行を選択するためのより多くの方法で提供し、ユーザーが編集をトリガすることなく行を選択することができます。

4.8.4 - 2021年3月14日
- SQLite バージョン 3.35.0 (2021-03-12) をサポート。
- テーブルを insert ステートメントにエクスポートするときに、列名が適切にエスケープされない問題を修正します。

4.8.3 - 2021年1月24日
- SQLite バージョン 3.34.1 (2021-01-20) をサポート。

4.8.2 - 2021年1月10日
- 日本語のサポート。

4.8.1 - Dec 13, 2020
- Supports full-height sidebar in macOS 11.
- Additional bug fixes and stability improvements.

4.8.0 - Dec 11, 2020
- Add supports for Apple Silicon Mac.
- Data Editor, supports copy data as insert/update statement.
- Supports dump database to a SQL file.
- Supports SQLite version 3.34.0 (2020-12-01).
- Fix an issue that may cause user SQL file move to app's temp query session folder after a crash happen.
- Additional bug fixes and stability improvements.

4.7.0 - Nov 4, 2020
- Significant performance improvement to Data Editor and Query Results when there are large numbers (like hundreds) of columns exist.
- This version of SQLiteFlow requires macOS 10.14 or later.
- Additional bug fixes and stability improvements.

4.6.1 - Sep 15, 2020
- Fix an issue that may cause UI glitch when in full screen mode.
- Additional bug fixes and stability improvements.

4.6.0 - Sep 8, 2020
- Supports export data as JSON.
- Supports export data as Markdown.

4.5.1 - Aug 29, 2020
- Bug fixes and stability improvements.

4.5.0 - Aug 28, 2020
- Tabbing behavior changes. Previously, close a window means hide the window, and all tabs in this window still remain opened. Now, close a window means close all tabs in this window and close the window.
- Now SQLiteFlow use the system tab bar instead of the previous custom one to get the most out of system offered features.
- Supports customize toolbar and new toolbar icons.
- Query Editor's auto save feature has been improved.
- Supports SQLite version 3.33.0 (2020-08-14).
- Additional bug fixes and stability improvements.

4.3.1 - Jul 8, 2020
- Filter in Data Editor now supports "!=" and "not contains" operator.

4.3.0 - Jul 3, 2020
- Supports pick a journal mode when creating a database.
- Table Schema, supports reorder columns using drag and drop. 
- Table Schema, add support for setting a table to WITHOUT ROWID table.
- Supports export data through table/view's context menu in Database List.
- Add more Touch Bar supports.
- Additional bug fixes and stability improvements.

4.2.0 - Jun 28, 2020
- Add some basic Touch Bar supports.

4.1.1 - Jun 22, 2020
- Supports SQLite version 3.32.3 (2020-06-18).
- Additional bug fixes and stability improvements.

4.1.0 - Jun 19, 2020
- Allow user to choose the macOS embedded SQLite library or the latest SQLite library (currently SQLite 3.32.2) to work with.
- Additional bug fixes and stability improvements.

4.0.1 - May 25, 2020
- Add an option 'Allow select all file types' to Open Database panel to allow user opening database files with arbitrary extensions from the Open Database panel.
- Fix an issue that cause the value of 'Enable Foreign Key Constraints' and 'Tab Key Behavior' not display correctly in Preference.

4.0.0 - May 22, 2020
- Database List, supports right click a table name to rename a table.
- Format Query, allow user choose the prefer indent using Spaces or Tabs.
- Format Query, allow user to set indent width. Now the default indent width is 4 to match the default Tab Width which is also 4. The default indent width is 3 in previous versions when the value is not customizable.
- Format Query, allow user to set comma that split column definition style to leading or trailing.
- Text Editing, allow user to set tab width. The default tab width is 4.
- Text Editing, allow user to set the behavior of the Tab key to inserts tab character or inserts spaces.
- The setting 'Enable Foreign Key Constraints' now move from Data Editor to Preference - General, so now this setting will affects to Data Editor, Query Editor and Import CSV.
- Enhancement for Alter Table.
- Import/Export CSV now supports use semicolon(;) or tab as delimiter to import/export data.
- Import CSV, fix an issue that cause last row is not imported when the CSV text's last field on the last record is not populated.
- Additional bug fixes and stability improvements.

3.8.1 - Aug 22, 2019
- Change 'Set NULL' to 'Set NULL & Apply' in Hex Editor.
- Syntax Highlighting & Format Query now supports UPSERT clause and window function for compatible with the future version of macOS.
- Additional bug fixes and stability improvements.

3.8.0 - Aug 16, 2019
- Inside Explorer. Show inside data structure of SQLite database file, journal file, WAL file or WAL-Index file.
- Now when editing data in Data Editor, you can tap Tab key to switch column.
- Now when editing data in Data Editor, you can tap ESC key can undo changes in the editing field.
- Now when editing data in Data Editor, you can tap Enter key to finish editing data, then tap Enter key again can trigger saving the edited data to database.
- Add an extra column at the left edge of Data Editor for helping you select rows easily.
- Copy data as CSV in Data Editor and Query Result now will respect column order shows in UI.
- Add 'Export' button in Data Editor. So you can choose 'Selected Rows', 'Displaying Rows' or 'Whole Table' with/without 'Include Header' to export data from a table/view to a CSV file.
- Add 'Export' button in Query Result. So you can choose 'Selected Rows' or 'Displaying Rows' with/without 'Include Header' to export data from query result or query message to a CSV file.
- Refresh database in Database List now can trigger opened tabs be refreshed too.

3.7.0 - Jun 23, 2019
- Support for Chinese (Simplified), Chinese (Traditional).
- Additional bug fixes and stability improvements.

3.6.2 - Jun 23, 2019
- Fix an issue that if a database file has .sql file extension, it be recognized as a malformed sql script file instead of a database file.

3.6.1 - Jun 20, 2019
- Supports save blob data to a file.
- Supports create sample database.
- Additional bug fixes and stability improvements.

3.6.0 - May 30, 2019
- Supports IS NULL and IS NOT NULL filter in Data Editor
- Supports automatically reload a row from database if one of the row's field be updated in Data Editor in Data Editor.
- Supports edit blob as hex.
- Supports display blob as image if blob data is an image.
- Fix an issue that may cause auto adjust column width for query results Message tab's sql column sometimes shorter than expected.
- Fix an issue that cause load database failed when a database contains virtual table that use an unknown module.

3.5.6 - May 23, 2019
- Fix an issue that cause 'Set NULL' when editing data takes no effect.

3.5.5 - May 10, 2019
- Additional bug fixes and stability improvements.

3.5.4 - May 1, 2019
- Performance improvements for format query.
- Performance improvements for syntax highlighting.
- Fix an issue that may cause click to open files from Finder may have no effect.
- Additional bug fixes and stability improvements.

3.5.3 - Apr 27, 2019
- Fix an issue that cause sorting by clicking on column in Data Viewer not working.
- Improvements in Dark Mode.
- Let the free trial feature's description more clearer.

3.5.2 - Apr 26, 2019
- Fix an issue that may cause Data Viewer showing empty records.

3.5.1 - Apr 25, 2019
- Fix an issue that may cause paid users see getting trial or getting full unlock screen.

3.5.0 - Apr 24, 2019
- We offer 2 weeks of free trial now, feel free to come on in and take a try.

3.3.1 - Mar 6, 2019
- Add shortcut Cmd + Shift + R to 'Run selected query'.
- Additional bug fixes and stability improvements.

3.3.0 - Jan 28, 2019
- Supports 'Show Previous Tab (Ctrl+Shift+Tab)'
- Supports 'Show Next Tab (Ctrl+Tab)'
- Supports 'Merge Tabs of This Database into New Window'
- Supports 'Move Tabs to Main Window'
- Supports 'Exchange Tabs with Main Window Tabs'
- Fix an issue that cause window size not remembered.
- Fix an issue that cause open FTS table failed.

3.2.0 - Jan 18, 2019
- Supports filter tables and views in database list.
- Additional bug fixes and stability improvements.

3.1.0 - Jan 11, 2019
- Supports sorting by click on column in Data Viewer.
- Supports import CSV data.
- Additional bug fixes and stability improvements.

3.0.2 - Dec 19, 2018
- Additional bug fixes and stability improvements.

3.0.1 - Dec 13, 2018
- Supports REGEXP operator for local SQLite databases when running query. Go Preferences - General - 'REGEXP operator' to enable or disable it.
- Data Viewer Filter also supports REGEXP if 'REGEXP operator' is enabled in Preferences.

3.0.0 - Dec 9, 2018
- Supports multiple windows.
- Supports Cmd + W to close selected tab.
- Additional bug fixes and stability improvements.

2.2.1 - Nov 12, 2018
- Display two groups in Paste Recent menu: Recent Files group and Recent Temporary Sessions group.
- Additional bug fixes and stability improvements.

2.2.0 - Nov 8, 2018
- [Database Diff] Supports generate SQL text that can let you transform a database into another.
- [Database Diff] Supports show only a summary of the differences between two databases.
- [Query Editor] Supports paste recent query sessions.
- [Query Editor] Supports save the query to a file.
- [Query Editor] Supports load the query from a file.

2.1.0 - Sep 26, 2018
- Supports Dark Mode for macOS Mojave.
- Supports customize syntax highlighting. 
- Add two default themes which are Light and Dark.
- In Query Editor, Use Cmd+ to make the font bigger, Cmd- to make the font smaller.
- Format Query, Toggle Comments, Toggle Wrap Lines have been moved to Editor menu.
- Fix an issue that causes syntax highlighting incorrect when typing block style comment.

2.0.1 - Sep 5, 2018
- [Database Statistics] Display table counts and each table's record count.
- [Database Statistics] Display each table's storage consumed and storage consumed detail, including table data storage consumed and indexes storage consumed. [* Available on macOS 10.13+]
- [Query Editor] Supports wrap lines. To toggle it on or off, go to Menu - Edit - Structure - Toggle Wrap Lines, or use shortcut Option + Cmd + L.
- [Query Editor] Improved SQL auto-completion.
- [Query Editor] Improved context menu.
- [Query Editor] Improved line number.

1.3.3 - Aug 10, 2018
- Additional bug fixes and stability improvements.

1.3.2 - Aug 10, 2018
- [Database Statistics] Supports adjust each column's width based on its content automatically.
- [Database Statistics] Display 'Records' in decimal style.

1.3.1 - Aug 8, 2018
- Supports show database statistics. For now, the statistics include each table's name and record count.

1.3.0 - Jul 29, 2018
- Additional bug fixes and stability improvements.

1.2.1 - Jul 20, 2018
- Fix a remote database connection issue when remote database's path contains special charachers.
- Shortcuts in Query Editor: Cmd + R to run query, Cmd + . to stop query, Cmd + I to format query.

1.1.0 - Jul 4, 2018
- Supports open remote SQLite database on iPhone or iPad with SQLiteFlow[iOS] installed.

1.0.5 - Jun 15, 2018
- Fix an issue that cause read database failed when database be replaced.
- Fix an issue that cause generate alter table script inaccurate.

1.0.4 - Jun 7, 2018
- Fix an issue that cause can't copy query results message to CSV.
- Additional bug fixes and stability improvements.

1.0.3 - May 11, 2018
- Toggle comments in Query Editor.
- Improvement for Format Query.
- Improvement for Syntax Highlighting.

1.0.2 - May 8, 2018
- Attach opened databases.
- Press enter to open Data Viewer for selected table.

1.0.1 - May 4, 2018
- Initial public release.

[Home](./)
