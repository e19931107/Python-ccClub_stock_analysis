# ccClub 2023 Fall Python 讀書會 Proposal
# 主題: 分析股票基本面，並挑出可投資之標的

## Members:
0045黃俐聞
0200俞筱柔
0206陳冠今
0366賴芃君

## Outline:
1. 目標：利用Python爬取公開資訊觀測站的每支股票之營收、ROE、利潤等資訊，並且使用Pandas套件進行資料彙整
2. 讓使用者可以選擇自己有興趣的產業來做投資，或是根據我們所設定之條件自動推薦股票

## Week1:
使用爬蟲套件（BeautifulSoup, Requests），來爬取公開資訊觀測站(https://mops.twse.com.tw/mops/web/index)股票之基本訊息，在JupyterBook上存成DataFrame的形式。
可能要克服的問題：有些欄位是網站沒有提供的，我們需要自己找到資料的定義並用現有資料去做計算。

## Week2:
將爬取下來的資料清理(data cleaning)，並將資產負債表和綜合損益表join在一起
分成兩部分，一個是使用者自行選取產業，一個是電腦推薦可投資之股票
使用者自行選取產業：
列出產業別，使用者輸入產業別後回傳在此產業當中之股票與ROE
電腦推薦可投資之股票：
運用營收YOY, 利潤YOY和EPS為負來篩選股票，並用營收成長率排序
可能要克服的問題：
1. ROE網站並無提供，需要自行計算
2. 使用者自行選取部分只有顯示出ROE，可能需要再更多指標

## Week3:
統整前面的資料，並結合linebot

## Week4:
預留一週緩衝

## Reference:
1. 行銷搬進大程式
https://www.youtube.com/@marketingliveincode

2. Python Pandas 資料分析 - 基礎教學 By 彭彭
https://www.youtube.com/watch?v=5QZqzKCDCQ4

## 企劃書:
https://docs.google.com/presentation/d/1m99mGraNMIVnai1Qepd4Md44LRycaILSr8MV6HTp5WU/edit#slide=id.g27623d9826f_1_0

[ccClub Final.pdf](https://github.com/e19931107/Python-ccClub_stock_analysis/files/14051487/ccClub.Final.pdf)

![ccClub Final_pages-to-jpg-0001](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/5836d19b-046e-4545-b301-25bc047c594e)

![ccClub Final_pages-to-jpg-0002](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/d0bfc38d-e43c-4ff4-b032-b15addae4855)

![ccClub Final_pages-to-jpg-0003](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/5017eb4a-13c5-4f51-8327-9319fc8ce25b)

![ccClub Final_pages-to-jpg-0004](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/3a30f1bc-94e3-4e91-b004-94cad46acb9c)

![ccClub Final_pages-to-jpg-0005](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/db06c96b-5688-43f3-b5af-46c53bb2fc1e)

![ccClub Final_pages-to-jpg-0006](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/b53ea076-0e37-4e68-ac0c-3d61320d710f)

![ccClub Final_pages-to-jpg-0007](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/8dcfd72b-f83d-4531-b55a-18cda9c5334b)

![ccClub Final_pages-to-jpg-0008](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/f8b979f1-1efe-4899-a2c6-7e220b61c83e)

![ccClub Final_pages-to-jpg-0009](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/e5b4fed7-0c5e-4e38-9525-c5f70d92d944)

![ccClub Final_pages-to-jpg-0010](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/8f5448d3-67e9-4399-b92f-3e01b259c948)

![ccClub Final_pages-to-jpg-0011](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/660c9fc5-876a-40fe-b9cc-deda5005f10d)

![ccClub Final_pages-to-jpg-0012](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/d43bb0ce-479c-4877-b2cc-abe78bb18680)

![ccClub Final_pages-to-jpg-0013](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/df0ebfe8-cd7d-4052-9f46-bc95f14f5956)

![ccClub Final_pages-to-jpg-0014](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/ff0152bd-bbb6-4012-b4a8-6f6a756f1bdf)

![ccClub Final_pages-to-jpg-0015](https://github.com/e19931107/Python-ccClub_stock_analysis/assets/50692450/45bec6e2-1835-410d-bd26-1f81a3149b23)

Video:
https://youtu.be/xS6sOURHsyY
