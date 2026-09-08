## DSH Desktop v0.4.1

DeepSeek Harness 桌面客户端 v0.4.1（2026-09-08 发布）
这是由 **DSH 通过命令自我封装与添加功能** 的桌面客户端

<img width="961" height="601" alt="1" src="https://github.com/user-attachments/assets/87ae230c-22d2-4807-9adb-4ad13443820a" />
<img width="961" height="601" alt="2" src="https://github.com/user-attachments/assets/22c12293-2ee2-4b21-a7ad-786c2ac7a84c" />
<img width="961" height="601" alt="3" src="https://github.com/user-attachments/assets/84132ee2-7c55-413a-a4d2-0245bfe53c7b" />
<img width="961" height="601" alt="4" src="https://github.com/user-attachments/assets/33f06e9a-0570-473a-b02f-1a178c304d9e" />
<img width="961" height="601" alt="5" src="https://github.com/user-attachments/assets/5e93cc9c-aaac-4545-b9b9-7127eb03174b" />


**v0.4.1 更新内容**
- 内核升级：dsh 0.1.2-rc.1（不再 0.1.1），插件市场 dshmarket 升到 1.42.0（兼容 0.1.2 内核）
- 新增插件兼容智能检测：更新前自动检测不兼容插件，官方插件自动升级，有新版则自动升级替代禁用
- "通过代码添加" 按钮注入修复
- 保留：token 自动认证、快照回滚（标题栏轮胎）、崩溃 3 次介入、存储位置管理、更新失败恢复服务

**下载前的提示**
可以将安装文件放置在非C盘目录下，建议路径不要有中文。

### 下载
- **[DSH-Desktop-v0.4.1.zip](https://github.com/SheepPen/DSH-Desktop/releases/download/DSH-Desktop/DSH-Desktop-v0.4.1.zip)**
- 压缩包解压后得到 DSH-Desktop解压包-0.4.1.exe
- 运行 exe 时自动解压文件至当前目录，解压完成自动运行程序
- 第一次运行时时间可能久一点，请耐心等待

## 说明：

1.免安装：exe仅自解压程序，释放文件。免部署：解压即可用

2.保持原生，仅增加一些实用功能

3.只携带“插件市场”插件

4.可在不同的文件夹内解压，可以多开，理论上可以用另一个客户端修复前一个

5.设置-通用设置增加Enter（回车）功能，设置为换行时，可在会话消息框处换行，避免按错发送，并自动改为Ctrl+Enter发送对话

6.设置-通用设置增加关闭按钮的功能，可设置最小化与直接关闭程序

7.设置-通用设置增加标题栏颜色，可设置跟随软件、跟随系统、自定义（取色盘）

8.设置-通用设置增加在系统盘常驻与开机自启动

9.设置-通用设置增加合并记录，合并记录说明见下方

10.设置-通用设置增加回滚快照功能，可自定义时间，自动备份文件。

11.设置-通用设置增加检查更新，可检测dsh内核版本，并更新

12.第三方中转的curl等部署代码可通过“通过代码添加”实现复制粘贴自动识别


## 合并记录说明：

合并记录在第一次解压运行会提醒，设置里也可找到合并记录并更新

合并记录包括会话存档、插件、设置、API。原因在于客户端崩溃，用新客户端时可以快速部署

合并记录如果有多个文件夹的方式，会列出所有的地址，可以自由选择合并哪个文件

合并记录的会话、插件、设置、API也可以随意选择

注意：如果某些情况下客户端出错，用新客户端合并时，谨慎合并会话记录。偶有发生记录不全的现象。
