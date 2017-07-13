# 应用程序拓展（Extension）支持

管理应用程序拓展跟它的主程序（hosting app）之间的交互。

---

### 主题

---

#### 拓展支持（Extension Support）

> ```
> protocol NSExtensionRequestHandling
> ```
> 一个接口，应用拓展用来回应一个主应用（host app）的请求(request)。

> ```
> class NSExtensionContext
> ```
> 调用应用扩展的主应用的上下文。（The host app context from which an app extension is invoked.）

---

#### 附件（Attachments）

> ```
> class NSItemProvider
> ```
> 一个项目的提供者（item provider）为了进程间通过拖拽（drag and drop）或复制粘贴（copy/paste）来传输数据或文件，或者从一个主应用到一个应用拓展。

> ```
> class NSExtensionItem
> ```
> 一个代表着对一个扩展起作用的项目的不同方面的值的不可变集合（An immutable collection of values representing different aspects of an item for an extension to act upon.）

---

#### 文件提供者（File Providers）

> ```
> struct NSFileProviderMessageInterfaceName（Beta）
> ```

---

#### 主应用交互（Host App Interaction）

> ```
> class NSUserActivity
> ```
> 一个关于你的应用在某个瞬间的状态的表达式。

> ```
> protocol NSUserActivityDelegate
> ```
> 一个接口，一个用户活动实例通过它来通知其代理更新。

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

> 错误（Errors）及异常（Exceptions）
>
> 响应你在api交互中产生的问题情况，微调你的应用以便更好的调试。

> 脚本支持（Scripting Support）
>
> 允许用户使用AppleScript和其他自动化技术来控制你的应用，或者在你的应用中运行脚本（scripts）。
