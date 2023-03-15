# 台灣影響大學生轉學考成功考上之因素

## 簡介
+ 資料時間：2018年
+ 資料來源：連振宇、高莉、盧海新
+ 原始問卷：https://forms.gle/SgTPFqFzJGNsJRYr8

## 資料說明
+ 編碼方式： `unicode_escape`
詳見`Coding Table.pdf`

## 資料讀取
```python
import pandas as pd
URL = r"https://github.com/Keycatowo/dataset/raw/main/001-%E5%8F%B0%E7%81%A3%E5%BD%B1%E9%9F%BF%E5%A4%A7%E5%AD%B8%E7%94%9F%E8%BD%89%E5%AD%B8%E8%80%83%E6%88%90%E5%8A%9F%E8%80%83%E4%B8%8A%E4%B9%8B%E5%9B%A0%E7%B4%A0/transfer_data.csv"
df = pd.read_csv(URL, encoding= 'unicode_escape')
```