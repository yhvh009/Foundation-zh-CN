# 脚本支持（Scripting Support）

允许用户使用AppleScript和其他自动化技术来控制你的应用，或者在你的应用中运行脚本（scripts）。

---

### 主题

---

#### 脚本执行（Script Execution）

> ```
> class NSAppleScript
> ```
> 一个提供加载（load），编译（compile）和执行（execute）脚本的能力的对象。

---

#### 苹果事件处理（Apple Event Handling）

> ```
> class NSAppleEventDescriptor
> ```
> 一个苹果事件描述符（Apple event descriptor）数据类型的包装（wrapper）。

> ```
> class NSAppleEventManager
> ```
> 一套机制，给苹果事件的特定类型注册处理惯例，以及分发事件到这些控制器。（A mechanism for registering handler routines for specific types of Apple events and dispatching events to those handlers.）

---

#### 脚本命令（Script Commands）

> ```
> class NSScriptCommand
> ```
> 一个自包含（self-contained）的脚本声明（statement）。

> ```
> class NSQuitCommand
> ```
> 一个退出特定应用的命令。

> ```
> class NSSetCommand
> ```
> 一个设置一或多个属性（attributes）或关系到一或多个值（values）的命令。

> ```
> class NSMoveCommand
> ```
> 一个移动一或多个可编写脚本（scriptable）对象的命令。

> ```
> class NSCreateCommand
> ```
> 一个创建一个可编写脚本对象的命令。

> ```
> class NSDeleteCommand
> ```
> 一个删除一个可编写脚本对象的命令。

> ```
> class NSExistsCommand
> ```
> 一个确定一个可编写脚本对象是否存在的命令。

> ```
> class NSCloneCommand
> ```
> 一个克隆（clone）一或多个可编写脚本对象的命令。

> ```
> class NSCountCommand
> ```
> 一个用于计算指定对象容器中指定类的对象数的命令。

> ```
> class NSCloseCommand
> ```
> 一个关闭一或多个可编写脚本对象的命令。

---

#### 对象说明符（Object Specifiers）

> ```
> class NSScriptObjectSpecifier
> ```
> 一个用于展示自然语言表达式（natural language expressions）的抽象类（abstract class）。

> ```
> class NSPropertySpecifier
> ```
> 一个用于简单属性值，一对一关系或多对象关系的所有元素的说明符。

> ```
> class NSPositionalSpecifier
> ```
> 一个用于容器中相对于容器中另一个对象的插入点的说明符。

> ```
> class NSRandomSpecifier
> ```
> 一个对于集合中任意对象的说明符，如果不是一对多关系，则是唯一对象。（A specifier for an arbitrary object in a collection or, if not a one-to-many relationship, the sole object.）

> ```
> class NSRangeSpecifier
> ```
> 一个用于在一个容器中的一个范围内的对象的说明符。

> ```
> class NSUniqueIDSpecifier
> ```
> 一个通过unique ID，对在一个在集合（或容器）中的对象的说明符。

> ```
> class NSWhoseSpecifier
> ```
> 一个用于指示在集合中符合条件的每个对象的说明符。（A specifier that indicates every object in a collection matching a condition.）

> ```
> class NSNameSpecifier
> ```
> 一个通过名字，对在一个集合（或容器）中的对象的说明符。

> ```
> class NSMiddleSpecifier
> ```
> 一个对于在集合中中间的对象的说明符，如果不是一对多关系，则是唯一对象。（A specifier indicating the middle object in a collection or, if not a one-to-many relationship, the sole object.）

> ```
> class NSIndexSpecifier
> ```
> 一个表示具有索引号的集合（或容器）中的对象的说明符。

> ```
> class NSRelativeSpecifier
> ```
> 一个指示符，通过其相对于另一个对象的位置来指示集合中的对象。

---

#### 脚本字典描述符（Script Dictionary Description）

> ```
> class NSScriptSuiteRegistry
> ```
> 一个应用在运行时（runtime）的关于脚本语言信息（scriptability information）的最高级库（top-level repository）。

> ```
> class NSScriptClassDescription
> ```
> 一个macOS应用支持的可编写脚本类（scriptable class）。

> ```
> class NSClassDescription
> ```
> 一个抽象类，提供接口支持查询一个类的关系（relationships）或属性（properties）。

> ```
> class NSScriptCommandDescription
> ```
> 一个macOS应用支持的脚本命令。

---

#### 对象匹配测试（Object Matching Tests）

> ```
> class NSScriptWhoseTest
> ```
> 一个抽象类，它提供了一次一个或一组地测试说明符的基础。

> ```
> class NSSpecifierTest
> ```
> 一个对象说明符跟一个测试对象之间的比较关系。

> ```
> class NSLogicalTest
> ```
> 一个一或多个说明符测试直接的逻辑组合（logical combination）。

---

#### NSObject脚本支持（Script Support）

> NSComparisonMethods
>
> 一个用于执行说明符测试的默认比较方法的集合。

> NSScriptingComparisonMethods
>
> 一个用于比较脚本对象的方法的集合。

> NSScriptKeyValueCoding
>
> 一个提供附加能力的方法集合，用于处理键值对编码（key-value coding）。

> NSScriptObjectSpecifiers
>
> 一个提供附加对象说明符功能的方法集合。

> ```
> class NSScriptCoercionHandler
> ```
> 一套转化一类脚本对象到另一类的机制。

> ```
> class NSScriptExecutionContext
> ```
> 当前执行的脚本命令的上下文（context）。

---

### 参见

---

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
