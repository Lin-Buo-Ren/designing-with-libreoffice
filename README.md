# designing-with-libreoffice
## 專案目標
簡單說，就是把 Designing with LibreOffice 這本書翻譯成中文版，並且針對 5.4 時下最新版本重製。等待完成後，再改版為 6.0 版。

## 實現方式
* OmegaT 4.1.2_beta2 翻譯輔助工具 https://sourceforge.net/projects/omegat/files/OmegaT%20-%20Latest/OmegaT%204.1.2%20update%202/
* GitHub 協作

### OmegaT 用法
參見 https://libreo-zht.blogspot.tw/2017/12/omegat-4-github-designing-with.html

## 協作方式
1. 開 Issue 認養章節
2. 利用 OmegaT 4.1.2_beta2 協作翻譯該章節
3. 完成翻譯後開另一 Issue 提請他人校對
4. 校對後關閉兩則 Issue（翻譯的 Issue 至少要經過一次校對才能關閉）

## 翻譯步驟
第一階段：翻譯
1. 各章節翻譯
2. 每章節完成找親朋好友閱讀並校對
3. 完成所有章節

第二階段：改作
1. 加入中文版對應要有的內容，例如中文的自由字型、中文的文字排印學，並且改作為符合 5.4 時下最新版（翻譯採最新修正後術語）
2. 四處找人閱讀校對
3. 正式發表
4. 改作為符合 6.0 版

## 翻譯階段
已完成的有：
第一章至第四章、第十六章、附錄A、附錄B、附錄C、附錄D

翻譯中的有：
第五章 (Cheng-Chia Tseng)、第六章（Mark Hung）、第七章 (Vdragon)、第十三章 (Jeff Huang)、第十五章（Franklin Weng）

校對中的有：
第十二章（未）、第十四章 (Cheng-Chia Tseng)

未處理的有：
第八章至第十一章

## 改作階段
尚未進入此階段

## 備註
1. LibreOffice 會自動補中英之間的排版空間，所以翻譯 odt 檔時不必中英間補空格。
2. 選單表示法為：「檔案 > 另存新檔」。
3. 記得到主視窗下方的「譯者注記」標籤頁，點按譯者注記方塊右上角設定用齒輪圖示，並勾選「分節有譯者注記時通知我」，可方便瞭解其他譯者留下的想法，自己也可以寫一些注記。
4. 給專案管理員：如果 merge 了外部 repo 的 pull reqeust，可能導致這邊的 OmegaT 無法繼續同步。解決方案是砍掉資料夾，重新用 OmegaT 下載協作專案回來 (等同重新 git clone) 就行了。
5. [關於明顯無意義的格式標籤的處置方式？](https://github.com/l10n-tw/designing-with-libreoffice/issues/18)
