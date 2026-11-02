# 資料字典

book.json為固定公開主本。pages[]僅f01；physical_page_id若有p01只是現代定位，並非原刻頁碼。units[]的id定位、layer=original-print、role保存實見文字角色、text為原字串、side=recto；陣列順序等於固定稿order。

methods.fixed_metadata與page_metadata保存允許公開的原稿metadata；approved_unit_coordinates保存原稿bbox（null或3336×4000原圖像素框[x0,y0,x1,y1]）。public unit.bbox固定null，未造逐字框。來源頁面尺寸與manifest尺寸不同，座標不得互用。

methods.approved_page_notes完整保存page.notes：主欄與unit映射、小註所附主欄、字串anchor、0起Unicode碼點插入位置及小字內部讀序；小註列於主欄後不表示位於欄末。TEI declared-methods保存同值。總註記採核定高層說明，不公開私有盤點檔名。

uncertainties採unit_id及Unicode碼點0起半開[start,end)，surface等於text[start:end]。target的候選及理由不替換正文。□是有定位理由的未定暫記，不能據此當一字缺損數；尚未處理區不得作已完成疑字。

methods.uncertainty_explicit_start記原稿是否明給start，供無損回讀。methods不含source-only、盤點、trace、私有活動或原稿worker；公開投影不是完整私檔bytes。

1幅官方recto、1目標物理面、38個原印文字單位、669個Unicode碼點、7筆定位疑讀、0個□。碼點數不是漢字數，疑讀數不是錯誤率。
