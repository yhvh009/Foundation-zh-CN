# Foundation

访问基本数据类型，集合（collections），和操作系统服务以定义应用程序的基本功能层。

> ###### SDKs
> iOS 2.0+  
> macOS 10.0+  
> tvOS 9.0+  
> watchOS 2.0+  

***

### 概览
Foundation框架提供了应用程序的基本功能层以及frameworks，数据存储及持久化，文本处理，日期及时间运算，分类及过滤，以及网络处理。Foundation定义的这些类（classes），协议（protocols）以及数据类型被用来贯穿macOS，iOS，watchOS和tvOS SDKs。

### 主题

***

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

> [过滤（Filters）和排序（Sorting）](/foundation/filters_and_sorting.md)
>
> 使用谓词（predicates），表达式（expressions）和排序描述式（sort descriptors）来检测在集合（collections）以及其他服务中的元素。

***

#### 应用程序支持

> [任务管理（Task Management）](/foundation/task_management.md)
>
> 管理你应用程序的工作以及它们与用户和系统之间的交互。

> [资源（Resources）](/foundation/resources.md)
>
> 访问你应用程序绑定（bundled）的assets和其他数据。

> [通知（Notifications）](/foundation/notifications.md)
>
> 设计广播消息及订阅广播的模式

> [应用程序拓展（Extension）支持](/foundation/app_extension_support.md)
>
> 管理应用程序拓展跟它的主程序（hosting app）之间的交互。

> [错误（Errors）及异常（Exceptions）](/foundation/errors_and_exceptions.md)
>
> 响应你在api交互中产生的问题情况，微调你的应用以便更好的调试。

> [脚本支持（Scripting Support）](/foundation/scripting_support.md)
>
> 允许用户使用AppleScript和其他自动化技术来控制你的应用，或者在你的应用中运行脚本（scripts）。

***

#### 文件及数据持久化

> [文件系统](/foundation/file_system.md)
>
> 在文件系统中创建，读取，写入以及检查文件跟文件夹。

> 存档（Archives）和序列化（Serialization）
>
> 在对象（objects），值（values）与property list，JSON及其他扁平的二进制表现形式（flat binary representations）之间相互转化。

> 配置（Preferences）
>
> 持久化保存用来设置（configure）你的应用的域名范围（domain-scoped）内的若干信息。

> Spotlight
>
> 搜索本地设备内的文件及其他内容，以及建立你用来搜索的应用内容的索引。

> iCloud
>
> 管理通过用户的iCloud设备来自动同步的文件及键值对（key-value）数据。

***

#### 网络（Networking）

> URL加载系统（URL Loading System）
>
> 使用标准Internet协议与URL进行交互及与服务端通信。

> Bonjour
>
> 本地网络上容易发现的广告服务，或者发现其他人的广告服务。  
> Advertise services for easy discovery on local networks, or discover services advertised by others.

***

#### 底层工具（Low-Level Utilities）

> XPC
>
> 管理进程间的安全通信。

> Object Runtime
>
> 获取Object-C特性，Cocoa设计模式以及Swift一体化的底层支持。

> 进程（Processes）与线程（Threads）
>
> 管理你应用与主操作系统及其他进程之间的交互，以及实现底层并发特性（low-level concurrency features）。

> 流（Streams），Sockets和端口（Ports）
>
> 使用底层Unix特性来管理文件，进程及网络的输入和输出。
***

#### 结构体（Structures）

```
struct NSFileProviderServiceName
```

```
struct NSTextCheckingKey
```

***

#### 类（Classes）

```
class NSFileProviderService
```

***

#### 参考（Reference）

> Foundation常量（Constants）

> Foundation数据类型
>
> 此文档描述Foundation框架中出现的数据类型及常量。
