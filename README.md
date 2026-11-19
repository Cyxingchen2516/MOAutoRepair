# MOAutoRepair

《心灵终结 3.3.6》（Mental Omega 3.3.6）的客户端插件。

## 功能

- 自动对受损建筑下达维修指令（客户端行为，联机安全）
- 可调节扫描间隔与每帧事件上限

## 安装

本插件不需要 `.inj` 文件，Syringe 会自动加载 `MOAutoRepair.dll`。

## 配置

```ini
[AutoRepair]
Enable=1
Interval=30   ; 扫描间隔（逻辑帧），30 ≈ 1 秒
Batch=24      ; 每逻辑帧最多发送多少条维修事件
Log=1
```
## 安装

1. 需要先安装 [Syringe](https://github.com/Ares-Developers/Syringe)（心灵终结自带）。
2. 把本目录下的文件放进游戏根目录（`gamemd.exe` 所在目录）。
3. 启动游戏即可。删除文件即卸载。

## 说明

- 纯客户端插件：不修改游戏模拟数据、不发送指令，联机时对方无需安装。
