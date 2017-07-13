# 任务管理（Task Management）

管理你应用程序的工作以及它们与用户和系统之间的交互。

---

### 主题

---

#### 撤销（Undo）

> ```
> class UndoManager
> ```
> 一个一般目的（general-purpose）的操作记录器（recorder），支持撤销（undo）及重做（redo）

---

#### 进度（progress）

> ```
> protocol ProgressReporting
> ```
> 一个对象的接口，用一个进度单例（a single progress instance）报告（report）进度。

> ```
> class Progress
> ```
> 一个对象，给用户传输给定任务的正在进行的进度。（An object that conveys ongoing progress for a given task to the user.
）

---

#### 操作（Operations）

> ```
> class Operation
> ```
> 一个抽象的类，表示代码及一个单一任务（single task）关联的数据。

> ```
> class OperationQueue
> ```
> 一个管理一系列操作执行的队列。

> ```
> class BlockOperation
> ```
> 一个管理一个或多个block的并发执行（concurrent execution）的操作器（operation）。

---

#### 安排（Scheduling）

> ```
> class Timer
> ```
> 一个计时器，在一段时间之后触发，发送一个特定的消息（specified message）给一个目标（target）对象。

---

#### 活动共享（Activity Sharing）

> ```
> class NSUserActivity
> ```
> 一个关于你的应用在某个瞬间的状态的表达式。

> ```
> protocol NSUserActivityDelegate
> ```
> 一个接口，一个用户活动实例通过它来通知其代理更新。

---

#### 系统交互（System Interaction）

> ```
> class ProcessInfo
> ```
> 一个关于当前进程的描述集合。

> ```
> class NSBackgroundActivityScheduler
> ```
> 一个任务计划（task scheduler），适合可以运行在后台的低优先级的操作（low priority operations）。

---

#### 用户通知（User Notifications）

> ```
> class NSUserNotification
> ```
> 一个可以安排在通知中心（notification center）显示的通知。

> ```
> class NSUserNotificationAction
> ```
> 一个action，可以被用户用来回应接收到的通知。

> ```
> class NSUserNotificationCenter
> ```
> 一个从应用分发通知给用户的对象。

> ```
> protocol NSUserNotificationCenterDelegate
> ```
> 一个支持自定义默认通知中心（default notification center）的表现（behavior）的接口。

---

### 参见

---

#### 应用程序支持

> [资源（Resources）](/foundation/resources.md)
>
> 访问你应用程序绑定（bundled）的assets和其他数据。

> [通知（Notifications）](/foundation/notifications.md)
>
> 设计广播消息及订阅广播的模式

> [应用程序拓展（Extension）支持](/foundation/app_extension_support.md)
>
> 管理应用程序拓展跟它的主程序（hosting app）之间的交互。

> 错误（Errors）及异常（Exceptions）
>
> 响应你在api交互中产生的问题情况，微调你的应用以便更好的调试。

> 脚本支持（Scripting Support）
>
> 允许用户使用AppleScript和其他自动化技术来控制你的应用，或者在你的应用中运行脚本（scripts）。
