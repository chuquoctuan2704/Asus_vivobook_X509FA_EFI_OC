# Asus VivoBook X509FB Hackintosh
Asus VivoBook X509FB Hackintosh Laptop-macOS Monterey-OpenCore

# Configuration

## 硬件配置 / Specifications:

Computer model：Asus VivoBook X509FB (Y5200FB)

Processor：Intel Core i5-8265U Processor（Whiskey Lake）

Memory：8GB Samsung DDR4 2400MHz

Hard Disk：128GB SSD WD SN520

Integrated Graphics：Intel UHD Graphics 620

Monitor：AUO61ED FHD 1920x1080 (15.6 inch)

Sound Card：Realtek ALC256 (layout-id:66)

Wireless Card：Realtek 8821CE Wireless LAN 802.11ac（Replaced with Intel AX200 Wireless）

## 无法工作 / Non-working:

- d-GPU (Nvidia MX110)

- Trackpad（GPIO interrupt mode）

「Trackpad polling mode is working properly」

- Realtek 8821CE Wireless LAN 802.11ac

- Micro-SD Card USB Reader

## 注意事项 / Attention Points

此机器搭载的ELAN1200触摸板无法正常工作，它会在macOS中随机停止工作，虽然在机器进入睡眠数分钟后，将机器唤醒会得到恢复。但是此问题我尝试研究后无法解决。
#### 因此使用该机器务必随身携带鼠标使用，避免仅使用触摸板而造成不必要的麻烦。

The ELAN1200 touchpad on this machine cannot work normally. It will stop working randomly in macOS, although it will be restored after waking up the machine a few minutes after the machine goes to sleep. But this problem can't be solved after I try to study it.
#### Therefore, when using the machine, be sure to carry the mouse with you to avoid unnecessary trouble caused by using only the touch pad.

#### 请勿使用具备T2安全芯片的Mac机型平台ID
#### Do not use a Mac platform ID with a T2 security chip.

详情请见链接

See the link for details

[Link/链接🔗](https://github.com/VoodooI2C/VoodooI2C/issues/321)

## 未经测试 / Untested availability:

- None

## 维护者 / Maintainer

© [Miracle樱乃.](https://github.com/Miracle-Sakuno), Released under the [MIT License](./LICENSE) .<br>
Authored and maintained by Miracle樱乃. with help from contributors ([list](https://github.com/Miracle-Sakuno/Asus-VivoBook-X509FB-Hackintosh/graphs/contributors)).

> GitHub [@Miracle樱乃.](https://github.com/Miracle-Sakuno) · Twitter [@Miracle樱乃.](https://twitter.com/Miracle_Sakuno) · Telegram Channel [@Rabbit House](https://t.me/RabbitHouse_i)

此文档暂时归档，若有其他维护者请勿改动

### 注意：本人公开的社交账号仅为此Github，Twitter和Telegram频道，以及本人QQ账号为：2112074157。除以上四个本人专用账号之外，其他任何以我的名义来发布消息的都是骗子，注意核实
### 尤其注意此人QQ账号：1063995989，1248394877长时间故意盗用本人身份发布各类不实消息，请各位注意核实，并帮助我举报他
### 感谢各位支持

Note: my social account is only for GitHub, twitter and telegraph channels, and my QQ account is 2112074157. In addition to the above four personal accounts, any other person who publishes information in my name is a liar. Pay attention to verification

Pay special attention to this person's QQ account: 1063995989，1248394877. He deliberately embezzles his identity and publishes all kinds of false news for a long time. Please pay attention to verification and help me report him

Thank you for your support
