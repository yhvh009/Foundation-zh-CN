# 字符串和文本

创建和处理Unicode字符，使用正则表达式查找模式（patterns），以及进行文本的自然语言分析。

***

### 主题

***

#### 字符串

> ```
> struct String
> ```
> 一个是字符集合的Unicode字符串值。

***

#### 有元数据的字符串（Strings with Metadata）

> ```
> class NSAttributedString
> ```
> 一个它部分文本有一些相关属性（如视觉样式，超链接，或可访问数据）的字符串。

> ```
> class NSMutableAttributedString
> ```
> 一个同样包含着一些跟它不同部分的文本有关的属性（如视觉样式，超链接，或可访问数据）的可变字符串对象。

***

#### 字符（Characters）

> ```
> struct CharacterSet
> ```
> 一组在搜索操作中使用的Unicode字符值。

> ```
> typealias UnicodeScalar
> ```

***

#### 自然语言处理（Natural Language Processing）

> ```
> class NSLinguisticTagger
> ```
> 分析自然语言来标记词性和词汇类，识别专有名称，执行词汇化，并确定文本的语言和脚本（正字法）。（Analyze natural language to tag part of speech and lexical class, identify proper names, perform lemmatization, and determine the language and script (orthography) of text.）

***

#### 模式匹配（Pattern Matching）

> ```
> class Scanner
> ```
> 类集群（class cluster）的抽象父类（abstract superclass），用于从字符串中扫描值。

> ```
> class NSRegularExpression
> ```
> 你用于Unicode字符串的编译的正则表达式（compiled regular expression）的一种不变的表达式（An immutable representation）。

> ```
> class NSDataDetector
> ```
> 一种专门的正则表达式对象，用于匹配预定义的数据模式（predefined data patterns）的自然语言文本。。

> ```
> class NSTextCheckingResult
> ```
> 在分析文本块期间发现的文本内容的结果（occurrence<sup>1</sup>），例如当匹配正则表达式时。

> ```
> let NSNotFound: Int
> ```
> 一个表示请求项目无法找到或者不存在的值。

***

#### 拼写和语法（Spelling and Grammar）

> ```
> class NSSpellServer
> ```
> 一个你的应用用来向在系统中运行的其他应用提供拼写检查服务的服务器。

> ```
> protocol NSSpellServerDelegate
> ```
> 一个被spell server的delegate实现的可选方法。

***

#### 本地化（Localization）

> ```
> struct Locale
> ```
> 关于用于格式化数据表示的语言，文化和技术惯例的信息。（Information about linguistic, cultural, and technological conventions for use in formatting data for presentation.）

> ```
> class NSOrthography
> ```
> 一个通常用于拼写和语法检查的一段文本的语言内容的描述。

> ```
> func NSLocalizedString(String, tableName: String?, bundle: Bundle, value: String, comment: String)
> ```
> 返回一个本地化字符串，如果没有指定bundle则使用主bundle。

***

### 参见

***

#### 基础

> [数字（Numbers）, 数据（Data）, 和基本值（Basic Values）](./numbers_data_and_basic_values.md)
>> 使用原始数据类型及其他基础类型贯穿整个Cocoa。

> [集合（Collections）](./collections.md)
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

***

1.原文是An occurrence of textual content，感觉occurrence翻译成出现不好理解，就翻译成结果了。
