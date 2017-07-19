# 归档（Archives）和序列化（Serialization）

在对象（objects），值（values）与property list，JSON及其他扁平的二进制表现形式（flat binary representations）之间相互转化。

### 主题

---

#### 第一步（First Steps）

> Encoding and Decoding Custom Types
>
> 使您的数据类型可编码和解码，以便与外部表示（external representation）（如JSON）兼容。

> ```
> typealias Codable（Beta）
> ```
> 一种可以把自己转化成外部表示（external representation）和从其转化的类型。

> ```
> protocol NSCoding
> ```
> 一种使对象能够进行编码和解码以进行归档（archiving）和分发（distribution）的协议。

> ```
> protocol NSSecureCoding
> ```
> 一个能以一种方式进行编码和解码来有强壮性对抗对象替代攻击的协议。（A protocol that enables encoding and decoding in a manner that is robust against object substitution attacks.）

---

#### JSON

> {} Using JSON with Custom Types
>
> 演示在Swift中编码和解码不同种类的JSON的方法。

> ```
> class JSONEncoder
> ```
> 一个将数据类型的实例编码为JSON对象的对象。

> ```
> class JSONDecoder
> ```
> 一个把JSON对象解码成数据类型的实例的对象。

> ```
> class JSONSerialization
> ```
> 一个在JSON和等效的Foundation对象之间进行相互转化的对象。

---

#### 属性列表（Property Lists）

> ```
> class PropertyListEncoder
> ```
> 一个把数据类型的实例编码成属性列表（property list）的对象。

> ```
> class PropertyListDecoder
> ```
> 一个把属性列表（property list）解码成数据类型的实例的对象。

> ```
> class PropertyListSerialization
> ```
> 一个在属性列表（property list）和几个序列化表示之一之间进行转换的对象。

---

#### XML

> XML Processing and Modeling
>
> 解析XML文档。

---

#### 键归档器（Keyed Archivers）

> ```
> class NSKeyedArchiver
> ```
> 一个编码器，将对象的数据存储到由键引用的归档（archive referenced by keys）。

> ```
> protocol NSKeyedArchiverDelegate
> ```
> keyed archiver的代理（delegate）实现的可选方法。

> ```
> class NSKeyedUnarchiver
> ```
> 一个解码器，用于从由键引用的归档中恢复数据。

> ```
> protocol NSKeyedUnarchiverDelegate
> ```
> keyed unarchiver的代理（delegate）实现的可选方法。

> ```
> class NSCoder
> ```
> 一个抽象类（abstract class），用作可以归档和分发其他对象的对象的基础。

---

#### 弃用（Deprecated）

> ```
> class NSArchiver
> ```
> 一个将对象的数据存储到归档的编码器.

> ```
> class FileManager
> ```
> 一个从归档恢复数据的解码器。

---

### 参见

---

#### 文件及数据持久化

> [文件系统](/foundation/file_system.md)
>
> 在文件系统中创建，读取，写入以及检查文件跟文件夹。

> 配置（Preferences）
>
> 持久化保存用来设置（configure）你的应用的域名范围（domain-scoped）内的若干信息。

> Spotlight
>
> 搜索本地设备内的文件及其他内容，以及建立你用来搜索的应用内容的索引。

> iCloud
>
> 管理通过用户的iCloud设备来自动同步的文件及键值对（key-value）数据。
