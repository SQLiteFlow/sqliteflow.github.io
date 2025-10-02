---
layout: default
title: SQLiteFlow
description: Mac SQLiteFlow 更新說明。
---

6.7.2 - 2025年10月2日
- 支援macOS 26。
- 其它問題修復與穩定性改善。

6.7.1 - 2025年8月15日
- 支援SQLite version 3.50.4 (2025-07-30)。
- 更新SQLCipher庫版本到4.10.0。

6.7.0 - 2025年7月20日
- 修復一個更改數據庫路徑可能導致app無法訪問數據庫的問題。舉個例子，當你打開在iOS模擬器中的數據庫並且重新部署app後，SQLiteFlow是應該可以正常訪問它的。

6.6.9 - 2025年7月19日
- 支援SQLite version 3.50.3 (2025-07-17)。

6.6.8 - 2025年6月29日
- 支援SQLite version 3.50.2 (2025-06-28)。

6.6.7 - 2025年6月21日
- 支援SQLite version 3.50.1 (2025-06-06)。
- 更新SQLCipher庫版本到4.9.0。
- 查詢編輯器，爲了讓「粘貼最近使用」這個功能更易被發現，現在可以在主菜單-「編輯器」中使用這個功能。
- 其它問題修復與穩定性改善。

6.6.6 - 2025年5月31日
- 支援SQLite version 3.50.0 (2025-05-29)。

6.6.5 - 2025年5月8日
- 支援SQLite version 3.49.2 (2025-05-07)。
- 更新SQLCipher庫版本到4.8.0。

6.6.4 - 2025年4月12日
- 更新SQLCipher庫版本到4.7.0。

6.6.3 - 2025年3月12日
- 問題修復與穩定性改善。

6.6.2 - 2025年3月11日
- 問題修復與穩定性改善。

6.6.1 - 2025年2月20日
- 十六進制編輯器。支持拷貝十六進制數據爲BLOB字串。
- 支援SQLite version 3.49.1 (2025-02-18)。

6.6.0 - 2025年2月16日
- 自動補全。支持自動補全大部分的SQLite內置函數，並且用佔位符來作爲參數提示。
- 支持使用Cmd+數字來切換窗口標籤頁。
- 在主菜單欄-工具菜單中添加導出菜單，使用戶可以更快捷的導出數據編輯器或者查詢結果頁中顯示中的行爲CSV，JSON或者Markdown到剪切板。
- 轉儲數據庫。修復了一個當某些觸發器存在時可能導致用於導入時失敗的問題。
- 支援SQLite version 3.49.0 (2025-02-06).
- 此版本的SQLiteFlow需要macOS 14.0+支持。

6.5.8 - 2025年1月20日
- JSONB編輯器. 修復一個可能導致讀取JSONB數據失敗的問題。
- 支援SQLite version 3.48.0 (2025-01-14)。

6.5.7 - 2025年1月7日
- 問題修復與穩定性改善。

6.5.6 - 2025年1月4日
- 修復一個創建FTS表時閃退的問題。

6.5.5 - 2024年12月8日
- 支援SQLite version 3.47.2 (2024-12-07)。

6.5.4 - 2024年12月7日
- 問題修復與穩定性改善。

6.5.3 - 2024年11月27日
- 創建函數。支持使用簡單的JavaScript例程創建標量函數。
- 支援SQLite version 3.47.1 (2024-11-25)。
- 其它問題修復與穩定性改善。

6.5.2 - 2024年11月14日
- 數據編輯器和查詢結果。添加了一個讓用戶在文本編輯器裏將文本格式化爲JSON的選項。
- 其它問題修復與穩定性改善。

6.5.1 - 2024年10月23日
- 查詢編輯器。現在執行完可能修改表結構的查詢後，會自動刷新一些和數據庫相關的界面。
- 支援SQLite version 3.47.0 (2024-10-21)。
- 其它問題修復與穩定性改善。

6.5.0 - 2024年10月2日
- 查詢編輯器。解釋和解釋查詢現在會對用戶選擇的文本來解釋。
- 修改表結構。修復一個導致在彈出菜單修改indexed column時沒有反應的問題。
- 購買計劃。修復一個在軟件啓動時購買計劃頁面可能非計劃彈出的問題。
- 內部查看器。當打開一個數據庫文件時，臨時日誌文件不再會被自動刷回主數據庫。
- 內部查看器。修復一個導致軟件閃退的問題。
- 捷徑。執行查詢。修復一個當查詢SQL爲空，且在設置中打開“在結果中包含查詢消息”時，結果中沒有包含查詢消息的問題。
- 其它問題修復與穩定性改善。

