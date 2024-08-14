## 一、專案主題: 台灣長照場域供需的歸納與分析
### 二、專案小組人員: 陳明勝、孫義翔、林重仰
### 三、專案網址:https://github.com/Ian092/Ian.git

### 四、預期目的:
1.本研究期待能夠透過研究長照機構和相關變數之間的關聯性，分析地區的供給和差異，以利政府及民間投資到需求較強的區域，提高整體國家的資源效益。

2.利用決策樹模型觀察哪些特徵值（例如人口老齡化程度、地區經濟狀況、醫療資源可及性等）對於預測長照機構數最為重要。
  了解哪些因素在影響長照機構數方面起到了關鍵作用，並預測未來數量成長或消退的趨勢。

### 五、研究方法:
1.分析長照場域的供需現狀：
  皮爾森相關係數（Pearson correlation coefficient）
  通過統計與數據分析比對長照機構數與多種變數之間的相關性，瞭解不同地區的長照需求與供應狀況。

2.預測未來長照機構需求：
  決策樹回歸模型(Decision Tree Regressor)
  分析影響機構數的因素（例如，老年人口數、老年化、就業人口等），預測未來長照機構數在各地區的數量變化和趨勢。


### 六、資料來源:
衛福部長照專區： https://1966.gov.tw/LTC/mp-207.html

政府開放平台： https://data.gov.tw/

行政院全球資訊網：https://www.gender.ey.gov.tw/gecdb/Stat_Statistics_Field.aspx

中華民國內政部戶政司全球資訊網： https://www.ris.gov.tw/app/portal/346

國發會人口推估查詢系統： https://pop-proj.ndc.gov.tw/

中華民國統計資訊網： https://www.stat.gov.tw/cl.aspx?n=2959

高齡醫學暨健康福祉研究中心： https://ageing.nhri.edu.tw/annual_report/

Taiwan Clinical Trials： https://www.taiwanclinicaltrials.tw/tw

用數據看台灣： https://www.taiwanstat.com/realtime/

行政院主計處： https://www.dgbas.gov.tw/


### 七、資料格式:
年度資料csv檔案
顯示資料類型包含:
地區 | 地區人口數 | 老年人口數 | 長照需求人數 | 老化指數 | 扶老比 |  | 就業人口 | 薪資中位數 | 醫療院所數 | 照服人力 | 長照機構數


### 八、視窗主程式：
#### [main.py](https://github.com/Ian092/Ian/blob/main/LTC_project/main.py)
#### [data_analysis.py](https://github.com/Ian092/Ian/blob/main/LTC_project/main.py)

![統計資料](LTC_project\image\LTC_Project_01.png)

![各地區長照機構數和長照需求人數](LTC_project\image\LTC_Project_02.png)

![變數盒鬚圖](LTC_project\image\LTC_Project_03.png)

![相關係數熱力圖](LTC_project\image\LTC_Project_04.png)

![決策樹](LTC_project\image\LTC_Project_05.png)