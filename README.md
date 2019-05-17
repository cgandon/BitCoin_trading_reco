BITCOIN TRADING

Project was created as part of my DataScience Full Time Class taken at Jedha in Paris, August 2019, as a practical application of what i've learned during this class.

**Objective:**
Apply machine learning to supporting trading decision. Leveraging on BTC market prices and volumes informations, I will try and identify markets "lows" and "highs" to trigger automated short term investments (few minutes to few hours between buy and sell). Volatility of BTC makes this type of trading possible and profitable in spite of transaction fees.

**Approach:**
Collected trading data from binance minute per minute from December 2018 to April 2019.
Data collection and preparation is available in Jupyter notebooks.
A deeplearning engine mostly leveraging on LSTM is setup and trained on data from December2018 to March2019, then tested on April data.

**First results after a week of work:**
They are encourageing, and show that the reco engine, if productive, would have allowed to nearly double gains on this period (vs organic progression of the market). It needs to be further tested and improved, and i'm currently following these clues:
- add sentiment from tweeter/news feed and combine with a more mid-term trend to give a better context to low/high predictions
- add trends from other market places (BTC and others..)  since they probably have interdependancies that would help fine tune predictions
- test the app in a "descending" market. April was generous and BTC naturally grew nearly 7%. Even through first test concluded on a 12% growth (beating market by 5 points!) it certainly needs to be tested in more difficult conditions. As traders say: anyone can make money when stock goes up, but only the best make money when it goes down.