6.4.2 - 2024年9月13日
- 問題修復與穩定性改善。

6.4.1 - 2024年9月13日
- 數據編輯器。支持讀取和保存過濾爲過濾文件。
- 數據編輯器。支持修改列的可見性。需要macOS 14.0支持。
- 修改視圖。在CREATE VIEW語句前加上DROP VIEW語句使修改視圖更方便。
- 數據庫列表。支持切換是否顯示數據庫位置。當前此值默認爲關閉，您可以通過在一個本地數據庫名上右鍵-顯示數據庫位置來開啓它。如果此軟件被賦予了訪問模擬器權限，那麼在模擬器文件夾中的數據庫的位置將被顯示爲相對於模擬器路徑的信息而不是文件路徑。
- 更新SQLCipher庫版本到4.6.1。

6.4.0 - 2024年8月13日
- 支援SQLite version 3.46.1 (2024-08-13)。

6.3.9 - 2024年7月8日
- 問題修復與穩定性改善。

6.3.8 - 2024年5月24日
- 支援SQLite version 3.46.0 (2024-05-23)。
- 其它問題修復與穩定性改善。

6.3.7 - 2024年4月30日
- 數據庫列表。支持顯示外鍵圖標。
- 支援SQLite version 3.45.3 (2024-04-15)。
- 更新SQLCipher庫版本到4.5.7。

6.3.6 - 2024年4月15日
- ER圖表。爲主鍵字段增加指示圖標。
- ER圖表。爲外鍵字段增加指示圖標。
- ER圖表。字段名和類型現在有了不同的字體風格。
- ER圖表。當選擇一個外鍵字段，外鍵關聯字段，或者關係路徑時，相關元素會被高亮顯示。
- ER圖表。支持打開表結構（通過點擊表名旁邊的按鈕）來編輯表結構。
- ER圖表。支持打開數據編輯器（通過右鍵單擊表名-查看數據）來編輯數據。
- 表結構。支持編輯表達式索引。
- 表結構。支持編輯部分（partial）索引。
- 表結構。使修改表SQL預覽在某些場景中更精煉。

6.3.3 - 2024年3月31日
- 支持顯示ER圖表。您可以到「菜單」 - 「數據庫」 - 「ER圖表」來打卡它。
- ER圖表，支持切換字段類型顯示狀態。
- ER圖表，支持開啓關聯猜測。此設置開啓後，當表名與列名合適時，即使兩表沒有聲明關聯，也視力兩表爲關聯。舉個例子，即使Customer表和Invoice表（Invoice表有個字段CustomerID）沒有聲明外鍵關聯，也視兩表有關聯。
- ER圖表，支持拷貝到Mermaid markdown。
- 訪問模擬器，支持打開app group container文件夾（如果存在的話）。

6.3.2 - 2024年3月21日
- 問題修復與穩定性改善。

6.3.1 - 2024年3月18日
- 支援SQLite version 3.45.2 (2024-03-12)。

6.3.0 - 2024年3月10日
<br/><br/>重新設計了購買方案，本更新不影響已購買用戶。所有的方案可以讓用戶享受此軟件所有的功能。此版本的SQLiteFlow需要macOS 13.0+支持。
- 兩週試用。兩週免費試用從第一次下載軟件時自動開始。試用到期後軟件會將被鎖住無法使用。
- 即用即付。一個按月付費的訂閱來讓用戶使用軟件。訂閱到期後軟件會將被鎖住無法使用。
- 按年付費，可勁用。一個按月年付費的訂閱來讓用戶使用軟件。訂閱到期後軟件會將被鎖住無法使用。
- 買斷制證書。一次購買，擁有軟件。這個方案之前被命名爲“完整應用”，所以已購買用戶已自動擁有此證書。

6.2.6 - 2024年1月31日
- 支援SQLite version 3.45.1 (2024-01-30).

6.2.5 - 2024年1月20日
- 更新SQLCipher庫版本到4.5.6。

