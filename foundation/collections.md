# 集合（Collections）

使用数组（arrays），字典（dictionaries），集合（sets），和专门的集合来存储跟迭代（iterate）一组对象（Objects）或者值（Values）。

***

### 主题

***

#### 基本集合

> ```
> struct Array
> ```
> 一个有序的随机访问（random-access）集合。

> ```
> struct Dictionary
> ```
> 一个元素是键值对的集合。

> ```
> struct Set
> ```
> 一个无序的唯一元素集合。

***

#### 索引（Indexes）

> ```
> struct IndexPath
> ```
> 一组索引的列表，一起来表示一个嵌套数组（nested arrays）的树中的一个特定位置的路径。

> ```
> struct IndexSet
> ```
> 一组唯一整型值的集合，以表示另一个集合中的元素的索引。

***

#### 专有集合（Specialized Sets）

> ```
> class NSCountedSet
> ```
> 一个不同对象的可变的无序集合，这些对象可能在集合中出现不止一次。

> ```
> class NSOrderedSet
> ```
> 一个唯一对象的静态有序集合。

> ```
> class NSMutableOrderedSet
> ```
> 一个唯一对象的动态有序集合。

***

#### 可清除集合（Purgeable Collections）

> ```
> class NSCache
> ```
> 一个可变的集合，你用来临时存储一些当资源紧张时可被回收的短时的键值对。

> ```
> class NSPurgeableData
> ```
> 一个包含字节的可变数据对象，当它们不再被使用时可以被丢弃。

***

#### 指针集合（Pointer Collections）<sup>1</sup>

> ```
> class NSPointerArray
> ```
> 一类类似于数组的集合，但有着更广泛的可用内存语义<sup>2</sup>。

> ```
> class NSMapTable
> ```
> 一个类似于字典（dictionary）的集合，但有着更广泛的可用内存语义。
> ```

> class NSHashTable
> ```
> 一个类似于 set 的集合，但有着更广泛的可用内存语义。

***

#### 迭代（Iteration）

> ```
> class NSEnumerator
> ```
> 一个抽象类，其子类用来枚举对象的集合，如数组和字典。

> ```
> protocol NSFastEnumeration
> ```
> 一个使对象适于快速枚举的协议（protocol）。

> ```
> struct NSFastEnumerationIterator
> ```

> ```
> struct NSIndexSetIterator
> ```
> 一个适用于枚举索引集合（index set）中元素的迭代器（iterator）。

> ```
> struct NSEnumerationOptions
> ```
> 枚举操作块（block enumeration operations）的选项。

> ```
> struct NSSortOptions
> ```
> 排序操作块（block sorting operations）的选项。

***

#### 特殊语义值（Special Semantic Values）

> ```
> class NSNull
> ```
> 一个单例对象（singleton object）用来表示集合对象中不允许 nil 值的空值。

> ```
> let NSNotFound: Int
> ```

> ```
> let NSNotFound: Int
> ```
> 一个用来表示一个请求项不能被找到或者不存在的值。

***

#### 基础

> [数字（Numbers）, 数据（Data）, 和基本值（Basic Values）](./foundation/numbers_data_and_basic_values.md)
>> 使用原始数据类型及其他基础类型贯穿整个Cocoa。

> [字符串（Strings）及文本（Text）](./foundation/strings_and_text.md)
>> 创建和处理Unicode字符，使用正则表达式查找模式（patterns），以及进行文本的自然语言分析。

> 日期（Dates）和时间（Times）
>> 比较日期和时间，以及进行日历和时区的运算。

> 单位（Units）和度量（Measurement）
>> 使用物理尺寸标注数字数量，以便允许在相关单位之间进行本地化（locale-aware）的格式化和转换。
>> Label numeric quantities with physical dimensions to allow locale-aware formatting and conversion between related units.

> 数据格式化（Data Formatting）
>> 数字，日期，度量（measurements）以及其他值与本地化（locale-aware）字符串表达式（string representations）之间进行相互转化。

> 过滤（Filters）和排序（Sorting）
>> 使用predicates，表达式（expressions）和排序描述式（sort descriptors）来检测在集合（collections）以及其他服务中的元素。


***

1.这个不知道通用的中文名称是什么，很少接触这个名称，如果大家有更正式的叫法可以告诉我。
2.这里原文是 with a broader range of available memory semantics 不太清楚具体意思。

<br>
<br>
<br>
<br>
<br>