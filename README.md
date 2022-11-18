# Daily_Forecast

  在基于该预测结果的交易策略中，2022年初至2022年11月18日的累计收益超过了46%，相对沪深300指数超额收益达到了70%，最大回撤24%，最大超额回撤15%，回测周期内投资组合平均每日换手率52%。
  
  文件说明：CSV中的排名，即为AI量化模型对所有个股Label值归一化后的排名结果。其Label预测的标的，为文件夹的名字（如T+2收盘价比T+1收盘价）。其中文件日期为T+1日（即次日），更新当日为T日。对于Label值本身(CSV第二列的数据)，您可以忽视它，预测只需参考每个文件中的个股排名即可。
  
  选股说明：最终的胜率和收益，完全取决于您的交易策略。即便您选择了预测排名靠前的股票，但是仓位不多（小于5支），风险是极大的。经过系统回测，投资组合仓位在15支（及以上）是较为稳重的选择。

  对于所有排名靠前的 次新股、涨停票、以及ST票的预测，请慎重参考，在我个人的交易策略中，是剔除了这些票的。

  长线（趋势）预测的准确率和有效性相对短线来说要更高些。对于包含开盘价信息的预测，IC值相对收盘预测是要低的，所以参考价值也有限。

  结果仅供参考！
  
  
  In the trading strategy based on this forecast result, the cumulative return from the 20220104 to 20221118 exceeded 46%, and the excess return relative to the CSI300 reached 70%.The maximum retracement is 24%, the maximum excess retracement is 15%, and the average daily turnover rate of the investment portfolio within the backtest period is 52%.
  
  Result parameter description: The ranking in the CSV file is the ranking result after the AI quantitative model normalizes the Label values of all individual stocks. The target of its Label prediction is the name of the folder (such as the closing price of T+2 divide by the closing price of T+1).The file date is T+1 day (that is, the next day), and the update date is T day.For the Label value itself(Data in the second column of CSV), you can ignore it, and the prediction only needs to refer to the stock ranking in each file.
  
 Stock selection instructions: The final winning rate and profit depend entirely on your trading strategy. Even if you choose a stock with a high forecast ranking, but the position is not large (less than 5 stocks), the risk is extremely high. After systematic backtesting, a portfolio position of 15 stocks (and above) is a more prudent choice.
  
 Please carefully refer to all the top-ranked sub-new stocks and forecasts of daily limit tickets.  
  
  Long-term (trend) forecasts are much more effective than short-term forecasts. For predictions that contain opening price information, the information ratio is very low, so the validity and accuracy are low relative to closing price information.
  
  This is for your reference only!
