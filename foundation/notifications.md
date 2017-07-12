# 通知（notifications）

设计广播消息及订阅广播的模式

---

### 主题

---

#### 键值观察（Key-Value Observing，KVO）

> NSKeyValueObserving
>
> 一个可以安排在通知中心（notification center）显示的通知。

---

#### 通知（Notifications）

> ```
> struct Notification
> ```
> 通过通知中心向所有注册的观察者广播的信息的容器。

> ```
> class NotificationCenter
> ```
> 一个使得信息广播给注册观察者的通知分发机制（notification dispatch mechanism）。

> ```
> class NotificationQueue
> ```
> 一个通知中心的缓冲区。

---

#### 跨进程通知（Cross-Process Notifications）

> ```
> class DistributedNotificationCenter
> ```
> 一个使得通知跨任务边界（across task boundaries）广播的通知分发机制notification dispatch mechanism）。

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

> 应用程序拓展（Extension）支持
>
> 管理应用程序拓展跟它的主程序（hosting app）之间的交互。

> 错误（Errors）及异常（Exceptions）
>
> 响应你在api交互中产生的问题情况，微调你的应用以便更好的调试。

> 脚本支持（Scripting Support）
>
> 允许用户使用AppleScript和其他自动化技术来控制你的应用，或者在你的应用中运行脚本（scripts）。
