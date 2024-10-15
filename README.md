# 新聞爬蟲斷詞練習
從Google News頭條新聞將新聞標題及內文使用爬蟲獲取資料，並將內文斷詞後儲存起來。

輸出結果:
- newslist.txt 包含檔案id/網址/新聞來源/新聞標題
- 新聞檔案(id.txt) 包含斷詞後的新聞內容

##使用方式
###  建立虛擬環境使用python3.9

`conda create -n news python=3.9`

### 安裝套件

`pip install beautifulsoup4`
`pip install requests`
`pip install pandas`

在news.ipynb的當前資料夾創建一個名字為output的資料夾
打開news.ipynb 逐步執行皆可
