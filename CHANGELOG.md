# 1.0.5版本

1. 增加回测爆仓检查
2. 策略模板增加合约乘数查询函数get_size
3. 加载日线和小时线数据时，不使用分段加载


# 1.0.4版本

1. 修复pos_data/target_data从缓存文件恢复数据，导致defaultdict变成dict的问题
2. 改为使用OmsEngine提供的OffsetConverter组件
3. 增加查询历史数据时的日志输出


# 1.0.3版本

1. 组合策略模板，增加持仓目标调仓交易模式
2. 修复部分情况下由于K线切片行情缺失，导致的回测计算盈亏错误

# 1.0.2版本

1. 使用zoneinfo替换pytz库
2. 调整安装脚本setup.cfg，添加Python版本限制

# 1.0.1版本

1. 将模块的图标文件信息，改为完整路径字符串
2. 改为使用PySide6风格的信号QtCore.Signal