# TuinkPad

Full open source mobile terminal device with e-ink screen, physical keyboard and long battery life, suitable for Linux system administrators and Linux users.


# 带电子墨水屏的廉价终端

## 名字(待定)

- Tundle
- TuinkPad
- TunaPad

## 愿景

Distraction Free: 让更多人能够集中精力完成任务，如写作，修服务器，修Bug，聊IRC....

Less is more: 足够可靠，功能越少越好

Full open source: 从硬件设计到生产工艺到供应商选型标准，全部开源

## 特性

 - 拥有 iPad Mini 大小的电子墨水屏
 - 带背光，像 Kindle Paperwhite 那样
 - 键盘要轻，全尺寸，像 Thinkpad 的那样最好
	 - 一定要有 Ctrl Meta 
 - 屏幕可 Dock 和 Undock，上面有一些基本的键如: PgUp PgDn，用于看电子书
 - 有身体支架，可在行走中使用
 - 成本在 500 块钱左右
 - 屏幕与键盘的连接足够可靠，可在地铁上(坐/站立)，出租车上，飞机上使用
 - 带有 Wi-Fi
 - 电池续航 4 周
 - ARM 或 MIPS 架构都可以
 - 无图形界面，但可以跑 fbterm
 - 开机/待机的切换时间小于 2 秒
 - 有一个 Micro USB 口，用于 OTG 方式外接 3G/4G 上网卡，或 Yubikey，并进行充电
   * 也可以一个 Micro USB，一个普通 USB
 - 如果电子墨水屏不好搞定，用计算器上的 LCD 单色屏也可以?
 - 被 Linux 主线 Kernel 所支持，无需过多定制
 - RAM:
 - 内部存储：64GB
 - 带有 SD 卡插槽可扩展
 - 所有设计全部开源！
 - 支持 UTF-8
 - OTG: 
   * as USB Gadget: mass storage 模拟成U盘，插到PC上
   * as USB Gadget: HID Keyboard 模拟成键盘对外输出文字

## 挑战

 - 电子墨水屏需要屏保，否则会烧屏
 - 成本
 - 待机电量


## 软件

预装

```
tmux alpine mutt mbsync/offlineimap weechat vim emacs dropbox 
```

输入法:
```
uim-fep fcitx-frontend-fbterm kmscon fbterm univt 
vim-im ywvim
```

## 实现方案
- 买个山寨平板，魔改一发
- BBB
- RPi
- 与 Digital Ocean 或阿里云厂商合作，塞广告来降低成本?
- 全志系列处理器？

## See Also

 - [FreeWrite/HemingWrite](https://www.kickstarter.com/projects/adamleeb/hemingwrite-a-distraction-free-digital-typewriter/description)
 - [AlphaSmart Neo](https://www.flickr.com/photos/kadavy/19875435485/in/pool-alphasmart/) [详细评测](https://jennifermack.net/2015/01/29/writing-with-the-alphasmart-neo2/)
 - [KindleBerry Pi](http://www.ponnuki.net/2012/09/kindleberry-pi/)
 - Atrix Dock 4G
 - Sony Clie UX50
 - [Displio](http://displ.io/)
 
 
## 商业模式

钱钱钱就知道钱！

咬我啊！
