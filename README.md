# guide-manjaro-desktop
Tips to use manjaro desktop

# Linux桌面使用说明

曾经使用了8年ubuntu,2年黑苹果,1年windows, 现在用manjaro作为唯一桌面环境

## 选择理由

1. 使用livecd能启动的系统中, manjaro的驱动是最全面的, 起码只有它和linuxmint能驱动我的高通无线网卡, 最新的ubuntu/debian都不行. 
> 为什么不是linuxmint? linuxmint也可以驱动网卡, 但是桌面系统启动可能失败,还有默认的kde设置和界面都很丑陋, 没有manjaro自带的好.
2. aur是linux最全的软件库,没有之一,实际使用yay的体验也非常好.虽然会有很多存储和组件的臃肿,但是只要使用流畅,花费一些存储不算什么
> 为什么不是ubuntu? ubuntu的synaptic装软件也很方便,但是要增加各种三方源, 如果遇到类库冲突, 软件包版本冲突甚至是依赖损坏,就很麻烦

## 有什么要求

1. 需要分配多一些硬盘, 200G以上
2. 科学上网, 好的科学上网可以弥补yay下载源码包编译的时候速度慢的遗憾

## 折腾了多久

第一次全部调教好,用的时间比较长,但是如果将经验分享出来, 相信在一天之内完全可以得到一个有高效生产力的系统
当linux使用稳定之后,完全可以不重装更换电脑

## 和黑苹果比较

相同硬件的情况下, 比黑苹果快, 省心程度和稳定性当然比黑苹果差一点

## 和windows比较

对开发和运维来讲, 比windows好很多, windows的wsl2(就是个hv虚拟机)就没必要了. windows下想用一个linux下的软件, 比如pip装ansible就很难, 还需要装几个G的windows sdk,这些麻烦都可以省了, 还基本不想要反病毒.
