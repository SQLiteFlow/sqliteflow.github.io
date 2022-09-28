---
layout: default
title: SQLiteFlow
description: Mac SQLiteFlow 更新说明。
---

5.8.4 - 2022年9月28日
- 支持SQLite version 3.39.3 (2022-09-05)。

5.8.3 - 2022年8月12日
- 支持SQLite version 3.39.2 (2022-07-21)。
- 更新SQLCipher库版本到4.5.2。

5.8.2 - 2022年7月19日
- 导入CSV，支持导入时行列转置。
- 导入CSV，如果“第一行为标题行”并且设置了导入到现存表，如果标题行的字段顺序和表的字段顺序不同，那么现在已支持正确导入。
- 导入CSV，如果“第一行为标题行”并且设置了导入到现存表，如果标题行的字段是表字段的子集，那么现在已支持正确导入。

5.8.1 - 2022年6月26日
- 新增了一个简单实用的小工具JSON格式化器作为夏日礼物送给大家。这是这个小工具的第一个版本，您可以通过“主菜单-工具”或者“自定义工具栏...“来访问它。如果您有什么问题和建议，欢迎来反馈给我们。
- 支持SQLite version 3.39.0 (2022-06-25)。

5.7.4 - 2022年6月11日
- 问题修复与稳定性改善。

5.7.3 - 2022年6月10日
- 问题修复与稳定性改善。

5.7.2 - 2022年6月2日
- 修复一个编辑查询时可能会闪退的问题。
- 其它问题修复与稳定性改善。

5.7.1 - 2022年05月21日
- 修复通过UI创建新表时会闪退的问题。

5.7.0 - 2022年05月16日
- 极大的提升了数据库的加载速度。
- 数据编辑器，升级显示blob为图片为显示blob为预览。这样blob数据如果可能，不仅可以显示图片，还能根据它的内容显示其它类型的数据，比如影片，pdf等。
- 数据编辑器，支持在视图中使用过滤来查看数据。

5.6.9 - 2022年05月7日
- 支持SQLite version 3.38.5 (2022-05-06)。

5.6.8 - 2022年04月28日
- 支持SQLite version 3.38.3 (2022-04-27)。
- 更新SQLCipher库版本到4.5.1。

5.6.7 - 2022年03月26日
- 支持SQLite version 3.38.2 (2022-03-26)。

5.6.6 - 2022年03月24日
- 问题修复与稳定性改善。

5.6.5 - 2022年03月13日
- 支持SQLite version 3.38.1 (2022-03-12)。

5.6.4 - 2022年02月27日
- 支持SQLite version 3.38.0 (2022-02-22)。

5.6.3 - 2022年01月12日
- 问题修复与稳定性改善。

5.6.2 - 2022年01月06日
- 支持SQLite version 3.37.2 (2022-01-06)。

5.6.1 - 2022年01月05日
- 支持SQLite version 3.37.1 (2021-12-30)。

5.6.0 - 2021年11月29日
- 支持SQLite version 3.37.0 (2021-11-27)。

5.5.0 - 2021年11月26日
- 添加捷径支持。现在“执行查询”和“导入CSV“已经可以在捷径应用中使用了。
- 其它问题修复与稳定性改善。

5.4.0 - 2021年11月12日
- 更新SQLCipher库版本到4.5.0。
- 此版本的SQLiteFlow需要macOS 10.14支持。
- 其它问题修复与稳定性改善。

5.3.0 - 2021年9月20日
- 数据库列表，支持过滤项目时选择只过滤表或者只过滤表字段。
- 数据库列表，支持右键点击一个字段名来重命名字段。 (需要SQLite 3.25.0+支持)
- 数据编辑器，为文本单元格添加“以文本编辑”右键菜单项目，用户可以用它来唤出一个文本编辑器弹窗来编辑单元格内容。
- 导出数据，支持直接将导出结果拷贝的剪切板。
- 现在，如果用户选择了一个窗口，那么如果合适的话，在数据库列表中的项目会根据窗口内容同步被选中。
- 支持访问苹果模拟器。这样用户在开发他们的App时，就可以更方便地打开他们App的Documents目录了。

