---
layout: default
title: SQLiteFlow
description: SQLiteFlow for iOS release notes.
---

5.7.1 - Jun 1, 2022
- Fix a potential crash issue when editing query.
- Additional bug fixes and stability improvements.

5.7.0 - May 22, 2022
- The speed of loading databases has been significantly improved.
- Data Editor, upgrade show blob as image to show blob as preview. So blob data can not only display as image if possible, but also can display as some other types based on its content if possible, like movie, pdf, etc.
- Data Editor, supports use filter when view views.
- Supports enable or disable display table record counts when open database.
- Import CSV, supports display CSV Data through Quick Look. (Please note that during our test, if the CSV data is too large to display in a short time, then it will be displayed as a brief file info instead of a full CSV content.)

5.3.1 - Mar 29, 2022
- Bug fixes and stability improvements.

5.3.0 - Sep 29, 2021
- Data Editor, more convenient filter behavior. 
- Query Editor, supports customize syntax highlighting.
- Additional bug fixes and stability improvements.

5.1.2 - Aug 18, 2021
- Shortcuts, allows "Run Query" and "Import CSV" run when device is locked to make it convenient for automation purpose.

5.1.1 - Aug 12, 2021
- Bug fixes and stability improvements.

5.1.0 - Aug 3, 2021
- UI enhancement.
- Query Editor, supports syntax aware indenting when typing Return.
- This version of SQLiteFlow now requires iOS 14.0 or later.
- Additional bug fixes and stability improvements.

5.0.5 - May 21, 2021
- When the app's language is set to Simplified Chinese, Query Editor's SQL auto-completion feature now supports use Pinyin to search specific table names or fields.

5.0.4 - May 17, 2021
- Enhancement to the code auto completion behavior.

5.0.3 - May 16, 2021
- Enhancement to the code auto completion behavior.

5.0.2 - May 11, 2021
- Enhancement to the code auto completion behavior.
- Additional bug fixes and stability improvements.

4.8.4 - Apr 12, 2021
- Shortcuts. When running an intent, SQLiteFlow now will try to download required files like database files, CSV files, etc, which are offloaded before actually do its job.

4.8.3 - Mar 14, 2021
- Fix an issue that may cause when exporting table to insert statements, the column names not suitably been escaped.

4.8.2 - Jan 10, 2021
- Support for Japanese.

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
