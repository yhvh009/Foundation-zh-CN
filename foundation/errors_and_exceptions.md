# 错误（Errors）及异常（Exceptions）

响应你在api交互中产生的问题情况，微调你的应用以便更好的调试。

---

### 主题

---

#### 用户相关错误（User-Relevant Errors）

> ```
> protocol Error
> ```
> 表示一个可以被抛出的错误值的类型。

> ```
> class NSError
> ```
> 关于错误情况的信息包括域名（domain），特定域的错误码（domain-specific error code），和特定应用信息（application-specific information）。

> ```
> protocol LocalizedError
> ```
> 一个专门的错误，提供本地化的信息来描述错误和它为什么产生。

> ```
> protocol RecoverableError
> ```
> 一个可能恢复的专门的错误，通过展示一些潜在的恢复选项给用户。（A specialized error that may be recoverable by presenting several potential recovery options to the user.）

> ```
> protocol CustomNSError
> ```
> 一个提供域名（domain），错误码（error code）和用户信息字典（user-info dictionary）的专门的错误。

---

#### 断言（Assertions）

> ```
> class NSAssertionHandler
> ```
> 一个在控制台（console）中展示断言（assertion）的日志（log）的对象。

---

#### 异常（Exceptions）

> ```
> class NSException
> ```
> 一个对象，展示打断（interrupts）正常的程序执行流（normal flow of program execution）的一个特殊情况（special condition）。

---

#### 诊断及调试（Diagnostics and Debugging）

> ```
> func NSLogv(String, CVaListPointer)
> ```
> 记录一个错误信息（error message）的日志到苹果系统日志设施（Apple System Log facility）中。

> ```
> func NSLog(String, CVarArg...)
> ```
> 记录一个错误信息（error message）的日志到苹果系统日志设施（Apple System Log facility）中。

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

> 脚本支持（Scripting Support）
>
> 允许用户使用AppleScript和其他自动化技术来控制你的应用，或者在你的应用中运行脚本（scripts）。
