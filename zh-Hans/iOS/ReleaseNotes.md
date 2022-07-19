---
layout: default
title: SQLiteFlow
description: SQLiteFlow for iOS release notes.
---

5.8.2 - 2022年7月19日
- 导入CSV，支持导入时行列转置。
- 导入CSV，如果“第一行为标题行”并且设置了导入到现存表，如果标题行的字段顺序和表的字段顺序不同，那么现在已支持正确导入。
- 导入CSV，如果“第一行为标题行”并且设置了导入到现存表，如果标题行的字段是表字段的子集，那么现在已支持正确导入。

5.8.0 - 2022年6月26日
- 问题修复与稳定性改善。

5.7.2 - 2022年6月11日
- 问题修复与稳定性改善。

5.7.1 - 2022年6月1日
- 修复一个编辑查询时可能会闪退的问题。
- 其它问题修复与稳定性改善。

5.7.0 - 2022年5月22日
- 极大的提升了数据库的加载速度。
- 数据编辑器，升级显示blob为图片为显示blob为预览。这样blob数据如果可能，不仅可以显示图片，还能根据它的内容显示其它类型的数据，比如影片，pdf等。
- 数据编辑器，支持在视图中使用过滤来查看数据。
- 支持打开数据库时开启或关闭表记录数的显示。
- 导入CSV，支持通过快速查看来显示CSV数据。（需要注意的是通过我们的测试，如果CSV数据因为太大以至不能在短时间内显示时，它会被显示为一个文件信息简介而不是一个完整的CSV内容。）

5.3.1 - 2022年3月29日
- 问题修复与稳定性改善。

5.3.0 - 2021年9月29日
- 数据编辑器，支持更方便的使用过滤。
- 查询编辑器，支持自定义语法高亮。
- 其它问题修复与稳定性改善。

5.1.2 - 2021年8月18日
- 捷径，允许“执行查询”和“导入CSV“在设备锁定状态下执行，方便自动化操作。

5.1.1 - 2021年8月12日
- 问题修复与稳定性改善。

5.1.0 - 2021年8月3日
- UI改进。
- 查询编辑器，支持键入回车键时执行语法感知缩进。
- 此版本的SQLiteFlow现在需要iOS 14.0+支持。
- 其它问题修复与稳定性改善。

5.0.5 - 2021年5月21日
- 当软件语言设置为简体中文时，查询编辑器的代码自动补全功能支持使用拼音来检索出对应的表名或字段。

5.0.4 - 2021年5月17日
- 改进SQL代码自动补全功能。

5.0.3 - 2021年5月16日
- 改进SQL代码自动补全功能。

5.0.2 - 2021年5月11日
- 改进SQL代码自动补全功能。
- 其它问题修复与稳定性改善。

4.8.4 - 2021年4月12日
- 捷径。当运行一个捷径程序时，SQLiteFlow现在首先会下载必要的但尚未被下载的文件，比如数据库文件，CSV文件等，然后再去做它的工作。

4.8.3 - 2021年3月14日
- 修复了一个可能导致导出表数据到insert语句时没有格式化列名的问题。

4.8.2 - 2021年1月10日
- 添加日语支持。

4.8.1 - 2020年12月15日
- 问题修复与稳定性改善。

4.8.0 - 2020年12月14日
- 数据编辑器支持导出数据为insert/update语句。
- 支持转储数据库到SQL文件。
- 其它问题修复与稳定性改善。

4.6.2 - 2020年11月30日
- 问题修复和稳定性更新。

4.6.1 - 2020年11月23日
- 导入CSV，现在“CSV第一行为标题“的默认值为”是“，和导出CSV功能一致。
- 导入CSV，支持导入前清空表数据。
- 添加快捷指令支持。现在“执行查询”和“导入CSV“已经可以在快接指令应用中使用了。这个功能需要iOS 14.0+支持。

4.6.0 - 2020年9月18日
- 支持导出数据到JSON。
- 支持导出数据到Markdown。
- 此版本的SQLiteFlow现在需要iOS 13+支持。

4.3.6 - 2020年9月7日
- 问题修复和稳定性更新。

4.3.5 - 2020年8月6日
- 数据编辑器，支持用键盘方向键来选择单元格。需要iOS 13.4+或者iPadOS 13.4+支持。
- 支持打开能够出现在“浏览”中的使用自定义拓展名的SQLite数据库。

4.3.4 - 2020年7月8日
- 为数据编辑器中的过滤器添加“!=“和“不包含”操作符支持。

