# 從上市高價股資料剔除 KY 股

> 透過 Series.str.contains 方法。

點擊圖示啟動專案 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/datainpoint/project-getting-rid-of-ky/HEAD?filepath=project-getting-rid-of-ky.ipynb)

## 標籤

- 獲取載入
- 整併轉換

## TL; DR

在這個專案中我們打算實作「財務自由的世界」所提及十二道選股流程中的前兩道擇股機制：

1. 股價前一百名的上市公司。
2. 剔除在開曼群島註冊的 KY 股。