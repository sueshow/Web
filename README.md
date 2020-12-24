# 網站的基本架構

## 前端 Front-End (介面)
* 如同 Shiny 中的 ui.R 
* 程式語言：
  * Html：超文件標籤語言 (HyperText Markup Language)，用來描述網站的架構、資訊
  * CSS：層疊樣式表 (Cascading Style Sheets)，用來控制網站顯示的樣式
  * JavaScript (JS)：用來處理網站上需要邏輯判斷的功能，如動態網站、處理網頁上所有動作、或是更細節的動畫
<br>

## 後端 Back-End (商業邏輯處理)
* 如同 Shiny 中的 server.R 
* 程式語言：
  * PHP：最普遍，易學，範例：Facebook、Wordpress
  * Java：應用層面廣，開發較慢，範例：Linkedin、Amazon
  * Python：語法易學，數據分析與資料探勘應用多，單獨使用運行性能較差，範例：Instagram、Reddit
  * Ruby：開發快速，範例：Airbnb、Twitter
  * JavaScript (Node.js)：高病發的情況執行效率極高，不適合 CPU 密集應用，範例：Yahoo、Walmart、阿里巴巴
  * Go：有很完善的標準庫，效能佳，速度快，學習資源少，範例：Google、Youtube
* 特性：把關資料的安全性 (第二道防線)
* 靜態網站 (Static Website)：網頁伺服器 (Web Server)
  * 特性：靜態檔案，不涉及資料庫
  * 可視需求安裝 DB Server
* 動態網站 (Dynamic WebSite)：應用程式伺服器 (application server；AP Server)
  * 特性：
    * 提供商業邏輯服務、與前端串接的入口/介面、系統間互相串連
    * 能儲存使用者互動的資訊，依使用者回資料庫拉對應資料塞回網頁顯示
  * 為了與外界串接 (提供服務)，需要使用指定網路傳輸協定 (Communications Protocol)，兩個串接的系統才能有同樣的二元資料 (0/1) 解讀規則。常見的如：http(s)、websocket、ftp(s)...等
<br>

## 網站架構
* 後端三層式架構：Web Server → Web API(提供服務) → DB Server
* 架構：前端語言 → 瀏覽器 (chrome/firefox) → 伺服器 (apache/nginx/IIS) → 後端語言 → 資料庫 (DB)
<br>  

## 參考資料
* [網頁新手入門：初探網頁架構和前後端語言](https://medium.com/appworks-school/%E7%B6%B2%E9%A0%81%E6%96%B0%E6%89%8B%E5%85%A5%E9%96%80-%E5%88%9D%E6%8E%A2%E7%B6%B2%E9%A0%81%E6%9E%B6%E6%A7%8B%E5%92%8C%E5%89%8D%E5%BE%8C%E7%AB%AF%E8%AA%9E%E8%A8%80-a88a5dc86ee3)
* [PM筆記：前端與後端、基本網站架構](https://medium.com/%E4%B8%80%E5%80%8B%E4%BA%BA%E7%9A%84%E6%96%87%E8%97%9D%E5%BE%A9%E8%88%88/pm%E7%AD%86%E8%A8%98-%E5%89%8D%E7%AB%AF%E8%88%87%E5%BE%8C%E7%AB%AF-%E5%9F%BA%E6%9C%AC%E7%B6%B2%E7%AB%99%E6%9E%B6%E6%A7%8B-a679cd7a7bfc)
* [開始玩轉後端](https://ithelp.ithome.com.tw/articles/10200476)
<br>