4.3.3 - 2020年7月3日
- 表列表中支持重命名表。
- 新建数据库时支持选择日志模式（WAL或者DELETE）。
- 修改表结构，支持使用拖拽来重新排序表列。
- 修改表结构，支持设置表的WITHOUT ROWID类型。

4.3.2 - 2020年6月19日
- 问题修复和稳定性更新。

4.3.1 - 2020年6月9日
- 问题修复和稳定性更新。

4.3.0 - 2020年6月8日
- 格式化查询，支持选择偏好缩进字符为空格或者Tabs。
- 格式化查询，支持设置缩进宽度。现在默认的缩进宽度为4，与默认Tab宽度（同样为4）相匹配。在之前版本中，这个值无法设置时，默认缩进宽度为3.
- 格式化查询，支持设置分隔列定义的逗号的风格，可选择在前或者在尾。
- 文本编辑，支持设置Tab宽度。
- 文本编辑，支持设置Tab键行为为插入tab字符或者插入空格。
- “启用外键约束”这个设置从数据编辑器移到了“设置” - “通用”中，所以这个设置现在对数据编辑器，查询编辑器和导入CSV都可以生效了。
- 导入CSV现在支持了使用分号（;）来作为分隔符去导入数据。

4.2.0 - 2020年4月28日
- 修改表结构支持预览修改表结构的SQL。
- 改进修改表结构使用体验。
- 改进连接实体键盘后，查询编辑器的输入体验。需要iOS 13.4+或者iPadOS 13.4+支持。
- 合并查询编辑器和查询结果页面。
- 其它问题修复与稳定性改善。

4.1.1 - 2020年3月28日
- 问题修复与稳定性改善。

4.1.0 - 2020年3月26日
- 在“数据编辑器”和“查询结果”中支持单元格，行和列的多选。
- 在“查询编辑器”中支持执行选中查询。
- 修复一个可能导致标记外部文件到”最近使用“列表失败的问题。
- 其它问题修复与稳定性改善。

4.0.0 - 2020年1月1日
- “数据库列表”重命名为“浏览”。
- 在“浏览”中，支持打开/新建本地文件夹，SQLite数据库，SQL文件，CSV文件。
- 在“浏览”中，支持打开过滤文件。
- 在“浏览”中，支持打开外部SQL文件，CSV文件，过滤文件。
- 在“浏览”中，支持打开外部文件夹。需要iOS 13.0+或者iPadOS 13.0+支持。
- 支持显示最近使用文件。
- 在查询结果中支持以十六进制来显示Blob数据。
- 在数据编辑器和查询结果中，支持长按显示记录预览。需要iOS 13.0+或者iPadOS 13.0+支持。
- 在数据编辑器中增加启用外间约束支持。
- 在数据编辑器中编辑数据时，屏幕上方增加“完成”按钮来保存编辑。
- 在数据编辑器和查询结果中增加拷贝一行数据的功能。
- 现在，数据编辑器中的过滤已基于过滤文件。
- 在数据编辑器中，支持轻触过滤按钮来打开或者创建一个过滤文件。
- 在数据编辑器中，打开过滤文件后，用户可以编辑或者应用次过滤。
- 在数据编辑器中应用一个过滤后，用户可以轻触过滤按钮来选择“编辑过滤”，“移除过滤”或者“选择其它过滤”。
- 修复了一个在导入CSV文件时可能导致导入数据为乱码的问题。
- 修复了无法在查询结果中拷贝数据的问题。
- 其它问题修复与稳定性改善。

3.9.3 - 2019年9月30日
- 修复了在查询编辑器中格式化查询时可能会导致引号转化为非ASCII编码引号的问题。

3.9.2 - 2019年9月28日
- 修复了数据库列表中分享菜单显示为空的问题。

3.9.1 - 2019年9月26日
- 为iPadOS 13支持多窗口。

3.9.0 - 2019年9月20日
- 在iOS 13中支持深色模式。
- 移除数据编辑器中的全局编辑文本框，所以您现在可以直接在数据单元格中编辑数据了。

3.8.0 - 2019年8月23日
- 语法高亮与格式化查询支持upsert分句和window function以兼容未来版本的iOS。
- 修复了在某些场景下使用中文输入法输入异常的问题。
- 其它问题修复与稳定性改善。

3.7.0 - 2019年7月2日
- 支持简体中文、繁体中文。
- 其它问题修复和稳定性更新。

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

[Home](./iOS)
