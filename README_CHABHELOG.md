## CHABGELOG
* 2024.10.29 調整 cheerio 套件的問題，詳見此[issue](https://github.com/Messiahhh/wenku8-downloader/issues/20)
* 2024.11.04 修正標題半形問題。章節標題如果有半形符號，則會在儲存檔案時出現問題。

## 等待解決的問題
* 下載圖片時常會失敗(已試過stream、Buffer都無法成功)(目前推測問題點在於，圖片的伺服器本身不穩，導致取資料途中會被中斷)

## note
使用下載為 EPUB 檔案的功能時，檔案內圖片為超連結
而下載圖片時，目前沒有方法可以成功下載
下載 EPUB 檔案推薦使用[這個網站](https://github.com/ShqWW/lightnovel-download?tab=readme-ov-file)