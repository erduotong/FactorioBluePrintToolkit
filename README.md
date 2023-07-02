# FactorioBluePrintToolkit

#### 这是一个处理[异星工场](https://www.factorio.com/)的蓝图和蓝图书的软件
## 它可以做什么?
* 将蓝图书/蓝图的字符串转换成json(dict)方便编辑
* 将json(dict)形式的蓝图转换会蓝图字符串
* 递归解压一个蓝图书字符串，并且最终只保留蓝图作为文件,蓝图书加载成文件夹
* 递归打包一个蓝图文件夹回到蓝图书

## 功能细节


从文件递归打包成蓝图书的时候只考虑文件名而不是其中的内容