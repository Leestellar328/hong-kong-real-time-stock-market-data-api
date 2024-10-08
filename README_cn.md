> [English](./README.md) | [中文](./README_cn.md)

# AllTick实时港股行情数据API

#### AllTick 实时香港股票市场数据API-港交所行情接口-低延迟WebSocket-逐笔推送高频数据接口

欢迎使用 AllTick 提供的**实时香港股票市场数据API**。此 API 提供来自香港交易所（HKEX）的高频实时股票行情数据，专为开发者、交易员、量化分析师、CFD交易所设计，满足算法交易、市场分析等需求，确保数据的可靠性和低延迟。

## 功能
- 实时股票数据：获取来自香港交易所的实时更新。
- 全面数据：包含买/卖价、成交量、最新价格和市场深度。
- 低延迟：优化设计，适用于高频交易和快速数据处理。
- 可扩展性：支持多个 API 请求并发，非常适合交易平台使用。
- 可定制查询：根据需求获取特定股票数据或市场整体概况。

## 使用场景
- 算法交易
- 量化投资策略
- 市场研究与分析
- 实时股票价格跟踪
- 股票交易平台、CFD交易所

## 为什么选择AllTick港股行情数据接口

AllTick 为获取实时金融市场数据提供了卓越的解决方案，专注于数据的准确性、速度和可靠性。

**1. 可靠的市场数据来源**

AllTick 以数据质量和系统稳定性为首要任务，平台拥有 99.95% 的服务级别协议（SLA），远超行业标准，确保为用户提供最高水平的可用性和性能。

**2. 广泛的市场覆盖** 

AllTick 支持超过 100,000 种金融产品代码，涵盖全球多个交易所的多种资产类别。无论是股票、外汇、期货还是加密货币的数据，AllTick 都能满足您的需求。

**3. 超低延迟的实时数据** 

我们的平台通过 WebSocket 提供超低延迟的实时数据流，平均延迟仅约为 170 毫秒，非常适合高频交易和实时应用场景。

**4. 逐笔推送的高频数据** 

AllTick 提供逐笔推送的高频数据，实时推送每一个交易报价。每个报价都可追溯，并与交易所的实时行情完全同步，确保您始终掌握最准确、最新的市场信息。

## 官网
[https://alltick.co](https://alltick.co)

  

## 接入指南
- [接入指南](./access_guide_cn.md)
## 接口介绍
### 错误码说明
- [错误码说明](./error_code_description_cn.md)
### 产品code列表
- [产品code列表-A股](./product_code_list_A_stock_cn.md)
- [产品code列表-港股](./product_code_list_HK_stock_cn.md)
- [产品code列表-加密货币(数字币)](./product_code_list_cryptocurrency_cn.md)
- [产品code列表-美股](./product_code_list_US_stock_cn.md)
- [产品code列表-商品(贵金属)](./product_code_list_commodities_gold_cn.md)
- [产品code列表-外汇](./product_code_list_forex_cn.md)

### http接口
- [行情API地址说明](./http_interface/api_address_description_cn.md)
- [接口限制](./http_interface/interface_limitation_cn.md)
- [通用标准头](./http_interface/common_standard_header_cn.md)
- [获取最新成交报价查询](./http_interface/latest_transaction_price_query_cn.md)
- [最新盘口报价查询](./http_interface/latest_order_book_price_query_cn.md)
- [K线查询](./http_interface/kline_query_cn.md)
- [批量查询产品最新K线](./http_interface/batch_kline_query_cn.md)

### websocket接口
- [行情API地址说明](./websocket_interface/api_address_description_cn.md)
- [接口限制](./websocket_interface/interface_limitation_cn.md)
- [通用标准头](./websocket_interface/common_standard_header_cn.md)
- [心跳](./websocket_interface/heartbeat_cn.md)
- [实时成交报价订阅](./websocket_interface/realtime_transaction_quote_subscription_cn.md)
- [实时盘口报价订阅](./websocket_interface/realtime_order_book_quote_subscription_cn.md)
- [取消实时报价订阅](./websocket_interface/cancel_realtime_quote_subscription_cn.md)

## 免费token获取
- [token申请](./token_application_cn.md)

## 使用示例,超简单上手
### php:

- [http请求示例](./example/php/php_http_curl.php)
- [websocket请求示例](./example/php/php_websocket_workerman.php)

### python:

- [http请求示例](./example/python/http_python_example.py)
- [websocket请求示例](./example/python/websocket_python_example.py)

### go:
- [http请求示例](./example/go/http_go_example.go)
- [websocket请求示例](./example/go/websocket_go_example.go)

### java:
- [http请求示例](./example/java/HttpJavaExample.java)
- [websocket请求示例](./example/java/WebSocketJavaExample.java)


## 联系我们
Email: support@alltick.co

Skype: [https://join.skype.com/invite/xokTc695huNu](https://join.skype.com/invite/xokTc695huNu)

Telegram: [https://t.me/alltick001](https://t.me/alltick001)

## 作者：AllTick

## 其他作品
官网:[https://alltick.co](https://alltick.co)
