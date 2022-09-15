<img src="https://s3.bmp.ovh/imgs/2022/07/25/008f709a62f414a6.png" alt="logo" style="zoom:67%;" />

# ArcGIS

## 错误：无法粘贴<feature class>空间参考不匹配

### 错误消息

将要素类从地理数据库粘贴到要素数据集中将返回以下消息：

“无法粘贴 <要素类> 空间参考不匹配”
![[O-Image] Failed to paste The spatial references do not match](https://gitee.com/xiaoyin1111/typora_pic_load/raw/master/typora_pic/00N39000003LL24-0EM39000000wdWe.png)

### 原因

当源和目标要素类之间存在不同的范围、分辨率和容差值时，将会出现此问题。

### 解决方案或解决方法

错误消息的后半部分“空间参考不匹配”适用于 X 和 Y 坐标、XY 容差、XY 分辨率以及 Z 或 M 分辨率。 要确保数据在所有这些区域中具有相同的属性，请使用以下步骤：

1. 将数据加载到地理数据库中的相同要素数据集。
2. 使用从源要素类导入的坐标系来创建新要素数据集。
3. 要将要素类导入或复制到新创建的要素数据集，请使用“要素类至要素类”或“要素类至地理数据库”地理处理工具。

## 如何把ArcGIS ‘图例’下面的图层名称及字段名称删除

使用[ArcGIS](http://www.lgwimonday.cn/archives/tag/arcgis/) 自动插入图例时候，经常会遇到很多问题，而修改图例样式的时候又比较耗费时间，所以很多时候，大家往往会直接将图例转成graphics，直接以图形的方式编辑图例，这样会带来一个严重的问题，那就是一旦修改了地图的颜色、专题样式等内容时，必须再重新制作图例。我在研究了图例功能后，做了如下总结。

1、插入图例后，如果有不满意的地方，不要着急重新生成图例或者转为图形，右击图例->属性，一般你想要的结果都可以在这里面修改

2、删除legend下面的图层名称及字段名称，也可以在属性对话框中进行，点击“items”选项卡，选择你需要修改的图层，点击“style...”，选择你想要的样式即可。这样做出来的图例可以反复使用，更改了地图样式后，图例也会自动更新。

![image-20220317110601016](https://gitee.com/xiaoyin1111/typora_pic_load/raw/master/typora_pic/image-20220317110601016.png)

![如何把ArcGIS 的图例legend下面的图层名称及字段名称删除](https://gitee.com/xiaoyin1111/typora_pic_load/raw/master/typora_pic/clip_image002.jpg)



# Color

# Github

# Jupyter Notebook

# Mapbox

# Markdown

# Mathtype

# MySQL

# Navicat

# PyCharm

# Python

# Typora

# Zotero

# Pandas
