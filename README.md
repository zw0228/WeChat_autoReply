# Wechat_autoReply
软件工程作业
1.【WeChat_autoReply】 其中WeChat_autoReply文件夹中主程序是weChat.py，其余.py文件均是做的查快递、天气、火车、机票的爬虫。 weChat.py利用itchat库实现了自动回复，集成了添加的几个爬虫后可以做到查快递、天气、火车、机票（玩法详见weChat.py）
2.【WeChat_autoReply】中的cityWeather中是所有城市对应的城市代码，执行SQL即可直接把SQL表和数据一并建好。全国城市和代码都有了，我们查某个城市的天气，只需要输入城市，就可以从mysql里获取对应的城市代码如：101020100，然后构造相应的url：http://www.weather.com.cn/weather/101190101.shtml
就可以查看到对应城市的7天天气了。
