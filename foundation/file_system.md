# 文件系统

在文件系统中创建，读取，写入以及检查文件跟文件夹。

---

### 主题

---

#### 文件系统操作（File System Operations）

> ```
> class FileManager
> ```
> 一个提供了文件系统内容的方便接口的对象。

> ```
> protocol FileManagerDelegate
> ```
> 一个file manager的delegate的接口，用来在操作进行中进行干预或者当一个错误产生时。

---

#### 文件访问管理（Managed File Access）

> ```
> class FileHandle
> ```
> 一个文件描述符的面向对象的包装（object-oriented wrapper）。

> ```
> class NSFileSecurity
> ```
> 一种封装有关文件的安全信息的存根类（stub class）。

> ```
> class NSFileVersion
> ```
> 一个文件在特定时间点的快照（snapshot）。

> ```
> class FileWrapper
> ```
> 文件系统中一个节点（一个文件，目录，或符号链接）的表示。（A representation of a node (a file, directory, or symbolic link) in the file system.）

---

#### 共享文件（Shared Files）

> ```
> protocol NSFilePresenter
> ```
> 文件协调器用来通知表示文件对象一些系统中其他地方的文件引起的一些改变的接口。（The interface a file coordinator uses to inform an object presenting a file about changes to that file made elsewhere in the system.）

> ```
> class NSFileAccessIntent
> ```
> 协调读取（coordinated-read）或协调写入（coordinated-write）操作的细节。

> ```
> class NSFileCoordinator
> ```
> 一个用于协调在文件呈现中的文件和目录及其读写的对象。（An object that coordinates the reading and writing of files and directories among file presenters.）

---

#### 错误（Errors）

> File System Error Codes
>
> 表示一个可以被抛出的错误值的类型。

---

### 参见

---

#### 文件及数据持久化

> [归档（Archives）和序列化（Serialization）](/foundation/archives_and_serialization.md)
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
