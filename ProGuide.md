YTKNetwork 使用高级教程
===

本教程将讲解 YTKNetwork 的高级功能的使用。

## YTKUrlFilterProtocol 接口

YTKUrlFilterProtocol 接口用于实现对网络请求URL或参数的重写，例如可以统一为网络请求加上一些参数，或者修改一些路径。 

例如：在猿题库中，我们需要为每个网络请求加上客户端的版本号作为参数。所以我们实现了如下一个YTKUrlArgumentsFilter类，实现了 `YTKUrlFilterProtocol` 接口:

TODO: 详细的示例

## YTKBatchRequest 类

YTKBatchRequest 类：用于方便地发送批量的网络请求，YTKBatchRequest是一个容器器，它可以放置多个 `YTKRequest` 子类，并统一处理这多个网络请求的成功和失败。

TODO：详细的示例

## YTKChainRequest 类

用于管理有相互依赖的网络请求，它实际上最终可以用来管理多个拓扑排序后的网络请求。

TODO：详细的示例