5.2.4 - 2021年8月23日
- 问题修复与稳定性改善。

5.2.3 - 2021年8月23日
- 问题修复与稳定性改善。

5.2.2 - 2021年8月12日
- 在数据库列表中支持显示表和视图的数量。

5.2.0 - 2021年6月21日
- 查询编辑器，支持键入回车键时执行语法感知缩进。
- 其它问题修复与稳定性改善。

5.1.0 - 2021年6月6日
- 数据库列表中支持显示表字段信息。这个信息现在包括字段名，字段类型，非空约束和主键约束。
- 支持手动设定浅色/深色模式。

5.0.8 - 2021年6月21日
- 支持SQLite version 3.36.0 (2021-06-18)。

5.0.6 - 2021年5月24日
- 问题修复与稳定性改善。

5.0.5 - 2021年5月21日
- 当软件语言设置为简体中文时，查询编辑器的代码自动补全功能支持使用拼音来检索出对应的表名或字段。

5.0.4 - 2021年5月17日
- 改进SQL代码自动补全功能。

5.0.3 - 2021年5月16日
- 改进SQL代码自动补全功能。

5.0.2 - 2021年5月11日
- 改进SQL代码自动补全功能。
- 其它问题修复与稳定性改善。

5.0.1 - 2021年5月6日
- 问题修复与稳定性改善。

5.0.0 - 2021年5月4日
- 在数据编辑器的过滤功能中增加了一个"SQL"操作符。
- 支持处理经SQLCipher库加密的数据库。
- 其它问题修复与稳定性改善。

4.9.2 - 2021年4月20日
- 问题修复与稳定性改善。

4.9.1 - 2021年4月20日
- 支持SQLite version 3.35.5 (2021-04-19)。

4.9.0 - 2021年3月28日
- 支持SQLite version 3.35.3 (2021-03-26)。
- 查询编辑器，当用户选中字符串的前缀为“SELECT”时，支持右键菜单创建视图。
- 数据编辑器，添加漂浮行头，它让用户多一种方式选择行，并且在这里选择行时不会触发编辑操作。

4.8.4 - 2021年3月14日
- 支持SQLite version 3.35.0 (2021-03-12)。
- 修复了一个可能导致导出表数据到insert语句时没有格式化列名的问题。

4.8.3 - 2021年1月24日
- 支持SQLite version 3.34.1 (2021-01-20)。

4.8.2 - 2021年1月10日
- 添加日语支持。

4.8.1 - 2020年12月13日
- 在macOS 11中支持全高度边栏。
- 其它问题修复与稳定性改善。

4.8.0 - 2020年12月11日
- 增加Apple Silicon Mac支持。
- 数据编辑器支持拷贝数据为insert/update语句。
- 支持转储数据库到SQL文件。
- 支持SQLite version 3.34.0 (2020-12-01)。
- 修复了一个在程序闪退后可能导致用户SQL文件被移动到程序临时查询会话文件夹的问题。
- 其它问题修复与稳定性改善。

4.7.0 - 2020年11月4日
- 极大的提高了数据编辑器和查询结果的性能，展示列数越多，效果越明显。
- 此版本的SQLiteFlow需要macOS 10.14支持。
- 其它问题修复与稳定性改善。

4.6.1 - 2020年9月15日
- 修复了一个在全屏模式中可能导致UI显示不正常的问题。
- 其它问题修复与稳定性改善。

4.6.0 - 2020年9月8日
- 支持导出数据到JSON。
- 支持导出数据到Markdown。

4.5.1 - 2020年8月29日
- 问题修复与稳定性改善。

4.5.0 - 2020年8月28日
- 标签页行为改动。改动前，关闭窗口的意思是隐藏窗口，所有的标签页保持打开。现在，关闭窗口的意思是关闭这个窗口中的所有标签页并且关闭窗口。
- 现在SQLiteFlow使用系统提供的标签栏来取代之前的标签栏，以获得更多系统提供的功能。
- 支持自定义工具栏，并且设计了新的工具栏图标。
- 改进了查询编辑器的自动保存功能。
- 支持SQLite version 3.33.0 (2020-08-14)。
- 其它问题修复与稳定性改善。

