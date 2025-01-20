---
layout: default
title: SQLiteFlow
description: SQLiteFlow for Mac release notes.
---

6.5.8 - Jan 20, 2025
- JSONB Editor. Fix an issue that may load JSONB data failed.
- Supports SQLite version 3.48.0 (2025-01-14).

6.5.7 - Jan 7, 2025
- Bug fixes and stability improvements.

6.5.6 - Jan 4, 2025
- Fix a crash issue when creating a FTS table.

6.5.5 - Dec 8, 2024
- Supports SQLite version 3.47.2 (2024-12-07).

6.5.4 - Dec 7, 2024
- Bug fixes and stability improvements.

6.5.3 - Nov 27, 2024
- Create Function. Supports create scalar function using a simple JavaScript routine.
- Supports SQLite version 3.47.1 (2024-11-25).
- Additional bug fixes and stability improvements.

6.5.2 - Nov 14, 2024
- Data Editor & Query Result, add an option to the Text Editor to let user format text as JSON.
- Additional bug fixes and stability improvements.

6.5.1 - Oct 22, 2024
- Query Editor. Now some database relate UI will automatically be refreshed after execute queries that may change database schema.
- Supports SQLite version 3.47.0 (2024-10-21).
- Additional bug fixes and stability improvements.

6.5.0 - Oct 2, 2024
- Query Editor. Explain and Explain Query Plan now respect to user selection text.
- Alter Table. Fix an issue that may cause editing indexed columns by choosing an item from a popup menu item have no effect.
- Purchase Plan. Fix an issue that may cause Purchase Plan page displays unexpectedly when app launches.
- Inside Explorer. When open a database file, the temp database journal files will no longer flush to main file automatically.
- Inside Explorer. Fix an issue that may lead to app crashes.
- Shortcut. Run Query action. Fix an issue that when query is empty and the setting Include Query Message in Result in turned on, query message is not included in result.
- Additional bug fixes and stability improvements.

6.4.2 - Sep 13, 2024
- Bug fixes and stability improvements.

6.4.1 - Sep 13, 2024
- Data Editor, supports load and save filter as a filter file.
- Data Editor, supports change visibility of columns. Requires macOS 14.0 or later.
- Alter View, prepend DROP VIEW statement before CREATE VIEW statement to make altering a view more conveniently.
- Database List, supports toggle show database location. Currently the default value is set to off, you can turn it on through right clicking a local database name - Show Database Location. If the app has simulator access permission, then databases on simulator folder may show simulator relative location info instead of file path.
- Update SQLCipher library to version 4.6.1.

6.4.0 - Aug 13, 2024
- Supports SQLite version 3.46.1 (2024-08-13).

6.3.9 - Jul 8, 2024
- Bug fixes and stability improvements.

6.3.8 - May 24, 2024
- Supports SQLite version 3.46.0 (2024-05-23).
- Additional bug fixes and stability improvements

6.3.7 - Apr 30, 2024
- Database List, supports show foreign key field icon.
- Supports SQLite version 3.45.3 (2024-04-15).
- Update SQLCipher library to version 4.5.7.

6.3.6 - Apr 15, 2024
- ER Diagram. Add an icon to primary key field to indicate a table's primary key.
- ER Diagram. Add an icon to foreign key field to indicate a table's foreign key.
- ER Diagram. Field name and type now has different text styling.
- ER Diagram. When select a foreign key field, foreign key referenced field, or relation path, related elements will be highlighted.
- ER Diagram. Supports open Table Schema (by clicking the button besides the table name) to edit table's schema structure.
- ER Diagram. Supports open Data Editor (by right clicking a table name - Select Rows) to edit table's data.
- Table Schema. Supports editing indexes on expressions.
- Table Schema. Supports editing partial indexes.
- Table Schema. Let alter table SQL preview less verbose in some scenarios.

6.3.3 - Mar 31, 2024
- Supports show database ER diagram. You can go to Menu - Database - ER Diagram to display it.
- ER Diagram, supports toggle field type hide and show.
- ER Diagram, supports enable Relationship Guessing. If this setting is enable, the diagram would treat two tables have relationship if they have appropriate table and field name even if they are not declared have relationship. For example, a table Customer and a table Invoice (which has a field named CustomerID) will be treated have relationship even if there's no foreign key declaration on table Invoice.
- ER Diagram, supports copy as Mermaid markdown.
- Access Simulator, supports open app group container folder if exists.

6.3.2 - Mar 21, 2024
- Bug fixes and stability improvements.

6.3.1 - Mar 18, 2024
- Supports SQLite version 3.45.2 (2024-03-12).