6.2.4 - 2024年1月16日
- JSONB編輯器，支持在數據編輯器和查詢結果中顯示JSONB。
- JSONB編輯器，支持在數據編輯器中以JSON來編輯JSONB。
- 十六進制編輯器，支持拷貝Hex值爲C代碼。
- 支持在導入中使用SQL文件來導入數據。
- 支持SQLite version 3.45.0 (2024-01-15).
- 其它問題修復與穩定性改善。

6.2.3 - 2023年11月29日
- 支援SQLite version 3.44.2 (2023-11-24)。

6.2.2 - 2023年11月22日
- 支援SQLite version 3.44.1 (2023-11-22)。

6.2.0 - 2023年11月4日
- 導出, 新增一個導出類型：List。 List導出類型和sqlite3命令行list輸出模式類似，但是List導出類型會將BLOB數據顯示爲空。在數據編輯器，查詢編輯器和捷徑中執行查詢操作可用。

6.2.0 - 2023年11月4日
- 支援SQLite version 3.44.0 (2023-11-01)。
- 支援導入JSON到表。
- 捷徑。支援導入JSON到表。（如果從JSON文件導入，文件的拓展名不能爲「.json」（因爲捷徑應用的一個bug）。）需要macOS 14.0+支持。
- 表結構，數據編輯器，統計，字體和顏色設置，加載拓展設置。分配給“+”按鈕一個快捷鍵⇧⌘N。分配給“-”按鈕一個快捷鍵⌫ (Delete)。
- 數據庫列表。支持⌥-雙擊表名/視圖名，或者⌥-回車表名/視圖名，來打開表結構/修改視圖結構頁面。
- 訪問模擬器。修復一個可能導致某些模擬器沒有顯示的問題。
- 因爲一些兼容問題此更新可能會重置您的工具欄設置。
- 此版本的SQLiteFlow需要macOS 12.0+支持。

6.1.0 - 2023年10月15日
- 支援SQLite version 3.43.2 (2023-10-10).

6.0.9 - 2023年10月7日
- 問題修復與穩定性改善。

6.0.8 - 2023年9月28日
- 問題修復與穩定性改善。

6.0.7 - 2023年9月17日
- 支持應用重啓時保留已打開的數據庫。您可以到“設置” - “一般”裏來開啓它。
- 其它問題修復與穩定性改善

6.0.6 - 2023年9月12日
- 支援SQLite version 3.43.1 (2023-09-11)。
- 更新SQLCipher庫版本到4.5.5。

6.0.5 - 2023年8月25日
- 支援SQLite version 3.43.0 (2023-08-24)。
- 其它問題修復與穩定性改善。

6.0.4 - 2023年8月21日
- 支持加載SQLite拓展。

6.0.3 - 2023年5月17日
- 支援Version 3.42.0 (2023-05-16)。
- 更新SQLCipher庫版本到4.5.4。

6.0.2 - 2023年4月11日
- 數據庫對比。支持使用主鍵來代替RowID來進行配對對比，現在這個選項默認爲打開。
- 捷徑。執行查詢支持將查詢消息從結果中排除。

6.0.1 - 2023年3月22日
- 支援SQLite version 3.41.2 (2022-03-22)。

6.0.0 - 2023年3月6日
- 問題修復與穩定性改善。

5.9.9 - 2023年3月2日
- 查詢編輯器，支持選擇數據庫來執行查詢。

5.9.8 - 2023年2月25日
- 查詢編輯器。如果有多行被選中，支持Tab鍵來增加每行縮進。
- 查詢編輯器。支持Shift-Tab來減少每行縮進。
- 支援SQLite version 3.41.0 (2023-02-21)。

5.9.6 - 2023年2月14日
- LLDB協作，支持sfopen命令。讓您能夠打開一個從被調試設備拷貝到本地的臨時數據庫。
- LLDB協作，支持sfsave命令。 讓您能夠拷貝一個臨時數據庫（最初被sfopen命令創建）到被調試設備。
在設置-LLDB協作中查看如何安裝這兩個命令。

5.9.3 - 2023年1月28日
- 問題修復與穩定性改善。

5.9.2 - 2023年1月26日
- 數據編輯器，支持顯示16字節BLOB爲UUID字符串。您可以在「設置」 - 「數據編輯器」裏開啓它。

5.9.1 - 2023年1月9日
- 支援SQLite version 3.40.1 (2022-12-28)。
- 其它問題修復與穩定性改善。

