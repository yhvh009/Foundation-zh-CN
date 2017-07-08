# 日期和时间

比较日期和时间，以及进行日历和时区的运算。

***

### 主题

***

#### 日期展示（Date Representations）

> ```
> struct Date
> ```
> 一个具体的时间点，独立于任何日历或时区

> ```
> struct DateInterval
> ```
> 具体的开始日期跟结束日期之间的时间跨度

> ```
> typealias TimeInterval
> ```
> 几秒钟

***

#### 日历计算（Calendrical Calculations）

> ```
> struct DateComponents
> ```
> 以日历系统和时区中要评估的单位（如年，月，日，小时和分钟）所指定的日期或时间。(A date or time specified in terms of units (such as year, month, day, hour, and minute) to be evaluated in a calendar system and time zone.)

> ```
> struct Calendar
> ```
> 一个关于日历单位（如世纪，年和周）与绝对时间点（absolute points in time）之间关系的定义，提供日期的计算和比较的特性。

> ```
> struct TimeZone
> ```
> 关于特定地理地区上的标准时间约定的信息。

***

#### 日期格式化（Date Formatting）

> ```
> class DateFormatter
> ```
> 一个在日期和其文字表达之间转化的转化器。

> ```
> class DateComponentsFormatter
> ```
> 一个创建大量时间的字符串表达的转化器。

> ```
> class DateIntervalFormatter
> ```
> 一个创建time interval的字符串表达的转化器。

> ```
> class ISO8601DateFormatter
> ```
> 一个在日期和其ISO 8601字符串表达之间转化的转化器。

***

#### 国际化（Internationalization）

> ```
> struct Locale
> ```
> 关于用于格式化数据表示的语言，文化和技术惯例的信息。（Information about linguistic, cultural, and technological conventions for use in formatting data for presentation.）

***

### 参见

***

#### 基础

> [数字（Numbers）, 数据（Data）, 和基本值（Basic Values）](./foundation/numbers_data_and_basic_values.md)
>
> 使用原始数据类型及其他基础类型贯穿整个Cocoa。

> [字符串（Strings）及文本（Text）](./foundation/strings_and_text.md)
>
> 创建和处理Unicode字符，使用正则表达式查找模式（patterns），以及进行文本的自然语言分析。

> [集合（Collections）](./foundation/collections.md)
>
> 使用数组（arrays），字典（dictionaries），集合（sets），和专门的集合来存储跟迭代（iterate）一组对象（Objects）或者值（Values）。

> [单位（Units）和度量（Measurement）](./foundation/units_and_measurement.md)
>
> 使用物理尺寸标注数字数量，以便允许在相关单位之间进行本地化（locale-aware）的格式化和转换。  
> Label numeric quantities with physical dimensions to allow locale-aware formatting and conversion between related units.

> 数据格式化（Data Formatting）
>
> 数字，日期，度量（measurements）以及其他值与本地化（locale-aware）字符串表达式（string representations）之间进行相互转化。

> 过滤（Filters）和排序（Sorting）
>
> 使用predicates，表达式（expressions）和排序描述式（sort descriptors）来检测在集合（collections）以及其他服务中的元素。
