# tagTrader

# 参照项目
    1.cppvnpy
        https://github.com/FlyCatZout/cppvnpy
        感谢 event_engine 的 c++ 实现,否则是不可实现任务
    2.LazzyQuant
        https://github.com/zc8424/LazzyQuant
    3.vnpy
        https://github.com/vnpy/vnpy
        了解接口算法的好材料
    4.CTPTrader
        https://github.com/huxingwu1/CTPTrader
      
# 已实现功能
    0.不同市场接口 以 dll 方式 自动 加载
    1.c++ 策略以 dll 方式 自动 加载
    2.python 策略 回测,加载
    3.多接口多账户同时启动停止
      多市场,多账户交易
    4.历史数据查询,实时数据推送
    5.手动交易
    6.c++策略,python策略 程序化交易
    
# 限制
    当前只实现 了 ctp,oes两个接口
    只在 win10x64 系统测试运行成功,其他 window 版本 未测试
    centos 上可以运行
    macos 上没有 ctp 接口,可运行 oes 接口

# 好项目
    1.https://github.com/Qt-Widgets/QSimpleTickerGraph-CPU-Usage-History-Chart-Graph-Plot-Realtime
        作者收集了大量 qt 程序,是个宝库
