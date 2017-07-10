# 过滤（Filters）和排序（Sorting）

使用谓词（predicates），表达式（expressions）和排序描述式（sort descriptors）来检测在集合（collections）以及其他服务中的元素。

---

### 主题

---

#### 过滤（Filtering）

> ```
> class NSPredicate
> ```
> 用于约束搜索或者内存过滤的逻辑条件。（The logical conditions used to constrain a search either for a fetch or for in-memory filtering.）

> ```
> class NSExpression
> ```
> 用于比较谓词的表达式。（An expression for use in a comparison predicate.）

> ```
> class NSComparisonPredicate
> ```
> 一个你用来比较表达式的特定谓词。（A specialized predicate that you use to compare expressions.）

> ```
> class NSCompoundPredicate
> ```
> 一个特定的谓词，用来评估其他谓词的逻辑组合。（A specialized predicate that evaluates logical combinations of other predicates.
）

---

#### 排序（Sorting）

> ```
> class NSSortDescriptor
> ```
> 一个不可变的描述，关于如何基于一个所有对象共有的属性（property）来进行对象集合的排序。

> ```
> enum ComparisonResult
> ```
> 表明排序顺序的常量。

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

> [数据格式化（Data Formatting）](/foundation/data_formatting.md)
>
> 在数字，日期，度量（measurements）以及其他值与本地化（locale-aware）字符串表达式（string representations）之间进行相互转化。
