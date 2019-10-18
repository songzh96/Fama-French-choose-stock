Thank you @SapiensSuwan， Let me check the code so that it can be used by others for reference
# Fama-French-choose-stock
基于Python3环境下设计的,请使用python3环境编译<br />
样本数据采集自网易财经，采用的是上证50板块<br />
Fama.py是主要计算脚本<br />
其他皆为获取数据的脚本<br />
分别是获取股票股本，股票收盘价，股票净资产<br />
需要搭建数据库，数据表的设计可以参考代码中字段<br />
语言：python3.6<br />
需要安装的库：numpy，pandas，stats models等，如果程序报错缺少模块，安装模块再重新编译（可在代码中查看）<br />
代码中有注释，可自行研究或做参考。<br />
自己对Fama-French的见解,[利用Fama-French三因子模型对中国A股市场锂电池板块的研究（基于聚宽平台）](https://www.jianshu.com/p/680ef46faaad)

# Fama-French-choose-stock how to use
1. 创建一个数据库环境（Mysql）
2. 创建一个数据库，名字叫testdata。
3. 导入testdata.sql
4. 运行Fama.py
5. 报错的话，根据错误自己解决，也可以提issue。
