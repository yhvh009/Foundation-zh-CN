# 数据格式化（Data Formatting）

在数字，日期，度量（measurements）以及其他值与本地化（locale-aware）字符串表达式（string representations）之间进行相互转化。

---

### 主题

---

#### 数字及货币（Currency）

> ```
> class NumberFormatter
> ```
> 一个格式化器，在数值跟其文字表达式之间相互转化。

---

#### 姓名（Names）

> ```
> class PersonNameComponentsFormatte
> ```
> 一个提供一个人姓名组成的本地化表达式的格式化器。

> ```
> struct PersonNameComponents
> ```
> 一个人姓名分离的部分，允许本地化（locale-aware）格式化。

---

#### 日期与时间（Datas and Times）

> ```
> class DateFormatter
> ```
> 一个在日期和其文字化表达式之间转化的格式化器。

> ```
> class DateComponentsFormatter
> ```
> 一个创建大量的时间的字符串表达式的格式化器。

> ```
> class DateIntervalFormatter
> ```
> 一个创建时间区间（time interval）的字符串表达式的格式化器。

> ```
> class ISO8601DateFormatter
> ```
> 一个在日期跟其IOS 8601字符串表达式之间进行相互转化的格式化器。

---

#### 数据大小（Data Sizes）

> ```
> class ByteCountFormatter
> ```
> 一个格式化器，能把一个字节计数值（byte count value）转化成一个有着恰当字节修饰（KB, MB, GB等）的本地化表达式。

---

#### 度量（Measurements）

> ```
> class MeasurementFormatter
> ```
> 一个提供单位（unit）和度量（measurement）的本地化表达式的格式化器。

---

#### 国际化（Internationalization）

> ```
> struct Locale
> ```
> 关于用于格式化数据表示的语言，文化和技术惯例的信息。（Information about linguistic, cultural, and technological conventions for use in formatting data for presentation.）

---

#### 自定义格式化器（Custom Formatters）

> ```
> class Formatter
> ```
> 一个抽象类，定义了关于对象创建，解释和验证一些值的文字化表达式的接口。

---

#### 弃用（Deprecated）

> ```
> class LengthFormatter
> ```
> 一个格式化器，提供了线性距离的本地化表达，如长度和高度。

> ```
> class MassFormatter
> ```
> 一个提供质量（mass）跟重量（weight）的本地化表达的格式化器。

> ```
> class EnergyFormatter
> ```
> 一个提供能量（energy）的本地化表达的格式化器。

---

### 参见

---

#### 基础

> [数字（Numbers）, 数据（Data）, 和基本值（Basic Values）](/foundation/numbers_data_and_basic_values.md)
>
> 使用原始数据类型及其他基础类型贯穿整个Cocoa。

> [字符串（Strings）及文本（Text）](/foundation/strings_and_text.md)
>
> 创建和处理Unicode字符，使用正则表达式查找模式（patterns），以及进行文本的自然语言分析。

> [集合（Collections）](/foundation/collections.md)
>
> 使用数组（arrays），字典（dictionaries），集合（sets），和专门的集合来存储跟迭代（iterate）一组对象（Objects）或者值（Values）。

> [日期（Dates）和时间（Times）](/foundation/dates_and_times.md)
>
> 比较日期和时间，以及进行日历和时区的运算。

> [单位（Units）和度量（Measurement）](/foundation/units_and_measurement.md)
>
> 使用物理尺寸标注数字数量，以便允许在相关单位之间进行本地化（locale-aware）的格式化和转换。  
> Label numeric quantities with physical dimensions to allow locale-aware formatting and conversion between related units.

> 过滤（Filters）和排序（Sorting）
>
> 使用predicates，表达式（expressions）和排序描述式（sort descriptors）来检测在集合（collections）以及其他服务中的元素。
