# bitcoin_trade_info
需要在input_data中输入private_Key和public_Key,然后运行input_data.py
目标是用机器学习自动交易okex的bitcoin季度和周的期货合约进行套利。
1. 按照时间30秒间隔抓取OKEX，huobi_USDT,bfx上现货价格。
2. 用skleran进行机器学习找出最佳策略最大化收益。
3. 用okex API进行自动交易。

代码尚未完成并会不断进行完善
