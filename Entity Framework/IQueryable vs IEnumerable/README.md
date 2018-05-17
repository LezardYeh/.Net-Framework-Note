# IQueryable
- 處理遠端的資料(ex. Database)
- IQueryable實作IEnumerable
- 通常由資料庫廠商進行實作，讓開發者可以透過LINQ語句來產生SQL Command
- IQueryable原則上不會立即觸發與DB的溝通，而是將Query Expression儲存起來，並可重新組合利用,透過Query Provider轉成SQL語法取得結果
- Linq to Entity

#IEnumerable
- 處理記憶體內的資料(ex. Array)
- 屬於應用程式端的物件，在記憶體中運行各種查詢邏輯- 
- Linq to Object

