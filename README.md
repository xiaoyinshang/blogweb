<img src="https://s3.bmp.ovh/imgs/2022/07/25/008f709a62f414a6.png" alt="logo" style="zoom:67%;" />

# ArcGIS

## 错误：无法粘贴<feature class>空间参考不匹配

**错误消息**

将要素类从地理数据库粘贴到要素数据集中将返回以下消息：

“无法粘贴 <要素类> 空间参考不匹配”

![O-Image](https://raw.githubusercontent.com/xiaoyinshang/blogImage/main/202209151659592.png)

**原因**

当源和目标要素类之间存在不同的范围、分辨率和容差值时，将会出现此问题。

**解决方案或解决方法**

错误消息的后半部分“空间参考不匹配”适用于 X 和 Y 坐标、XY 容差、XY 分辨率以及 Z 或 M 分辨率。 要确保数据在所有这些区域中具有相同的属性，请使用以下步骤：

1. 将数据加载到地理数据库中的相同要素数据集。
2. 使用从源要素类导入的坐标系来创建新要素数据集。
3. 要将要素类导入或复制到新创建的要素数据集，请使用“要素类至要素类”或“要素类至地理数据库”地理处理工具。



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