6.3.0 - Mar 10, 2024
<br/><br/>Redesign purchase plans, this update has no effect on existing users. All plans can let user enjoy all features of the app. This version of SQLiteFlow requires macOS 13.0 or later.
- 2-week Trial, the free trial start automatically at your first time download the app, no in-app purchases will be involved. App will be locked when free trial ends.
- Pay-As-You-Go, a monthly subscription that let user enjoy the app. App will be locked when subscription expired.
- Unlimited Annual, an annually subscription that let user enjoy the app. App will be locked when subscription expired.
- Lifetime License, buy once, own the app. This plan was previously named Full App, so existing purchased user should already have this.

6.2.6 - Jan 31, 2024
- Supports SQLite version 3.45.1 (2024-01-30).

6.2.5 - Jan 20, 2024
- Update SQLCipher library to version 4.5.6.

6.2.4 - Jan 16, 2024
- JSONB Editor, supports view JSONB as JSON in Data Editor & Query Result
- JSONB Editor, supports edit JSONB as JSON in Data Editor.
- Hex Editor, supports copy hex values as C code.
- Import, supports import data by SQL file.
- Supports SQLite version 3.45.0 (2024-01-15).
- Additional bug fixes and stability improvements.

6.2.3 - Nov 29, 2023
- Supports SQLite version 3.44.2 (2023-11-24).

6.2.2 - Nov 22, 2023
- Supports SQLite version 3.44.1 (2023-11-22).

6.2.1 - Nov 15, 2023
- Export, add an export type: List. The List type behaves similar with the list output mode in sqlite3 command line shell, but show BLOB data as empty. Available on Data Editor, Query Editor and Run Query Shortcuts action.

6.2.0 - Nov 4, 2023
- Supports SQLite version 3.44.0 (2023-11-01).
- Supports import JSON to a table.
- Shortcuts. Supports import JSON to a table. (If import from a JSON file, the file cannot have “.json” file extension due to a bug of the Shortcuts app). Requires macOS 14.0 or later.
- Table Schema, Data Editor, Statistics, Font and Color Settings, Load Extension Settings. Give “+’ button a hotkey ⇧⌘N. Give “-“ button a hotkey ⌫ (Delete).
- Database List. Supports ⌥-Double Click a table name/view name or ⌥-Return a table name/view name to open Table Schema/Alter View page.
- Access Simulator. Fix an issue that may cause some simulators not showing up.
- This update may reset your toolbar settings due to a compatibility issue.
- This version of SQLiteFlow requires macOS 12.0 or later.

6.1.0 - Oct 15, 2023
- Supports SQLite version 3.43.2 (2023-10-10).

6.0.9 - Oct 7, 2023
- Bug fixes and stability improvements.

6.0.8 - Sep 28, 2023
- Bug fixes and stability improvements.

6.0.7 - Sep 17, 2023
- Supports persist opened databases across app launches. You can go to Settings - General to enable it.
- Additional bug fixes and stability improvements.

6.0.6 - Sep 12, 2023
- Supports SQLite version 3.43.1 (2023-09-11).
- Update SQLCipher library to version 4.5.5.

6.0.5 - Aug 25, 2023
- Supports SQLite version 3.43.0 (2023-08-24).
- Additional bug fixes and stability improvements.

6.0.4 - Aug 21, 2023
- Supports SQLite load extension.

6.0.3 - May 17, 2023
- Supports SQLite version 3.42.0 (2023-05-16).
- Update SQLCipher library to version 4.5.4.

6.0.2 - Apr 11, 2023
- Database Diff. Supports use primary key instead of RowID to pair to diff, and this option is enabled by default now.
- Shortcuts. The Run Query action now offers an option to exclude query message in result.

6.0.1 - Mar 22, 2023
- Supports SQLite version 3.41.2 (2022-03-22).

6.0.0 - Mar 6, 2023
- Bug fixes and stability improvements.

5.9.9 - Mar 2, 2023
- Query Editor, supports select the database that run query against.

5.9.8 - Feb 25, 2023
- Query Editor. Supports press Tab key to insert multi line indent if multi lines have been selected.
- Query Editor. Supports press Shift-Tab key to remove selected lines indent.
- Supports SQLite version 3.41.0 (2023-02-21).

5.9.6 - Feb 14, 2023
- LLDB Co-worker, supports sfopen command. Let you open a copy of a temporary local database that originally in debugged device.
- LLDB Co-worker, supports sfsave command. Let you copy the temporary local database (that originally created by sfopen command) to debugged device.
Go to Settings - LLDB Co-worker to check how to set it up.

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
