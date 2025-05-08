# supreme-carnival
# **This and that with Python**

**More Parks, Please!** 

![OSM_EU_capitals_parks](https://github.com/user-attachments/assets/778055e6-b563-46c7-be6a-42cf3828bae0)

**Merry Christmas!** (Drawn with Python)

![xmas_card](https://github.com/user-attachments/assets/201c43cd-3e61-4d8e-b528-a13c1fb43246)

**Icebergs**

![icebergs_2021](https://github.com/user-attachments/assets/84d4d14b-7222-46f5-a8ec-bd5fac2dc360)

**Rat Sightings in NYC**

![oh_rats](https://github.com/DevJupyHUB/supreme-carnival/assets/125738232/2fa6eea0-c73b-47ff-89cb-18012e957901)

[Gen AI](https://github.com/DevJupyHUB/supreme-carnival/blob/main/code/GEN_AI.ipynb)

<img src="/plots/gen_ai.png" width="75%"/>

[Stocks](https://github.com/DevJupyHUB/bookish-octo-doodle/blob/main/code/2025-04-29.ipynb)

<img src="/plots/stock_prices.png" width="75%"/>

-------------------------------------------------------------------------------------------------------------------

[Diplomatic missions of Portugal](https://github.com/DevJupyHUB/supreme-carnival/blob/main/code/diplomatic-missions-of-portugal.ipynb)

**Goal:**

To look at what type of portuguese diplomatic missions are in the world and where these missions are located.

**Method:**

The list of diplomatic missions is scraped from Wikipedia using pandas the read_html() method. After that a thorough data cleaning took place. The cleaned data was joined with a country codes dataset from Kaggle. Finally, the data was visualized by using a waffle chart and two coropleth map charts.


![image](https://github.com/DevJupyHUB/supreme-carnival/assets/125738232/8d1e3e75-72d5-4e21-bff9-7a023d1969dd)

![image](https://github.com/DevJupyHUB/supreme-carnival/assets/125738232/4515d0ea-c30d-443a-b2c2-1991888900a5)

![image](https://github.com/DevJupyHUB/supreme-carnival/assets/125738232/8e8d90e1-cdd2-467f-9f1e-2d33859338bf)


-----------------------------------------------------------------------------------------------------

[Predicting US tornados' magnitude](https://github.com/DevJupyHUB/supreme-carnival/blob/main/code/us-tornados.ipynb)

**Goal:**

The main goal is to explore the US Tornado data by performing exploratory data analysis and try to predict tornado magnitude by building machine learning models. It is a multi-class classification problem where balaced accuray is seelected as metric.

**Data:**

The data is from NOAA and can be found on [Kaggle](https://www.kaggle.com/datasets/sujaykapadnis/tornados).

**Summary:**

Tornados occur in all US states but the most of them occure atthe middle and at the east states. The number of tornado occurencies seems to be increasing over time but further analysis relvealed that only the number weak tornados shows a strong upward trend while the number of strong tornados doesn't seem to change. Most tornados likley tend to occure in May and June. They happen at any time but most of them seem to occure at afternoon and evening hours. Texas is the most heavily hit by tornados comparing to other states but the most devastating tornados occur in Oklahoma. It is observed that the more powerful the tornado, the longer and wider its path but most tornadoes are neither long nor wide, big and powerful tornadoes are rare. 2011 was oustanding in terms of injuries, fatalities and loss in USD and Texas, Alabama and Oklahoma states suffered the most.

![image](https://github.com/DevJupyHUB/supreme-carnival/assets/125738232/3b09568f-0c1a-403f-983f-2c7102513859)

The Random Forest model performed the best comparing to the other models, however, the selected metric of balanaced accuracy improved only about by 0.003619 comparing to Decision Tree cv and by 0.039984 comparing to the baseline Decision Tree model.

![image](https://github.com/DevJupyHUB/supreme-carnival/assets/125738232/37e16eee-1e6b-4573-b8dd-45ff85b9743b)

Neither of these model worked satisfactorily as the selected metric of balanced accuracy remained under 0.5. Future work should consider other techniques for handling imbalanced data, including over and/or under sampling techniques and more hyperparameter tuning.

