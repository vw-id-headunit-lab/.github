## VW-ID 车机研究俱乐部 👋

欢迎加入 VW-ID 车机研究俱乐部！这里汇集了大众 ID. 系列车机研究爱好者。

### 车型与项目入口

- ID.3 / ID.4（2024 年前）：请从 [ICAS3 AGL root](https://github.com/vw-id-headunit-lab/icas3-agl-root) 入门。
- ID.3 MKII · ICAS3GP · 软件版本 8704：[a3-root](https://github.com/vw-id-headunit-lab/a3-root)，通过车机 SoftAP A3 通道拉起 Linux SSH，并使用源端口 7878 进行 root 公钥登录。目前仅已实现 Linux IVI（AGL）root，Android root、ADB 和 QNX 均未完成。
- ID.7 软件版本7047：参考 [a3-root](https://github.com/vw-id-headunit-lab/a3-root)，通过车机 SoftAP A3 通道拉起 Linux SSH，车机AGL自带adb，可直接安装软件

### 联网问题：

- 网关补丁：[点击这里](https://github.com/vw-id-headunit-lab/http-gateway-patch)
- 白名单补丁：[点击这里](https://github.com/vw-id-headunit-lab/ivi-whitelist-manager)

### 已有特性：

- 灯光精灵carplay联动：[点击这里](https://github.com/vw-id-headunit-lab/smartlight-agl)
- 自动切换日间夜间模式：[点击这里](https://github.com/vw-id-headunit-lab/icas3-agl-auto_day_night)
- 持续更新，敬请期待。

### 开发虚拟机

- 安卓虚拟机：[点击这里](https://github.com/vw-id-headunit-lab/android-firmware-qemu-bench)
- HMI虚拟机：[点击这里](https://github.com/vw-id-headunit-lab/icas3-hmi-bench)

---

***转载与衍生作品，请注明来源***

---

## VW-ID Head Unit Research Club 👋

Welcome to the VW-ID Head Unit Research Club! This is a community of enthusiasts dedicated to researching Volkswagen ID. series infotainment systems.

### Supported Models & Projects

- ID.3 / ID.4 (pre-2024): Get started with [ICAS3 AGL root](https://github.com/vw-id-headunit-lab/icas3-agl-root).
- ID.3 MKII · ICAS3GP · Software Version 8704: [a3-root](https://github.com/vw-id-headunit-lab/a3-root). Enables Linux SSH via the head unit's SoftAP A3 channel, with root public-key authentication using source port 7878. Currently, only Linux IVI (AGL) root access has been achieved. Android root, ADB, and QNX support are not yet available.
- ID.7 · Software Version 7047: Refer to [a3-root](https://github.com/vw-id-headunit-lab/a3-root). Linux SSH can be enabled via the head unit's SoftAP A3 channel. The AGL system comes with built-in ADB, allowing applications to be installed directly.

### Network Connectivity

- Gateway Patch: [Click here](https://github.com/vw-id-headunit-lab/http-gateway-patch)
- Whitelist Patch: [Click here](https://github.com/vw-id-headunit-lab/ivi-whitelist-manager)

### Available Features

- Smart Light (ID. Light) integration with Apple CarPlay: [Click here](https://github.com/vw-id-headunit-lab/smartlight-agl)
- Automatic day/night mode switching: [Click here](https://github.com/vw-id-headunit-lab/icas3-agl-auto_day_night)
- More features are under development. Stay tuned!

### Development Virtual Machines

- Android Virtual Machine: [Click here](https://github.com/vw-id-headunit-lab/android-firmware-qemu-bench)
- HMI Virtual Machine: [Click here](https://github.com/vw-id-headunit-lab/icas3-hmi-bench)

---

***Please credit the original source when redistributing or creating derivative works.***
