---
layout: default
title: SQLiteFlow
description: SQLiteFlow for Mac release notes.
---

5.9.5 - Feb 14, 2023
- LLDB co-worker. Add two LLDB commands sfopen and sfsave. Go to Settings - LLDB Co-worker to check how to set it up.

5.9.3 - Jan 28, 2023
- Bug fixes and stability improvements.

5.9.2 - Jan 26, 2023
- Data Editor, supports show 16 bytes BLOB as UUID string. You can go to Settings - Data Editor to enable it.

5.9.1 - Jan 9, 2023
- Supports SQLite version 3.40.1 (2022-12-28).
- Additional bug fixes and stability improvements.

5.9.0 - Dec 26, 2022
- Update SQLCipher library to version 4.5.3.
- This version of SQLiteFlow requires macOS 11.0 or later.
- Additional bug fixes and stability improvements.

5.8.6 - Dec 1, 2022
- Enhancement to the tab bar title.
- Fix an hotkey issue which may cause some hotkey require unnecessary additional Shift modifier.
- Supports SQLite version 3.40.0 (2022-11-16).
- Additional bug fixes and stability improvements.

5.8.5 - Oct 2, 2022
- Supports SQLite version 3.39.4 (2022-09-29).

5.8.4 - Sep 28, 2022
- Supports SQLite version 3.39.3 (2022-09-05).

5.8.3 - Aug 12, 2022
- Supports SQLite version 3.39.2 (2022-07-21).
- Update SQLCipher library to version 4.5.2.

5.8.2 - Jul 19, 2022
- Import CSV, supports transpose rows and columns when import.
- Import CSV, if “First Line in CSV is Header” is enabled, and is set to import to an existing table, then if the sequence of the header fields is different from the sequence of the table fields, you can now import it correctly.
- Import CSV, if “First Line in CSV is Header” is enabled, and is set to import to an existing table, then if the header fields is a subset of the table fields, you can now import it correctly if database constraints allows.

5.8.1 - Jun 26, 2022
- Add a simple and useful utility JSON Formatter as a summer gift to all of you. This is the initial version of this utility, and you can access it through "Main Menu - Tools" or  "Customize Toolbar". If you have any questions or advices about it, you are welcome to contact us.
- Supports SQLite version 3.39.0 (2022-06-25).

5.7.4 - Jun 11, 2022
- Bug fixes and stability improvements.

5.7.3 - Jun 10, 2022
- Bug fixes and stability improvements.

5.7.2 - Jun 2, 2022
- Fix a potential crash issue when editing query.
- Additional bug fixes and stability improvements.

5.7.1 - May 21, 2022
- Fix a crash issue when creating a new table through UI.

5.7.0 - May 16, 2022
- The speed of loading databases has been significantly improved.
- Data Editor, upgrade show blob as image to show blob as preview. So blob data can not only display as image if possible, but also can display as some other types based on its content if possible, like movie, pdf, etc.
- Data Editor, supports use filter when view views.

5.6.9 - May 7, 2022
- Supports SQLite version 3.38.5 (2022-05-06).

5.6.8 - Apr 28, 2022
- Supports SQLite version 3.38.3 (2022-04-27).
- Update SQLCipher library to version 4.5.1.

5.6.7 - Mar 26, 2022
- Supports SQLite version 3.38.2 (2022-03-26).

5.6.6 - Mar 24, 2022
- Bug fixes and stability improvements.

5.6.5 - Mar 13, 2022
- Supports SQLite version 3.38.1 (2022-03-12).

5.6.4 - Feb 27, 2022
- Supports SQLite version 3.38.0 (2022-02-22).

5.6.3 - Jan 12, 2022
- Bug fixes and stability improvements.

5.6.2 - Jan 6, 2022
- Supports SQLite version 3.37.2 (2022-01-06).

5.6.1 - Jan 5, 2022
- Supports SQLite version 3.37.1 (2021-12-30).

5.6.0 - Nov 29, 2021
- Supports SQLite version 3.37.0 (2021-11-27).

5.5.0 - Nov 26, 2021
- Add Shortcuts support. Now “Run Query” and “Import CSV” are available in the Shortcuts app.
- Additional bug fixes and stability improvements.

5.4.0 - Nov 12, 2021
- Update SQLCipher library to version 4.5.0.
- This version of SQLiteFlow requires macOS 10.15 or later.
- Additional bug fixes and stability improvements.

5.3.0 - Sep 20, 2021
- Database List, supports filter item only by tables or filter item only by table fields.
- Database List, supports right click a field name to rename a table field. (Require SQLite 3.25.0 or later.)
- Data Editor, add "Edit as Text" to text cell's context menu, so users can use it to bring up a popover text editor to edit the cell's content as text.
- Export, supports copy the export result to clipboard directly.
- Now if users select a window tab, then the selected item in database list will be synced based on the tab's content if appropriate.
- Supports access Apple simulator. So users can open their app's Documents directory more easily when developing their apps.

5.2.4 - Aug 23, 2021
- Bug fixes and stability improvements.

5.2.3 - Aug 23, 2021
- Bug fixes and stability improvements.

5.2.2 - Aug 12, 2021
- Supports show table/view counts in Database List.

5.2.0 - Jul 21, 2021
- Query Editor, supports syntax aware indenting when typing Return.
- Additional bug fixes and stability improvements.

5.1.0 - Jul 6, 2021
- Supports show table fields information in database list. The information currently contains field name, field type, not null constraints and primary key constraints.
- Supports manually specific light/dark appearance.

5.0.8 - Jun 21, 2021
- Supports SQLite version 3.36.0 (2021-06-18).

5.0.6 - May 24, 2021
- Bug fixes and stability improvements.

5.0.5 - May 21, 2021
- When the app's language is set to Simplified Chinese, Query Editor's SQL auto-completion feature now supports use Pinyin to search specific table names or fields.

5.0.4 - May 17, 2021
- Enhancement to the code auto completion behavior.

5.0.3 - May 16, 2021
- Enhancement to the code auto completion behavior.

5.0.2 - May 11, 2021
- Enhancement to the code auto completion behavior.
- Additional bug fixes and stability improvements.

5.0.1 - May 6, 2021
- Bug fixes and stability improvements.

5.0.0 - May 4, 2021
- Add an operator "SQL" to Data Editor's filter feature.
- Supports handle encrypted SQLite databases which are encrypted by SQLCipher library.
- Additional bug fixes and stability improvements.

4.9.2 - Apr 20, 2021
- Bug fixes and stability improvements.

4.9.1 - Apr 20, 2021
- Supports SQLite version 3.35.5 (2021-04-19).

4.9.0 - Mar 14, 2021
- Supports SQLite version 3.35.3 (2021-03-26).
- Query Editor, supports create a view from right click menu if user selected string has prefix "SELECT".
- Data Editor, add a floating row header to data editor, it offers one more way to select rows, and could let user select a row without triggering editing.

4.8.4 - Mar 14, 2021
- Supports SQLite version 3.35.0 (2021-03-12).
- Fix an issue that may cause when exporting table to insert statements, the column names not suitably been escaped.

4.8.3 - Jan 24, 2021
- Supports SQLite version 3.34.1 (2021-01-20).

4.8.2 - Jan 10, 2021
- Support for Japanese.

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
