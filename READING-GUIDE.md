# 讀者指南

TXT的〔unit:…〕標籤、分隔與換行是現代導航，不是古籍新增標點。引用記版本及unit ID，再依f01的canvas/image_url核原圖。

疑讀見uncertainties.json，與TXT／TEI一同保留。本版零筆疑讀只表示沒有明列的疑讀，並非零錯誤保證。TEI是固定JSON的最小投影，body/ab保留精確字串；不虛構逐字座標、TextLine或完整校勘apparatus。

小註實際附著位置見book.methods.approved_page_notes，依主欄unit、字串anchor及Unicode碼點插入位置閱讀，不把陣列順序誤當小註在欄末。TEI declared-methods保存同值；TXT配合JSON旁附資料閱讀。

VALIDATION.json列已實跑的JSON、TXT、TEI RelaxNG與CFF檢查；未做ODD、Schematron或人類全文二校。

AI初錄，尚未套用獨立讀字。未經人類全文雙校、專家審定或同儕審查，未量測準確率。格式與hash通過不證明讀字正確；實際原生模型、effort、token未回報，維持null。

本包不含來源影像、裁片、專用程式、提示、完整內部工作與盤點紀錄；未提供從原圖完整重跑的方法。
