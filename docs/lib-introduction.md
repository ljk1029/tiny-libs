### 1. 基础小组件模块

#### 编解码与数据处理
- base64：Base64 编码与解码工具。
- cjson：轻量级 JSON 解析库。
- protobuf：Google Protocol Buffers，结构化数据序列化。

#### 网络与通信
- network：基础网络通信接口。

#### 日志与测试
- gtest：Google Test 单元测试框架。
- spdlog：高性能日志库。
- zlog：轻量级日志系统。

#### 数据库
- sqlite3：嵌入式关系型数据库。

### 2. USB模块

#### 相关库
- libusb：通用 USB 设备访问库，支持跨平台 USB 通信。
- hid：HID 设备访问库，支持键盘、鼠标等设备。

#### USB命令
- lsusb：列出系统中的 USB 设备。

#### USB路径
- `/sys/bus/usb/devices`
- `/dev/bus/usb`
- `/proc/bus/usb`

### 3. ALSA 声音

#### 相关库
- alsa-lib：ALSA 项目的 C 语言库，提供对声卡的底层访问。

#### 命令行工具
- `arecord`：录音命令。
- `aplay`：播放音频文件命令。
- `alsamixer`：终端下的音频混音器。