5.9.0 - 2022年12月26日
- 更新SQLCipher庫版本到4.5.3。
- 此版本的SQLiteFlow需要macOS 11.0支援。
- 其它問題修復與穩定性改善。

5.8.6 - 2022年11月1日
- 標籤欄標題改進。
- 修復了一個某些時候需要額外按下Shift鍵才能正常工作的快捷鍵問題。
- 支援SQLite version 3.40.0 (2022-11-16).
- 其它問題修復與穩定性改善。

5.8.5 - 2022年10月2日
- 支援SQLite version 3.39.4 (2022-09-29)。

5.8.4 - 2022-09-28
- 支援SQLite version 3.39.3 (2022-09-05)。

5.8.3 - 2022年8月12日
- 支援SQLite version 3.39.2 (2022-07-21)。
- 更新SQLCipher庫版本到4.5.2。

5.8.2 - 2022年7月19日
- 匯入CSV，支援匯入時行列。
- 匯入CSV，如果「第一行為標題行」並且設定了匯入到現存表，如果標題行的欄位順序和表的欄位順序不同，那麼現在已支援正確匯入。
- 匯入CSV，如果「第一行為標題行」並且設定了匯入到現存表，如果標題行的欄位是表字段的子集，那麼現在已支援正確匯入。

5.8.1 - 2022年6月26日
- 新增了一個簡單實用的小工具JSON格式化器作為夏日禮物送給大家。這是這個小工具的第一個版本，您可以通過「主選單-工具」或者「自定義工具欄...」來訪問它。如果您有什麼問題和建議，歡迎來反饋給我們。
- 支援SQLite version 3.39.0 (2022-06-25)。

5.7.4 - 2022年6月11日
- 問題修復與穩定性改善。

5.7.3 - 2022年6月10日
- 問題修復與穩定性改善。

5.7.2 - 2022年6月2日
- 修復一個編輯查詢時可能會閃退的問題。
- 其它問題修復與穩定性改善。

5.7.1 - 2022年5月21日
- 修復通過UI建立新表時會閃退的問題。

5.7.0 - 2022年5月16日
- 極大的提升了資料庫的載入速度。
- 資料編輯器，升級顯示blob為圖片為顯示blob為預覽。這樣blob資料如果可能，不僅可以顯示圖片，還能根據它的內容顯示其它型別的資料，比如影片，pdf等。
- 資料編輯器，支援在檢視中使用過濾來檢視資料。

5.6.9 - 2022年5月7日
- 支援SQLite version 3.38.5 (2022-05-06)。

5.6.8 - 2022年4月28日
- 支援SQLite version 3.38.3 (2022-04-27)。
- 更新SQLCipher庫版本到4.5.1。

5.6.7 - 2022年3月26日
- 支援SQLite version 3.38.2 (2022-03-26)。

5.6.6 - 2022年3月24日
- 問題修復與穩定性改善。

5.6.5 - 2022年3月13日
- 支援SQLite version 3.38.1 (2022-03-12)。

5.6.4 - 2022年2月27日
- 支援SQLite version 3.38.0 (2022-02-22)。

5.6.3 - 2022年1月12日
- 問題修復與穩定性改善。

5.6.2 - 2022年1月6日
- 支援SQLite version 3.37.2 (2022-01-06)。

5.6.1 - 2022年1月5日
- 支援SQLite version 3.37.1 (2021-12-30)。

5.6.0 - 2021年11月29日
- 支援SQLite version 3.37.0 (2021-11-27)。

5.5.0 - 2021年11月26日
- 新增捷徑支援。現在“執行查詢”和“匯入CSV“已經可以在捷徑應用中使用了。
- 其它問題修復與穩定性改善。

5.4.0 - 2021年11月12日
- 更新SQLCipher庫版本到4.5.0。
- 此版本的SQLiteFlow需要macOS 10.15支援。
- 其它問題修復與穩定性改善。

5.3.0 - 2021年9月20日
- 資料庫列表，支援過濾專案時選擇只過濾表或者只過濾表字段。
- 資料庫列表，支援右鍵點選一個欄位名來重新命名欄位。 (需要SQLite 3.25.0+支援)
- 資料編輯器，為文字單元格新增“以文字編輯”右鍵選單專案，使用者可以用它來喚出一個文字編輯器彈窗來編輯單元格內容。
- 匯出資料，支援直接將匯出結果拷貝的剪下板。
- 現在，如果使用者選擇了一個視窗，那麼如果合適的話，在資料庫列表中的專案會根據視窗內容同步被選中。
- 支援訪問蘋果模擬器。這樣使用者在開發他們的App時，就可以更方便地開啟他們App的Documents目錄了。

