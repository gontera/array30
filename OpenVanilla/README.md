# 行列輸入法 array30 for OpenVanilla
OpenVanilla 是專為 macOS 平台開發的第三方輸入法軟體框架。本頁面提供的輸入法鍵碼表（.cin 檔案），係特別為 OpenVanilla 製作及調整。如欲尋求 OpenVanilla 相關支援，請參見其官網 https://openvanilla.org/ 。

檔案說明：
* array-shortcode.cin：行列一、二級簡碼。
* array-special.cin：行列特別碼。
* array30-OpenVanilla-big.cin：行列 30 鍵版鍵碼表。

版本更新歷程：
* 2023-02-11 版本 v2023-1.0，依據行列30 v2023 新校訂編碼製作。
* 2022-03-17 版本 0.94，修正 https://github.com/gontera/array30/issues/4 暨增補 Ext-C 字面漏編的「𫊖」字。
* 2021-08-04 版本 0.93，修正 https://github.com/gontera/array30/issues/3 暨刪除部分重複收編的漢字，感謝 Terry Tsang 回報。
* 2021-07-23 版本 0.90，新增 CJK Ext-G，並補足原本 Unicode 13.0 中未定義於 CJK Ext-A/B/C/D/E/F/G 中的漢字。
* 2018-04-24 版本 0.86，新增支援 CJK Ext-F。
* 2016-03-19 版本 0.80，新增支援 CJK Ext-E，並依據行列輸入法官網發布之 CJK Ext-B V2016A 版對照表，修正 Ext-B 的部分鍵碼。
* 2015-09-16 版本 0.75，配合行列官網釋出的特別碼版本 V201509，更新特別碼。
* 2014-05-20 版本 0.71，更新 CJK Ext-C/D，相容於行列 2013A 官版對照表。
* 2012-12-01 版本 0.70，支援 CJK Ext-C/D，相容於行列 2012A 官版對照表。
* 2011-08-21 版本 0.60，依照行列輸入法官網發布的 2008A 版對照表重新定義特別碼，並更正一、二級簡碼。
* 2011-05-15 版本 0.53，重新定義 w+8 順序（數字）符號組。
* 2008-10-27 版本 0.52，依行列科技廖明德先生提供之最新對照檔，再製新版。
* 2007-09-25 將 big5 字集定義【粧銹恒碁墻嫺裏】共七個特殊用字，自 cin 檔移除，避免這些字在 unicode 選字窗中重複出現。
* 2005-05-11 配合 OpenVanilla 0.7 將一級簡碼自本檔移除，另獨立至 ArrayShortCode.cin 中。
