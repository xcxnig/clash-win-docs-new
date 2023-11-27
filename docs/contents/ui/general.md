# 常规 General

![](~@imgs/ui-general.png)

在常规页面下可以清楚了解当前配置文件的设置，譬如常规的 http 和 socks5 代理端口等，方便对某些应用单独进行配置代理。部分含删除线功能说明在新版本后弃用。

## 选项说明

- Port：Mixed(Http+Socks) 代理端口
- Allow LAN：是否允许局域网代理
  - 网络图标：显示网卡信息
- Log Level：Clash 核心日志等级
- IPV6: 是否启用 IPV6
- Home Directory：Clash 配置文件目录（不建议修改此目录下文件内容）
- GeoIP Database：GeoIP 数据库更新
- UWP Loopback：UWP 应用联网限制解除工具
- Service Mode: 虚拟网卡安装(TUN 模式)
  - 地球图标：显示 Service Mode 在线状态
- TUN Mode: 是否启用 TUN 模式
  - 设置图标：打开 TUN 模式设置面板
- TAP Device：虚拟网卡安装(TAP 模式)
- Mixin: 是否启用 Mixin 模式
  - 设置图标：启动编辑器修改 Mixin 配置
- System Proxy：系统代理开关
- Start with Windows/macOS/Linux：开机自启动开关

## 点击行为

- Clash for Windows（标题）：快速重启软件
- v x.x.x: 当显示`new`提示时可以直接点击下载新版安装包 (每隔 6 小时检查一次更新)
- Connected/Disconnected：文件夹中显示当前日志文件

## 右侧对应点击行为

- Port:
  - 终端图标: 使用命令行设置系统代理
  - 循环图标: 随机设置 Mixed 端口
  - 端口号：修改 Mixed Port
- Log Level: 设置日志类型
- IPv6：设置是否启用 IPv6 连接逻辑
- Clash Core
  - 内核版本号: 打开 Clash 内核控制 Web 页面
  - ![button-functions](~@imgs/button-functions.png)
- UWP Loopback：快速打开回环代理限制器
- Home Directory：快速打开配置文件目录
- GeoIP Database：点击更新 GeoIP 库 （macOS 可用）
- TAP Device：打开 TAP 模式虚拟网卡控制面板（Windows 可用）