5.2.4 - 2021年8月23日
- 問題修復與穩定性改善。

5.2.3 - 2021年8月23日
- 問題修復與穩定性改善。

5.2.2 - 2021年8月12日
- 在資料庫列表中支援顯示錶和檢視的數量。

5.2.0 - 2021年6月21日
- 查詢編輯器，支援鍵入回車鍵時執行語法感知縮排。
- 其它問題修復與穩定性改善。

5.1.0 - 2021年6月6日
- 資料庫列表中支援顯示錶欄位資訊。這個資訊現在包括欄位名，欄位型別，非空約束和主鍵約束。
- 支援手動設定淺色/深色模式。

5.0.8 - 2021年6月21日
- 支援SQLite version 3.36.0 (2021-06-18)。

5.0.6 - 2021年5月24日
- 問題修復與穩定性改善。

5.0.5 - 2021年5月21日
- 當軟體語言設定為簡體中文時，查詢編輯器的程式碼自動補全功能支援使用拼音來檢索出對應的表名或欄位。

5.0.4 - 2021年5月17日
- 改進SQL程式碼自動補全功能。

5.0.3 - 2021年5月16日
- 改進SQL程式碼自動補全功能。

5.0.2 - 2021年5月11日
- 改進SQL程式碼自動補全功能。
- 其它問題修復與穩定性改善。

5.0.1 - 2021年5月6日
- 問題修復與穩定性改善。

5.0.0 - 2021年5月4日
- 在資料編輯器的過濾功能中增加了一個「SQL」操作符。
- 支援處理經SQLCipher庫加密的資料庫。
- 其它問題修復與穩定性改善。

4.9.2 - 2021年4月20日
- 問題修復與穩定性改善。

4.9.1 - 2021年4月20日
- 支援SQLite version 3.35.5 (2021-04-19)。

4.9.0 - 2021年3月28日
- 支援SQLite version 3.35.3 (2021-03-26)。
- 查詢編輯器，當用戶選中字串的字首為“SELECT”時，支援右鍵選單建立檢視。
- 資料編輯器，新增漂浮行頭，它讓使用者多一種方式選擇行，並且在這裡選擇行時不會觸發編輯操作。

4.8.4 - 2021年3月14日
- 支援SQLite version 3.35.0 (2021-03-12)。
- 修復了一個可能導致匯出表資料到insert語句時沒有格式化列名的問題。

4.8.3 - 2021年1月24日
- 支援SQLite version 3.34.1 (2021-01-20)。

4.8.2 - 2021年1月10日
- 新增日語支援。

4.8.1 - 2020年12月13日
- 在macOS 11中支援全高度側邊欄。
- 其它問題修復與穩定性改善。

4.8.0 - 2020年12月11日
- 增加Apple Silicon Mac支援。
- 資料編輯器支援拷貝資料為insert/update語句。
- 支援轉儲資料庫到SQL檔案。
- 支援SQLite version 3.34.0 (2020-12-01)。
- 修復了一個在程式閃退後可能導致使用者SQL檔案被移動到程式臨時查詢會話資料夾的問題。
- 其它問題修復與穩定性改善。

4.7.0 - 2020年11月4日
- 極大的提高了資料編輯器和查詢結果的效能，展示列數越多，效果越明顯。
- 此版本的SQLiteFlow需要macOS 10.14支援。
- 其它問題修復與穩定性改善。

4.6.1 - 2020年9月15日
- 修復了一個在全屏模式中可能導致UI顯示不正常的問題。
- 其它問題修復與穩定性改善。

4.6.0 - 2020年9月8日
- 支援匯出資料到JSON。
- 支援匯出資料到Markdown。

4.5.1 - 2020年8月29日
- 問題修復與穩定性改善。

4.5.0 - 2020年8月28日
- 標籤頁行為改動。改動前，關閉視窗的意思是隱藏視窗，所有的標籤頁保持開啟。現在，關閉視窗的意思是關閉這個視窗中的所有標籤頁並且關閉視窗。
- 現在SQLiteFlow使用系統提供的標籤欄來取代之前的標籤欄，以獲得更多系統提供的功能。
- 支援自定義工具欄，並且設計了新的工具欄圖示。
- 改進了查詢編輯器的自動儲存功能。
- 支援SQLite version 3.33.0 (2020-08-14)。
- 其它問題修復與穩定性改善。