4.3.1 - 2020年7月8日
- 为数据编辑器中的过滤器添加“!=“和“不包含”操作符支持。

4.3.0 - 2020年7月3日
- 新建数据库时支持选择日志模式。
- 修改表结构，支持使用拖拽来重新排序表列。
- 修改表结构，支持设置表的WITHOUT ROWID类型。
- 数据库列表中的表/视图的右键菜单支持导出数据。
- 添加更多触控栏支持。
- 其它问题修复与稳定性改善。

4.2.0 - 2020年6月28日
- 添加一些基本的触控栏支持。

4.1.1 - 2020年6月22日
- 支持SQLite 3.32.3 (2020-06-18)。
- 其它问题修复与稳定性改善。

4.1.0 - 2020年6月19日
- 支持选择使用macOS内嵌SQLite库，或者选择使用最新SQLite库（目前是SQLite 3.32.2）来工作。
- 其它问题修复与稳定性改善。

4.0.1 - 2020年5月25日
- 在打开数据库对话框中添加了一个“允许选择所有文件类型”的选项，来让用户能够在打开数据库对话框中，打开拥有自定义拓展名的数据库。
- 修复偏好设置中“启用外键约束“和”Tab键行为“的值没有显示正确的问题。

4.0.0 - 2020年5月22日
- 在数据库列表中，支持右键表名-重命名表名。
- 格式化查询，支持选择偏好缩进字符为空格或者Tabs。
- 格式化查询，支持设置缩进宽度。现在默认的缩进宽度为4，与默认Tab宽度（同样为4）相匹配。在之前版本中，这个值无法设置时，默认缩进宽度为3.
- 格式化查询，支持设置分隔列定义的逗号的风格，可选择在前或者在尾。
- 文本编辑，支持设置Tab宽度。
- 文本编辑，支持设置Tab键行为为插入tab字符或者插入空格。
- “启用外键约束”这个设置从数据编辑器移到了“偏好设置” - “通用”中，所以这个设置现在对数据编辑器，查询编辑器和导入CSV都可以生效了。
- 改进修改表结构。
- 导入/导出CSV现在支持了使用分号（;）或者tab来作为分隔符去导入/导出数据。
- 导入CSV，修复了一个当CSV文本的最后一行的最后一个值没有提供时，导入时无法导入最后一行的问题。
- 其它问题修复与稳定性改善。

3.8.1 - 2019年8月22日
- 在十六进制编辑器中将”设置为NULL“改为”设置为NULL并应用“。
- 语法高亮与格式化查询支持upsert分句和window function以兼容未来版本的macOS。
- 其它问题修复与稳定性改善。

3.8.0 - 2019年8月16日
- 内部查看器，查看SQLite数据库文件，日志文件，WAL文件或者WAL-索引文件的内部结构。
- 现在数据编辑器编辑数据时，您可以使用Tab键来切换列。
- 现在数据编辑器编辑数据时，您可以使用ESC键来撤销对当前值的修改。
- 现在数据编辑器编辑数据时，您可以使用Enter键来完成编辑数据, 然后再使用Enter键来触发数据保存。
- 在数据编辑器中增加了左边栏来方便您选择行。
- 在数据编辑器中拷贝数据到CSV中列的顺序会根据UI中列的顺序变化而变化。
- 在数据编辑器中增加了“导出”按钮。您可以选择“已选行”，“显示中的行”或者“整个表”，以及是否“包含标题行”来从表/视图中导出数据到CSV文件。
- 在查询结果中增加了“导出”按钮。您可以选择“已选行”或者“显示中的行”，以及是否“包含标题行”来从查询结果或者查询消息中导出数据到CSV文件。
- 现在在数据库列表中刷新数据库会触发已打开的标签页一并刷新。

3.7.0 - 2019年6月28日
- 支持简体中文、繁体中文。
- 其它问题修复和稳定性更新。

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
