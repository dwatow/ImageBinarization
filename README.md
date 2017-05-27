# ImageBinarization
用Javascript寫二值化的影像處理演算法

## 執行注意事項(Usage)

### 啟動
其中，`getImageData`語法，無法用瀏覽器透過`file://`讀取，所以在此建議使用[python的簡易web server](https://darkblack02.blogspot.tw/2017/04/blog-post.html)
即可透過`localhost:8000`(預設用8000)成功取得影像資料。

### 換圖片
程式中的路徑，預設在`index.html`同層目錄的圖片檔。
直接在網頁上，貼上檔名，會立即執行演算法。(建議用ctrl+v貼上)

### 改變二值化閥值
直接在網頁上，改變預設值，會立即執行演算法。