4.3.1 - 2020年7月8日
- 為資料編輯器中的過濾器新增「!=」和「不包含」操作符支援。

4.3.0 - 2020年7月3日
- 新建資料庫時支援選擇日誌模式。
- 修改表結構，支援使用拖拽來重新排序表列。
- 修改表結構，支援設定表的WITHOUT ROWID型別。
- 資料庫列表中的表/檢視的右鍵選單支援匯出資料。
- 新增更多觸控欄支援。
- 其它問題修復與穩定性改善。

4.2.0 - 2020年6月28日
- 新增一些基本的觸控欄支援。

4.1.1 - 2020年6月22日
- 支援SQLite 3.32.3 (2020-06-18)。
- 其它問題修復與穩定性改善。

4.1.0 - 2020年6月19日
- 支援選擇使用macOS內嵌SQLite庫，或者選擇使用最新SQLite庫（目前是SQLite 3.32.2）來工作。
- 其它問題修復與穩定性改善。

4.0.1 - 2020年5月25日
- 在開啟資料庫對話方塊中添加了一個「允許選擇所有檔案型別」的選項，來讓使用者能夠在開啟資料庫對話方塊中，開啟擁有自定義拓展名的資料庫。
- 修復偏好設定中「啟用外來鍵約束」和「Tab鍵行為」的值沒有顯示正確的問題。

4.0.0 - 2020年5月22日
- 在資料庫列表中，支援右鍵表名-重命名錶名。
- 格式化查詢，支援選擇偏好縮排字元為空格或者Tabs。
- 格式化查詢，支援設定縮排寬度。現在預設的縮排寬度為4，與預設Tab寬度（同樣為4）相匹配。在之前版本中，這個值無法設定時，預設縮排寬度為3.
- 格式化查詢，支援設定分隔列定義的逗號的風格，可選擇在前或者在尾。
- 文字編輯，支援設定Tab寬度。
- 文字編輯，支援設定Tab鍵行為為插入tab字元或者插入空格。
- 「啟用外來鍵約束」這個設定從資料編輯器移到了「偏好設定」中，所以這個設定現在對資料編輯器，查詢編輯器和匯入CSV都可以生效了。
- 改進修改表結構。
- 匯入/匯出CSV現在支援了使用分號（;）或者tab來作為分隔符去匯入/匯出資料。
- 匯入CSV，修復了一個當CSV文字的最後一行的最後一個值沒有提供時，匯入時無法匯入最後一行的問題。
- 其它問題修復與穩定性改善。

3.8.1 - 2019年8月22日
- 在十六進位制編輯器中將「設定為NULL」改為「設定為NULL並應用」。
- 語法高亮與格式化查詢支援upsert分句和window function以相容未來版本的macOS。
- 其它問題修復與穩定性改善。

3.8.0 - 2019年8月16日
- 內部檢視器，檢視SQLite資料庫檔案，日誌檔案，WAL檔案或者WAL-索引檔案的內部結構。
- 現在資料編輯器編輯資料時，您可以使用Tab鍵來切換列。
- 現在資料編輯器編輯資料時，您可以使用ESC鍵來撤銷對當前值的修改。
- 現在資料編輯器編輯資料時，您可以使用Enter鍵來完成編輯資料, 然後再使用Enter鍵來觸發資料儲存。
- 在資料編輯器中增加了左邊欄來方便您選擇行。
- 在資料編輯器中拷貝資料到CSV中列的順序會根據UI中列的順序變化而變化。
- 在資料編輯器中增加了“匯出”按鈕。您可以選擇“已選行”，“顯示中的行”或者“整個表”，以及是否“包含標題行”來從表/檢視中匯出資料到CSV檔案。
- 在查詢結果中增加了“匯出”按鈕。您可以選擇“已選行”或者“顯示中的行”，以及是否“包含標題行”來從查詢結果或者查詢訊息中匯出資料到CSV檔案。
- 現在在資料庫列表中重新整理資料庫會觸發已開啟的標籤頁一併重新整理。

3.7.0 - 2019年6月28日
- 支援簡體中文、繁體中文。
- 其它問題修復和穩定性更新。

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
