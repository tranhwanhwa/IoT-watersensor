這是一個利用LoRa無線傳輸技術實現遠距無線傳輸的淹水感測系統。

感測模組部分使用Linkit 7697做為開發板，並連接KSM038 水位高度感測器，用來觀察淹水情況，最後透過LoRaWAN Module將資料發送至LoRaWAN Gateway。

我們使用node-red來管理後台，除了資料過濾與資料庫的管理，也使用node-red建立Http服務端點，來顯示簡易的視覺化網頁，供使用者查詢該處的淹水狀況。
