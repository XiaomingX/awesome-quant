# awesome-quant

A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance)

## Python

### 数值库与数据结构

- [numpy](https://www.numpy.org) - NumPy是Python科学计算的基础库。
- [scipy](https://www.scipy.org) - SciPy是一个基于Python的开源数学、科学和工程软件生态系统。
- [pandas](https://pandas.pydata.org) - pandas是一个开源库，提供高性能、易用的数据结构和数据分析工具。
- [polars](https://docs.pola.rs/) - Polars是一个非常快速的DataFrame库，用于处理结构化数据。
- [quantdsl](https://github.com/johnbywater/quantdsl) - 金融和交易中的定量分析领域专用语言。
- [statistics](https://docs.python.org/3/library/statistics.html) - Python内置库，提供基本统计计算功能。
- [sympy](https://www.sympy.org/) - SymPy是一个Python符号数学库。
- [pymc3](https://docs.pymc.io/) - Python中的概率编程：贝叶斯建模和概率机器学习，基于Theano。
- [modelx](https://docs.modelx.io/) - 将电子表格重新定义为面向公式的对象，兼容pandas。
- [ArcticDB](https://github.com/man-group/ArcticDB) - 高性能的时间序列和tick数据存储库。

### 金融工具与定价

- [OpenBB Terminal](https://github.com/OpenBB-finance/OpenBBTerminal) - 面向所有人的投资研究终端。
- [Fincept Terminal](https://github.com/Fincept-Corporation/FinceptTerminal) - 用于各种金融资产研究的高级AI数据终端。
- [PyQL](https://github.com/enthought/pyql) - QuantLib的Python端口。
- [pyfin](https://github.com/opendoor-labs/pyfin) - 基础期权定价库（已归档）。
- [vollib](https://github.com/vollib/vollib) - 一个用于计算期权价格、隐含波动率和希腊字母的Python库。
- [QuantPy](https://github.com/jsmidt/QuantPy) - 一个Python定量金融框架。
- [Finance-Python](https://github.com/alpha-miner/Finance-Python) - Python金融工具。
- [ffn](https://github.com/pmorissette/ffn) - 用于金融分析的Python函数库。
- [pynance](https://github.com/GriffinAustin/pynance) - 轻量级Python库，用于汇总和分析金融数据。
- [tia](https://github.com/bpsmith/tia) - 集成与分析工具包。
- [hasura/base-python-dash](https://platform.hasura.io/hub/projects/hasura/base-python-dash) - 快速部署Dash框架的Hasura启动项目，适合用Python构建高度自定义的数据可视化应用。
- [hasura/base-python-bokeh](https://platform.hasura.io/hub/projects/hasura/base-python-bokeh) - 用于数据可视化的bokeh库快速启动项目。
- [pysabr](https://github.com/ynouri/pysabr) - SABR模型的Python实现。
- [FinancePy](https://github.com/domokane/FinancePy) - 专注于金融衍生品定价与风险管理的Python库。
- [gs-quant](https://github.com/goldmansachs/gs-quant) - 高盛的Python定量金融工具包。
- [willowtree](https://github.com/federicomariamassari/willowtree) - 一个稳健且灵活的Python实现，用于衍生品定价的willow tree格子模型。
- [financial-engineering](https://github.com/federicomariamassari/financial-engineering) - 使用蒙特卡罗方法进行金融工程项目的应用。
- [optlib](https://github.com/dbrojas/optlib) - 用于金融期权定价的Python库。
- [tf-quant-finance](https://github.com/google/tf-quant-finance) - 基于TensorFlow的高性能定量金融库。
- [Q-Fin](https://github.com/RomanMichaelPaolucci/Q-Fin) - 一个用于数学金融的Python库。
- [Quantsbin](https://github.com/quantsbin/Quantsbin) - 用于定价和绘制常规期权价格、希腊字母等分析工具。
- [finoptions](https://github.com/bbcho/finoptions-dev) - 完整的Python实现R包fOptions，支持各种期权定价。
- [pypme](https://github.com/ymyke/pypme) - PME（公共市场等效）计算工具。
- [AbsBox](https://github.com/yellowbean/AbsBox) - 用于建模资产支持证券（ABS）和按揭支持证券（MBS）现金流的Python库。
- [Intrinsic-Value-Calculator](https://github.com/akashaero/Intrinsic-Value-Calculator) - 一个Python工具，用于使用贴现现金流法快速计算股票的公允价值。
- [Kelly-Criterion](https://github.com/deltaray-io/kelly-criterion) - 用Python实现的Kelly准则，用于基于J.L. Kelly Jr公式计算投资组合大小。
- [rateslib](https://github.com/attack68/rateslib) - 用于定价债券、债券期货及衍生品的固定收益Python库。
- [fypy](https://github.com/jkirkby3/fypy) - 支持定量研究与开发的期权定价库，涵盖常规与另类期权定价，以及金融模型的市场数据标定。


### 技术指标

- [pandas_talib](https://github.com/femtotrader/pandas_talib)：一个基于Pandas的Python技术分析指标库。
- [finta](https://github.com/peerchemist/finta)：实现常见金融技术分析指标的Pandas库。
- [Tulipy](https://github.com/cirla/tulipy)：金融技术分析指标库（提供Python绑定）。
- [lppls](https://github.com/Boulder-Investment-Technologies/lppls)：用于拟合Log-Periodic Power Law Singularity (LPPLS)模型的Python模块。
- [talipp](https://github.com/nardew/talipp)：增量式技术分析库。
- [streaming_indicators](https://github.com/mr-easy/streaming_indicators)：用于流数据中计算技术分析指标的Python库。

### 交易与回测

- [skfolio](https://github.com/skfolio/skfolio)：一个基于scikit-learn的Python库，用于投资组合优化。
- [Investing algorithm framework](https://github.com/coding-kitties/investing-algorithm-framework)：用于开发、回测和部署自动化交易算法的框架。
- [QSTrader](https://github.com/mhallsmoore/qstrader)：QSTrader回测模拟引擎。
- [Blankly](https://github.com/Blankly-Finance/Blankly)：集成了回测、模拟交易和实时部署的系统。
- [TA-Lib](https://github.com/mrjbq7/ta-lib)：TA-Lib的Python接口。
- [zipline](https://github.com/quantopian/zipline)：Python算法交易库。
- [zipline-reloaded](https://github.com/stefan-jansen/zipline-reloaded)：Zipline的重载版本，适用于算法交易。
- [QuantSoftware Toolkit](https://github.com/QuantSoftware/QuantSoftwareToolkit)：基于Python的开源框架，支持投资组合构建与管理。
- [quantitative](https://github.com/jeffrey-liang/quantitative)：量化金融与回测库。
- [analyzer](https://github.com/llazzaro/analyzer)：用于实时金融与交易策略回测的Python框架。
- [bt](https://github.com/pmorissette/bt)：灵活的Python回测框架。
- [backtrader](https://github.com/backtrader/backtrader)：Python交易策略回测库。
- [pythalesians](https://github.com/thalesians/pythalesians)：用于回测交易策略、绘制图表、下载市场数据、分析市场模式等功能的Python库。
- [pybacktest](https://github.com/ematvey/pybacktest)：基于Pandas的向量化回测框架。
- [pyalgotrade](https://github.com/gbeced/pyalgotrade)：Python算法交易库。
- [basana](https://github.com/gbeced/basana)：基于Python的异步事件驱动算法交易框架，专注于加密货币。
- [tradingWithPython](https://pypi.org/project/tradingWithPython/)：量化交易的函数和类集合。
- [Pandas TA](https://github.com/twopirllc/pandas-ta)：易于使用的Python 3 Pandas扩展，提供115+种指标。
- [ta](https://github.com/bukosabino/ta)：基于Pandas的技术分析库（Python）。
- [algobroker](https://github.com/joequant/algobroker)：一个算法交易的执行引擎。
- [pysentosa](https://pypi.org/project/pysentosa/)：Sentosa交易系统的Python API。
- [finmarketpy](https://github.com/cuemacro/finmarketpy)：用于回测交易策略和分析金融市场的Python库。
- [binary-martingale](https://github.com/metaperl/binary-martingale)：自动化的二元期权马丁格尔交易程序。
- [fooltrader](https://github.com/foolcage/fooltrader)：利用大数据技术分析市场的项目。
- [zvt](https://github.com/zvtvz/zvt)：一个基于SQL和Pandas的统一数据记录、因子计算、证券选择、回测和实时交易框架。
- [pylivetrader](https://github.com/alpacahq/pylivetrader)：与Zipline兼容的实时交易库。
- [pipeline-live](https://github.com/alpacahq/pipeline-live)：Zipline的管道功能与IEX的实时交易。
- [zipline-extensions](https://github.com/quantrocket-llc/zipline-extensions)：Zipline的扩展与QuantRocket适配器。
- [moonshot](https://github.com/quantrocket-llc/moonshot)：基于Pandas的回测器和交易引擎。
- [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt)：Python中的投资组合优化工具，支持经典的有效前沿和先进方法。
- [Eiten](https://github.com/tradytics/eiten)：Tradytics提供的开源工具包，支持统计与算法投资策略。
- [riskparity.py](https://github.com/dppalomar/riskparity.py)：基于TensorFlow 2.0的风险平价投资组合设计工具。
- [mlfinlab](https://github.com/hudson-and-thames/mlfinlab)：关于《金融机器学习进展》的实现，涉及特征工程、金融数据结构、元标记等。
- [pyqstrat](https://github.com/abbass2/pyqstrat)：一个快速、可扩展且透明的Python库，用于回测量化策略。
- [NowTrade](https://github.com/edouardpoitras/NowTrade)：用于回测技术/机械策略的Python库。
- [pinkfish](https://github.com/fja05680/pinkfish)：用于安全分析的回测器与电子表格库。
- [aat](https://github.com/timkpaine/aat)：基于Python的异步算法交易引擎。
- [Backtesting.py](https://kernc.github.io/backtesting.py/)：用于回测交易策略的Python库。
- [catalyst](https://github.com/enigmampc/catalyst)：专为加密资产设计的算法交易库。
- [quantstats](https://github.com/ranaroussi/quantstats)：为量化分析师提供的投资组合分析工具。
- [qtpylib](https://github.com/ranaroussi/qtpylib)：Python化的算法交易库。
- [Quantdom](https://github.com/constverum/Quantdom)：基于Python的量化交易策略回测框架，附带图形界面。
- [freqtrade](https://github.com/freqtrade/freqtrade)：开源的加密交易机器人。
- [algorithmic-trading-with-python](https://github.com/chrisconlan/algorithmic-trading-with-python)：用于交易模拟、回测和金融数据机器学习的免费资源。
- [DeepDow](https://github.com/jankrepl/deepdow)：基于深度学习的投资组合优化。
- [Qlib](https://github.com/microsoft/qlib)：微软推出的量化投资平台，提供完整的机器学习流程。
- [machine-learning-for-trading](https://github.com/stefan-jansen/machine-learning-for-trading)：量化交易的机器学习代码和资源。
- [AlphaPy](https://github.com/ScottfreeLLC/AlphaPy)：自动化机器学习（AutoML）工具包，支持多种模型。
- [jesse](https://github.com/jesse-ai/jesse)：一个先进的加密交易机器人。
- [rqalpha](https://github.com/ricequant/rqalpha)：一个可扩展的Python算法回测与交易框架，支持多种证券。
- [FinRL-Library](https://github.com/AI4Finance-LLC/FinRL-Library)：深度强化学习库，用于量化金融中的自动交易。
- [bulbea](https://github.com/achillesrasquinha/bulbea)：基于深度学习的股市预测与建模库。
- [ib_nope](https://github.com/ajhpark/ib_nope)：用于IBKR TWS平台的自动化交易系统。
- [OctoBot](https://github.com/Drakkar-Software/OctoBot)：开源加密交易机器人，支持高频、套利、技术分析和社交交易。
- [bta-lib](https://github.com/mementum/bta-lib)：基于Pandas的技术分析库，用于回测和量化分析。
- [Stock-Prediction-Models](https://github.com/huseinzol05/Stock-Prediction-Models)：收集机器学习和深度学习模型，用于股市预测和交易机器人开发。
- [TuneTA](https://github.com/jmrichardson/tuneta)：使用距离相关度度量优化技术指标的库。
- [AutoTrader](https://github.com/kieran-mackle/AutoTrader)：开源Python交易自动化工具，利用深度学习、强化学习进行算法交易。



### 风险分析

- [QuantLibRisks](https://github.com/auto-differentiation/QuantLib-Risks-Py) - 使用QuantLib进行快速风险分析
- [XAD](https://github.com/auto-differentiation/xad-py) - 自动微分（AAD）库
- [pyfolio](https://github.com/quantopian/pyfolio) - Python中的投资组合和风险分析工具
- [empyrical](https://github.com/quantopian/empyrical) - 常用的金融风险和绩效指标
- [fecon235](https://github.com/rsvp/fecon235) - 包含高峰风险的高斯混合模型和自适应Boltzmann投资组合的金融经济学计算工具
- [finance](https://pypi.org/project/finance/) - 财务风险计算工具，易于使用
- [qfrm](https://pypi.org/project/qfrm/) - 定量金融风险管理工具，用于衡量、管理和可视化金融工具及投资组合的风险
- [visualize-wealth](https://github.com/benjaminmgross/visualize-wealth) - 投资组合构建与定量分析
- [VisualPortfolio](https://github.com/wegamekinglc/VisualPortfolio) - 用于可视化投资组合表现的工具
- [universal-portfolios](https://github.com/Marigold/universal-portfolios) - 用于在线投资组合选择的算法集合
- [FinQuant](https://github.com/fmilthaler/FinQuant) - 投资组合管理、分析与优化程序
- [Empyrial](https://github.com/ssantoshp/Empyrial) - 投资组合风险、绩效分析与回报预测
- [risktools](https://github.com/bbcho/risktools-dev) - 用于原油及其产品交易的风险工具，部分实现了R的PerformanceAnalytics
- [Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) - 用于投资组合优化与定量战略资产配置的Python库
- [empyrical-reloaded](https://github.com/stefan-jansen/empyrical-reloaded) - 常用的金融风险和绩效指标，empyrical的改进版
- [pyfolio-reloaded](https://github.com/stefan-jansen/pyfolio-reloaded) - Python中的投资组合和风险分析工具，pyfolio的改进版
- [fortitudo.tech](https://github.com/fortitudo-tech/fortitudo.tech) - 用于投资组合优化的条件风险值（CVaR）工具和熵池视图/压力测试

### 因子分析

- [alphalens](https://github.com/quantopian/alphalens) - 预测性因子的绩效分析
- [alphalens-reloaded](https://github.com/stefan-jansen/alphalens-reloaded) - 预测性（alpha）股票因子的绩效分析
- [Spectre](https://github.com/Heerozh/spectre) - GPU加速的因子分析库与回测工具

### 情感分析

- [Asset News Sentiment Analyzer](https://github.com/KVignesh122/AssetNewsSentimentAnalyzer) - 针对金融资产的情感分析与报告生成工具，利用GPT模型

### 定量研究环境

- [Jupyter Quant](https://github.com/gnzsnz/jupyter-quant) - 一个Docker化的Jupyter量化研究环境，预加载量化分析工具（如statsmodels、pymc、zipline-reloaded等）

### 时间序列分析

- [ARCH](https://github.com/bashtage/arch) - Python中的ARCH模型
- [statsmodels](http://statsmodels.sourceforge.net) - Python模块，支持数据探索、统计模型估计与统计检验
- [dynts](https://github.com/quantmind/dynts) - Python包，用于时间序列分析与处理
- [PyFlux](https://github.com/RJT1990/pyflux) - Python库，用于时间序列建模与推断（包括频率与贝叶斯方法）
- [tsfresh](https://github.com/blue-yonder/tsfresh) - 自动从时间序列中提取相关特征
- [hasura/quandl-metabase](https://platform.hasura.io/hub/projects/anirudhm/quandl-metabase-time-series) - Hasura快速入门，使用Metabase可视化Quandl的时间序列数据
- [Facebook Prophet](https://github.com/facebook/prophet) - 用于高质量时间序列预测的工具，支持多季节性与线性或非线性增长
- [tsmoothie](https://github.com/cerlymarco/tsmoothie) - Python库，用于时间序列平滑与异常值检测
- [pmdarima](https://github.com/alkaline-ml/pmdarima) - 一个统计库，填补Python在时间序列分析领域的空白，提供R的auto.arima功能
- [gluon-ts](https://github.com/awslabs/gluon-ts) - 用于时间序列建模的Python库
- [functime](https://github.com/functime-org/functime) - 大规模时间序列机器学习，基于Polars库加速特征提取与预测

### 日历工具

- [exchange_calendars](https://github.com/gerrymanoim/exchange_calendars) - 股票交易日历
- [bizdays](https://github.com/wilsonfreitas/python-bizdays) - 计算商业日期的工具与实用程序
- [pandas_market_calendars](https://github.com/rsheftel/pandas_market_calendars) - 与pandas结合使用的交易所日历

### 数据来源

- [yfinance](https://github.com/ranaroussi/yfinance) - Yahoo! Finance市场数据下载工具
- [findatapy](https://github.com/cuemacro/findatapy) - Python库，通过Bloomberg、Quandl、Yahoo等获取市场数据
- [googlefinance](https://github.com/hongtaocai/googlefinance) - 用于获取Google Finance实时股票数据的Python模块
- [yahoo-finance](https://github.com/lukaszbanasiak/yahoo-finance) - 获取Yahoo! Finance股票数据的Python模块
- [pandas-datareader](https://github.com/pydata/pandas-datareader) - 用于从多种数据源（如Yahoo Finance、FRED等）获取数据的Python模块
- [pyhoofinance](https://github.com/innes213/pyhoofinance) - 快速查询Yahoo Finance多个股票代码数据的工具
- [yfinanceapi](https://github.com/Karthik005/yfinanceapi) - 用于获取财务数据的Python API
- [coinmarketcap](https://github.com/barnumbirr/coinmarketcap) - CoinMarketCap的Python API接口
- [after-hours](https://github.com/datawrestler/after-hours) - 获取特定股票在盘后交易时间的股票价格
- [bronto-python](https://pypi.org/project/bronto-python/) - Bronto API集成工具
- [pytdx](https://github.com/rainx/pytdx) - 用于从TongDaXin节点获取中国股票实时报价数据的Python接口
- [tiingo](https://github.com/hydrosquall/tiingo-python) - Tiingo数据平台提供的日常合成价格、OHLCV、实时新闻的Python接口
- [iexfinance](https://github.com/addisonlynch/iexfinance) - 用于从Investor's Exchange获取实时与历史股票数据的Python接口
- [alpaca-trade-api](https://github.com/alpacahq/alpaca-trade-api-python) - 用于获取实时与历史股票价格和交易执行的Python接口
- [metatrader5](https://pypi.org/project/MetaTrader5/) - MetaTrader 5终端API连接工具
- [akshare](https://github.com/jindaxiang/akshare) - 一个优雅且简洁的金融数据接口库，适用于Python用户
- [yahooquery](https://github.com/dpguthrie/yahooquery) - 通过非官方Yahoo Finance API接口获取数据的Python接口
- [investpy](https://github.com/alvarobartt/investpy) - 从Investing.com获取金融数据的Python工具

### Excel 集成

- [xlwings](https://www.xlwings.org/) - 让 Excel 与 Python 无缝连接。
- [openpyxl](https://openpyxl.readthedocs.io/en/latest/) - 读取/写入 Excel 2007 xlsx/xlsm 文件。
- [xlrd](https://github.com/python-excel/xlrd) - 用于从 Excel 表格文件提取数据的开发库。
- [xlsxwriter](https://xlsxwriter.readthedocs.io/) - 写入 Excel 2007+ XLSX 文件格式。
- [xlwt](https://github.com/python-excel/xlwt) - 创建兼容 MS Excel 97/2000/XP/2003 XLS 文件的库。
- [DataNitro](https://datanitro.com/) - 提供完整的 Python-Excel 集成功能，包括用户自定义函数 (UDFs)，需要购买许可。
- [xlloop](http://xlloop.sourceforge.net) - 一个开源框架，用于在集中式服务器上实现 Excel 用户自定义函数 (UDFs)。
- [expy](http://www.bnikolic.co.uk/expy/expy.html) - 允许在 Excel 表格中直接使用 Python 执行代码并定义新函数的插件。
- [pyxll](https://www.pyxll.com) - 一个 Excel 插件，通过 Python 扩展 Excel 功能。

### 数据可视化

- [D-Tale](https://github.com/man-group/dtale) - 用于可视化 pandas 数据框和 xarray 数据集的工具。
- [mplfinance](https://github.com/matplotlib/mplfinance) - 用于金融数据的可视化分析。
- [finplot](https://github.com/highfestiva/finplot) - 高效的金融数据绘图工具。
- [finvizfinance](https://github.com/lit26/finvizfinance) - Finviz 分析 Python 库。
- [market-analy](https://github.com/maread99/market_analy) - 使用 [market-prices](https://github.com/maread99/market_prices) 和 bqplot 进行市场数据分析和互动图表。
- [QuantInvestStrats](https://github.com/ArturSepp/QuantInvestStrats) - 提供金融数据可视化、绩效报告和定量策略分析的工具包。

## R

### 数值库与数据结构

- [xts](https://github.com/joshuaulrich/xts) - 扩展 zoo 库，处理 R 中的时间序列数据。
- [data.table](https://github.com/Rdatatable/data.table) - 扩展数据框，支持快速聚合、排序连接、分组操作等，适用于大数据。
- [sparseEigen](https://github.com/dppalomar/sparseEigen) - 稀疏主成分分析。
- [TSdbi](http://tsdbi.r-forge.r-project.org/) - 提供通用的时间序列数据库接口。
- [tseries](https://cran.r-project.org/web/packages/tseries/index.html) - 时间序列分析与金融计算。
- [zoo](https://cran.r-project.org/web/packages/zoo/index.html) - 用于规则和不规则时间序列的 S3 基础设施。
- [tis](https://cran.r-project.org/web/packages/tis/index.html) - 提供时间索引和时间序列的函数和 S3 类。
- [tfplot](https://cran.r-project.org/web/packages/tfplot/index.html) - 用于时间序列数据的简单操作和快速绘图。
- [tframe](https://cran.r-project.org/web/packages/tframe/index.html) - 用于编写时间序列方法的核心函数库。

### 数据源

- [IBrokers](https://cran.r-project.org/web/packages/IBrokers/index.html) - 提供 R 访问 Interactive Brokers Trader Workstation API 的接口。
- [Rblpapi](https://github.com/Rblp/Rblpapi) - 提供 Bloomberg 的 R 接口。
- [Quandl](https://www.quandl.com/tools/r) - 直接将金融数据导入 R。
- [Rbitcoin](https://github.com/jangorecki/Rbitcoin) - 统一的市场 API 接口（bitstamp, kraken, btce, bitmarket）。
- [GetTDData](https://github.com/msperlin/GetTDData) - 直接从 Tesouro Direto 网站下载并汇总巴西政府债券数据。
- [GetHFData](https://github.com/msperlin/GetHFData) - 直接从 Bovespa ftp 网站下载并汇总巴西高频交易数据。
- [Reddit WallstreetBets API](https://dashboard.nbshare.io/apps/reddit/api/) - 提供 Reddit WallstreetBets 子版块的每日股票和情感分析。
- [td](https://github.com/eddelbuettel/td) - 用于股票和数字货币的 Twelvedata API 接口。
- [rbcb](https://github.com/wilsonfreitas/rbcb) - 巴西中央银行的 R 接口。
- [rb3](https://github.com/ropensci/rb3) - 提供从 B3 下载和解析数据的工具。
- [simfinapi](https://github.com/matthiasgomolka/simfinapi) - 使 R 更易访问 SimFin 数据。
- [tidyfinance](https://github.com/tidy-finance/r-tidyfinance) - 用于下载金融数据并将其转换为结构化格式的 R 工具。

### 金融工具与定价

- [RQuantLib](https://github.com/eddelbuettel/rquantlib) - 连接 GNU R 和 QuantLib。
- [quantmod](https://cran.r-project.org/web/packages/quantmod/index.html) - 定量金融建模框架。
- [Rmetrics](https://www.rmetrics.org) - 用于定量金融教学和训练的开源软件解决方案。
  - [fAsianOptions](https://cran.r-project.org/web/packages/fAsianOptions/index.html) - 亚洲期权估值。
  - [fAssets](https://cran.r-project.org/web/packages/fAssets/index.html) - 金融资产分析与建模。
  - [fBasics](https://cran.r-project.org/web/packages/fBasics/index.html) - 市场与基础统计。
  - [fBonds](https://cran.r-project.org/web/packages/fBonds/index.html) - 债券与利率模型。
  - [fExoticOptions](https://cran.r-project.org/web/packages/fExoticOptions/index.html) - 异常期权估值。
  - [fOptions](https://cran.r-project.org/web/packages/fOptions/index.html) - 期权定价与评估。
  - [fPortfolio](https://cran.r-project.org/web/packages/fPortfolio/index.html) - 投资组合选择与优化。
- [portfolio](https://github.com/dgerlanc/portfolio) - 股票投资组合分析。
- [sparseIndexTracking](https://github.com/dppalomar/sparseIndexTracking) - 设计跟踪指数的投资组合。
- [covFactorModel](https://github.com/dppalomar/covFactorModel) - 使用因子模型估算协方差矩阵。
- [riskParityPortfolio](https://github.com/dppalomar/riskParityPortfolio) - 快速设计风险平价投资组合。
- [sde](https://cran.r-project.org/web/packages/sde/index.html) - 随机微分方程的仿真与推断。
- [YieldCurve](https://cran.r-project.org/web/packages/YieldCurve/index.html) - 收益曲线建模与估算。
- [SmithWilsonYieldCurve](https://cran.r-project.org/web/packages/SmithWilsonYieldCurve/index.html) - 使用 Smith-Wilson 方法构建 LIBOR 和 SWAP 率的收益曲线。
- [ycinterextra](https://cran.r-project.org/web/packages/ycinterextra/index.html) - 收益曲线或零票息价格的插值与外推。
- [AmericanCallOpt](https://cran.r-project.org/web/packages/AmericanCallOpt/index.html) - 定价美国看涨期权。
- [VarSwapPrice](https://cran.r-project.org/web/packages/VarSwapPrice/index.html) - 定价股指波动率互换。
- [RND](https://cran.r-project.org/web/packages/RND/index.html) - 风险中性密度提取包。
- [LSMonteCarlo](https://cran.r-project.org/web/packages/LSMonteCarlo/index.html) - 使用最小二乘蒙特卡洛方法定价美国期权。
- [OptHedging](https://cran.r-project.org/web/packages/OptHedging/index.html) - 估算期权的价值与对冲策略。
- [tvm](https://cran.r-project.org/web/packages/tvm/index.html) - 时间价值函数。
- [OptionPricing](https://cran.r-project.org/web/packages/OptionPricing/index.html) - 高效仿真算法进行期权定价。
- [credule](https://github.com/blenezet/credule) - 信用违约互换功能。
- [derivmkts](https://cran.r-project.org/web/packages/derivmkts/index.html) - 用于处理金融衍生品和期权分析的 R 包。

### 交易

- [backtest](https://cran.r-project.org/web/packages/backtest/index.html) - 探索基于投资组合的金融工具假设。
- [pa](https://cran.r-project.org/web/packages/pa/index.html) - 股票投资组合的表现归因分析。
- [TTR](https://github.com/joshuaulrich/TTR) - 技术交易规则。
- [QuantTools](https://quanttools.bitbucket.io/_site/index.html) - 增强型量化交易建模工具。
- [blotter](https://github.com/braverock/blotter) - 用于定义金融工具、交易、投资组合和账户的交易系统基础设施，支持多资产类别和多货币投资组合，持续维护和更新。

### 回测

- [quantstrat](https://github.com/braverock/quantstrat) - 以交易为中心的基础设施，用于构建交易系统和回测，支持多资产类别和多货币投资组合。

### 风险分析

- [PerformanceAnalytics](https://github.com/braverock/PerformanceAnalytics) - 用于绩效和风险分析的计量经济学工具。

### 因子分析

- [FactorAnalytics](https://github.com/braverock/FactorAnalytics) - 包含用于投资组合构建、优化和风险管理的三种主要因子模型分析方法：基本面因子模型、时间序列因子模型和统计因子模型。
- [Expected Returns](https://github.com/JustinMShea/ExpectedReturns) - 提供增强投资组合多样化的解决方案，并重现了近年来一些经典的金融学论文。

### 时间序列

- [tseries](https://cran.r-project.org/web/packages/tseries/index.html) - 时间序列分析与计算金融学工具。
- [fGarch](https://cran.r-project.org/web/packages/fGarch/index.html) - Rmetrics工具：自回归条件异方差模型。
- [timeSeries](https://cran.r-project.org/web/packages/timeSeries/index.html) - Rmetrics工具：金融时间序列对象。
- [rugarch](https://github.com/alexiosg/rugarch) - 单变量GARCH模型。
- [rmgarch](https://github.com/alexiosg/rmgarch) - 多变量GARCH模型。
- [tidypredict](https://github.com/edgararuiz/tidypredict) - 在数据库中运行预测。
- [tidyquant](https://github.com/business-science/tidyquant) - 将金融分析引入tidyverse。
- [timetk](https://github.com/business-science/timetk) - 用于时间序列处理的R工具包。
- [tibbletime](https://github.com/business-science/tibbletime) - 基于tidyverse构建的扩展，允许通过设置时间索引创建具有时间感知的tibbles。
- [matrixprofile](https://github.com/matrix-profile-foundation/matrixprofile) - 基于Matrix Profile数据结构和算法的时间序列数据挖掘库。
- [garchmodels](https://github.com/AlbertoAlmuinha/garchmodels) - GARCH模型的parsnip后端。

### 日历

- [timeDate](https://cran.r-project.org/web/packages/timeDate/index.html) - 时间和日历对象。
- [bizdays](https://github.com/wilsonfreitas/R-bizdays) - 计算工作日的工具和实用程序。

### Matlab

- [QUANTAXIS](https://github.com/yutiansut/quantaxis) - 集成的Matlab量化工具箱。
- [PROJ_Option_Pricing_Matlab](https://github.com/jkirkby3/PROJ_Option_Pricing_Matlab) - 量化期权定价：包括障碍期权、亚洲期权、欧洲期权等。

### Julia

- [Lucky.jl](https://github.com/oliviermilla/Lucky.jl) - 纯Julia编写的模块化、异步交易引擎。
- [QuantLib.jl](https://github.com/pazzo83/QuantLib.jl) - 纯Julia实现的QuantLib。
- [Ito.jl](https://github.com/aviks/Ito.jl) - 用于量化金融的Julia包。
- [TALib.jl](https://github.com/femtotrader/TALib.jl) - TA-Lib的Julia封装。
- [IncTA.jl](https://github.com/femtotrader/IncTA.jl) - Julia增量技术分析指标。
- [Miletus.jl](https://github.com/JuliaComputing/Miletus.jl) - 金融合同定义、建模语言和估值框架。
- [Temporal.jl](https://github.com/dysonance/Temporal.jl) - 高效的时间序列类及方法。
- [Indicators.jl](https://github.com/dysonance/Indicators.jl) - 基于Temporal的金融市场技术分析与指标。
- [Strategems.jl](https://github.com/dysonance/Strategems.jl) - 量化系统交易策略开发与回测。
- [TimeSeries.jl](https://github.com/JuliaStats/TimeSeries.jl) - Julia时间序列工具包。
- [MarketTechnicals.jl](https://github.com/JuliaQuant/MarketTechnicals.jl) - 基于TimeSeries的金融时间序列技术分析。
- [MarketData.jl](https://github.com/JuliaQuant/MarketData.jl) - 时间序列市场数据。
- [TimeFrames.jl](https://github.com/femtotrader/TimeFrames.jl) - 定义时间框架的Julia库，主要用于时间序列重采样。
- [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) - Julia中的内存数据框。
- [TSFrames.jl](https://github.com/xKDR/TSFrames.jl) - 基于DataFrames.jl处理时间序列数据。

### Java

- [Strata](http://strata.opengamma.io/) - 现代化的开源分析和市场风险库，基于Java编写。
- [JQuantLib](https://github.com/frgomes/jquantlib) - JQuantLib是一个免费的、全面的量化金融框架，完全用Java编写。
- [finmath.net](http://finmath.net) - Java库，包含与数学金融相关的算法和方法。
- [quantcomponents](https://github.com/lsgro/quantcomponents) - 免费的Java量化金融和算法交易组件。
- [DRIP](https://lakshmidrip.github.io/DRIP) - 固定收益、资产配置、交易成本分析和XVA度量库。
- [ta4j](https://github.com/ta4j/ta4j) - 用于技术分析的Java库。

### JavaScript

- [finance.js](https://github.com/ebradyjobory/finance.js) - 用于常见金融计算的JavaScript库。
- [portfolio-allocation](https://github.com/lequant40/portfolio_allocation_js) - 一个用于构建由多种资产组成的金融投资组合的JavaScript库。
- [Ghostfolio](https://github.com/ghostfolio/ghostfolio) - 财富管理软件，帮助追踪股票、ETF或加密货币等金融资产，并做出数据驱动的投资决策。
- [IndicatorTS](https://github.com/cinar/indicatorts) - 提供各种股票技术分析指标、策略和回测框架的TypeScript模块。
- [ccxt](https://github.com/ccxt/ccxt) - 支持超过100个比特币/山寨币交易所的加密货币交易API（JavaScript/Python/PHP）。
- [PENDAX](https://github.com/CompendiumFi/PENDAX-SDK) - 用于FTX、FTXUS、OKX、Bybit等交易所的JavaScript SDK。

### 数据可视化

- [QUANTAXIS_Webkit](https://github.com/yutiansut/QUANTAXIS_Webkit) - 基于quantaxis的强大数据可视化中心。

### Haskell

- [quantfin](https://github.com/boundedvariation/quantfin) - 纯Haskell编写的量化金融库。
- [Haxcel](https://github.com/MarcusRainbow/Haxcel) - Haskell的Excel插件。
- [Ffinar](https://github.com/MarcusRainbow/Ffinar) - Haskell中的金融数学库。

### Scala

- [QuantScale](https://github.com/choucrifahed/quantscale) - Scala量化金融库。
- [Scala Quant](https://github.com/frankcash/Scala-Quant) - 用于从IFTTT配方或Google Finance获取股票数据的Scala库。

### Ruby

- [Jiji](https://github.com/unageanu/jiji2) - 开源的外汇算法交易框架，使用OANDA REST API。

### Elixir/Erlang

- [Tai](https://github.com/fremantle-capital/tai) - 开源的可组合、实时市场数据和交易执行工具包。
- [Workbench](https://github.com/fremantle-capital/workbench) - 基于Erlang/Elixir的量化交易工具包。

## 作品再现、训练与书籍

- [自动微分网站](https://auto-differentiation.github.io/) - 提供自动微分（AD）和伴随算法微分（AAD）的背景信息和资源。
- [德曼论文](https://github.com/MarcosCarreira/DermanPapers) - 复现Emanuel Derman的经典量化金融论文的笔记本。
- [ML-Quant](https://www.ml-quant.com/) - 提供ArXiv、SSRN、RePec、期刊、播客、视频和博客等量化资源。
- [波动率交易](https://github.com/jasonstrimpel/volatility-trading) - 基于Euan Sinclair的《波动率交易》提供完整的波动率估算工具集。
- [量化金融](https://github.com/paulperry/quant) - 量化金融和算法交易的资源，主要是基于Quantopian、Zipline或Pandas的Ipython笔记本。
- [fecon235](https://github.com/rsvp/fecon235) - 公开的金融经济学软件工具开源项目，提供许多Jupyter笔记本，帮助互动验证理论和实践方法。
- [量化笔记本](https://github.com/LongOnly/Quantitative-Notebooks) - 关于量化金融、算法交易、金融建模和投资策略的教育笔记本。
- [QuantEcon](https://quantecon.org/) - 经济学、金融学、计量经济学和数据科学的讲座系列，包含QuantEcon.py、QuantEcon.jl等工具和笔记本。
- [FinanceHub](https://github.com/Finance-Hub/FinanceHub) - 量化金融资源。
- [Python期权定价](https://github.com/dedwards25/Python_Option_Pricing) - 一个用Python编写的金融期权定价库，涵盖了Black-Scholes、Black 76、隐含波动率、美式、欧式、亚洲期权等。
- [J.P. Morgan Python培训](https://github.com/jpmorganchase/python-training) - J.P. Morgan为业务分析师和交易员提供的Python培训课程。
- [量化股票分析](https://github.com/LastAncientOne/Stock_Analysis_For_Quant) - 提供在Excel、Matlab、Power BI、Python、R和Tableau等工具中进行股票分析的方法。
- [Python算法交易](https://github.com/chrisconlan/algorithmic-trading-with-python) - 书籍《Python算法交易（2020）》的源代码。
- [MEDIUM笔记本](https://github.com/cerlymarco/MEDIUM_NoteBook) - 收录cerlymarco在Medium上的笔记本文章。
- [量化金融训练](https://github.com/PythonCharmers/QuantFinance) - 量化金融训练资料。
- [IPython脚本](https://github.com/mgroncki/IPythonScripts) - 介绍Python和QuantLib的量化金融教程，涵盖定价、xVAs、对冲、投资组合优化、机器学习等。
- [计算金融课程](https://github.com/LechGrzelak/Computational-Finance-Course) - 计算金融课程的资料。
- [资产管理机器学习](https://github.com/emoen/Machine-Learning-for-Asset-Managers) - 实现《资产管理的机器学习》书中的代码片段，应用于实时数据。
- [Python金融烹饪书](https://github.com/PacktPublishing/Python-for-Finance-Cookbook) - 《Python金融烹饪书》，由Packt出版。
- [期权定价模型](https://github.com/ysaporito/modelos_vol_derivativos) - 《期权定价模型》一书的Jupyter笔记本。
- [NMOF](https://github.com/enricoschumann/NMOF) - 《金融中的数值方法与优化》一书的函数、示例和数据。
- [py4fi2nd](https://github.com/yhilpisch/py4fi2nd) - 《Python金融（二版）》书的Jupyter笔记本与代码。
- [aiif](https://github.com/yhilpisch/aiif) - 《金融中的人工智能》书的Jupyter笔记本与代码。
- [py4at](https://github.com/yhilpisch/py4at) - 《算法交易的Python》书的Jupyter笔记本与代码。
- [dawp](https://github.com/yhilpisch/dawp) - 《用Python分析衍生品》书的Jupyter笔记本与代码。
- [dx](https://github.com/yhilpisch/dx) - 使用Python进行金融与衍生品分析的资源。
- [量化金融书](https://github.com/LechGrzelak/QuantFinanceBook) - 量化金融书籍的资源。
- [粗糙Bergomi模型](https://github.com/ryanmccrickerd/rough_bergomi) - 粗糙Bergomi模型的Python实现。
- [FRH-Heston模型](https://github.com/ryanmccrickerd/frh-fx) - 适用于外汇市场的Fast-Reversion Heston模型的Python实现。
- [价值投资研究](https://github.com/euclidjda/value-investing-studies) - 价值投资在长期内的表现和特点的数据分析研究。
- [机器学习资产管理](https://github.com/firmai/machine-learning-asset-management) - 机器学习在资产管理中的应用。
- [深度学习与机器学习股票](https://github.com/LastAncientOne/Deep-Learning-Machine-Learning-Stock) - 深度学习和机器学习在股票中的应用，具有长短期投资机会。
- [技术分析与特征工程](https://github.com/jo-cho/Technical_Analysis_and_Feature_Engineering) - 机器学习在金融市场中的特征工程与特征重要性。
- [差分机器学习与重要轴](https://github.com/differential-machine-learning/notebooks) - 实现、展示、复现并扩展《风险》文章中的《差分机器学习》和《带差分的PCA》方法，并补充论文中未提及的实现细节。
- [系统交易示例](https://github.com/robcarver17/systematictradingexamples) - 与《系统交易》书和博客相关的代码示例。
- [pysystemtrade示例](https://github.com/robcarver17/pysystemtrade_examples) - 使用pysystemtrade的代码示例，来源于Robert Carver的博客。
- [ML金融代码](https://github.com/mfrdixon/ML_Finance_Codes) - 《机器学习在金融中的应用：从理论到实践》书中的代码。
- [算法交易机器学习实战](https://github.com/packtpublishing/hands-on-machine-learning-for-algorithmic-trading) - 《算法交易的机器学习实战》，由Packt出版。
- [金融小白杂项](https://github.com/financialnoob/misc) - @financialnoob在博客上的帖子中的代码。
- [MesoSim期权交易策略库](https://github.com/deltaray-io/strategy-library) - MesoSim的公开免费期权交易策略库。
- [量化金融与Python代码](https://github.com/lingyixu/Quant-Finance-With-Python-Code) - 《量化金融与Python代码》书中的代码示例。
- [量化金融训练](https://github.com/JoaoJungblut/QuantFinanceTraining) - 这是我在CQF（量化金融证书）培训期间执行的代码库，代码按课程组织，便于导航和参考。
- [基于统计学习的投资组合优化](https://github.com/YannickKae/Statistical-Learning-based-Portfolio-Optimization) - 一个R Shiny应用，利用层次化平衡风险贡献（HERC）方法进行投资组合优化。
- [利率衍生品定价与交易书](https://github.com/attack68/book_irds3) - 《利率衍生品定价与交易》书的代码库。
- [自编码器资产定价模型](https://github.com/RichardS0268/Autoencoder-Asset-Pricing-Models) - 自编码器资产定价模型（GKX, 2019）的重现。
- [金融编程](https://github.com/shashankvemuri/Finance) - 150多个用于收集、处理和分析股市数据的Python程序。
- [101公式性Alpha](https://github.com/ram-ki/101_formulaic_alphas) - 使用qstrader实现《101公式性Alpha》的代码。
- [Tidy Finance](https://www.tidy-finance.org/) - 一种有观点的金融经济学实证研究方法，提供多个编程语言（Python和R）的开源代码，支持学生和实践者实现可重复的金融研究项目。
- [粗糙波动性研讨会](https://github.com/jgatheral/RoughVolatilityWorkshop) - 2024年QuantMind的粗糙波动性研讨会讲座。
