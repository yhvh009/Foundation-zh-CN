# 数字（Numbers）, 数据（Data）, 和基本值（Basic Values）
使用原始数据类型及其他基础类型贯穿整个Cocoa。

### 主题

***

#### 数字

> ```
> struct Int
> ```
> 有符号的整型类型

> ```
> struct Double
> ```
> 双精度的浮点值类型。

> ```
> struct Decimal
> ```
> 表示10进制数的类型。

> ```
> class NumberFormatter
> ```
> 转化数值与其文字表示的formatter。

***

#### 二进制数据

> ```
> struct Data
> ```
> 内存中的字节buffer。

***

#### URLs

> ```
> struct URL
> ```
> 标识资源位置的值，如在远程服务器的一项或本地文件的路径。

> ```
> struct URLComponents
> ```
> 一个解析或构建URL到它们的组成成分的结构。

> ```
> struct URLComponents
> ```
> 一个URL的请求部分的单一键值对（single name-value pair）。

***

#### 唯一标识（Unique Identifiers）

> ```
> struct UUID
> ```
> 可用于识别类型，接口（interfaces）和其他项的通用唯一值。

***

#### 几何

> ```
> struct CGFloat
> ```
> 在Core Graphics和其他相关框架中表示浮点标量值的基本类型。

> ```
> typealias NSPoint
> ```
> 一个在笛卡尔坐标系中的点。

> ```
> typealias NSSize
> ```
> 一个二维尺寸

> ```
> typealias NSRect
> ```
> 一个长方形。

> ```
> struct AffineTransform
> ```
> 一个图形坐标转换。

> ```
> struct NSEdgeInsets
> ```
> 一个关于两个矩形之间的距离的描述。

***

#### 范围（Ranges）

> ```
> typealias NSRange
> ```
> 一个用来描述一个系列（series）（如字符串（string）中的字符（characters）或者数组（array）中的对象（objects））的一部分的结构。

***

### 参见

***

#### 基础

> [字符串（Strings）及文本（Text）]((./strings_and_text.md)
)
>> 创建和处理Unicode字符，使用正则表达式查找模式（patterns），以及进行文本的自然语言分析。

> 集合（Collections）
>> 使用数组（arrays），字典（dictionaries），集合（sets），和专门的集合来存储跟迭代（iterate）一组对象（Objects）或者值（Values）。

> 日期（Dates）和时间（Times）
>> 比较日期和时间，以及进行日历和时区的运算。

> 单位（Units）和度量（Measurement）
>> 使用物理尺寸标注数字数量，以便允许在相关单位之间进行本地化（locale-aware）的格式化和转换。  
>> Label numeric quantities with physical dimensions to allow locale-aware formatting and conversion between related units.

> 数据格式化（Data Formatting）
>> 数字，日期，度量（measurements）以及其他值与本地化（locale-aware）字符串表达式（string representations）之间进行相互转化。

> 过滤（Filters）和排序（Sorting）
>> 使用predicates，表达式（expressions）和排序描述式（sort descriptors）来检测在集合（collections）以及其他服务中的元素。
