---
title: Operating System
date: 2017-08-14 09:48:18
tags: Tech
---

## [Operating System][lnk_OSWiki]
<img src="operating-system-system_0.png" width = "50" height = "50" alt="Operating System" align=left />
```
操作系统（英语：operating system，缩写：OS）
是管理计算机硬件与软件资源的计算机程序，同时也是计算机系统的内核与基石。
操作系统需要处理如管理与配置内存、决定系统资源供需的优先次序、
控制输入与输出装置、操作网络与管理文件系统等基本事务。
操作系统也提供一个让使用者与系统互动的操作界面。
```

<img src="operating-system-system_1.png" width = "50" height = "50" alt="Operating System" align=left />
```
操作系统的型态非常多样，不同机器安装的操作系统可从简单到复杂，
可从非智能手机的嵌入式系统到超级电脑的大型操作系统。
许多操作系统制造者对它涵盖范畴的定义也不尽一致，
例如有些操作系统整合了图形用户界面，而有些仅使用命令行界面，
而将图形用户界面视为一种非必要的应用程序。
```

<img src="operating-system-system_2.png" width = "50" height = "50" alt="Operating System" align=left />
```
操作系统理论在计算机科学中，为历史悠久而又活跃的分支；
而操作系统的设计与实现则是软件工业的基础与内核
```

<!--more-->

## History

<img src="operating-system-system_3.png" width = "50" height = "50" alt="Operating System" align=left />
```
综观电脑之历史，操作系统与电脑硬件的发展息息相关。
操作系统之本意原为提供简单的工作排序能力，后为辅助更新更复杂的硬件设施而渐渐演化。
从最早的批次模式开始，分时机制也随之出现，在多处理器时代来临时，
操作系统也随之添加多处理器协调功能，甚至是分散式系统的协调功能。
其他方面的演变也类似于此。
另一方面，在个人电脑上，个人电脑之操作系统因袭大型电脑的成长之路，
在硬件越来越复杂、强大时，也逐步实践以往衹有大型电脑才有的功能。
总而言之，操作系统的历史就是一部解决电脑系统需求与问题的历史。
```
1. 1980年代前
>**第一部电脑并没有操作系统。**
 这是由于早期电脑的建立方式（如同建造机械算盘）与效能不足以执行如此程式。
 但在1947年发明了晶体管，以及莫里斯·威尔克斯发明的微程序方法，
 使得电脑不再是机械装置，而是电子产品。
 系统管理工具以及简化硬件操作流程的程式很快就出现了，且成为操作系统的滥觞。
 到了1960年代早期，商用电脑制造商制造了批次处理系统，
 此系统可将工作的建置、排程以及执行序列化。
 此时，厂商为每一台不同型号的电脑创造不同的操作系统，
 因此为某电脑而写的程式无法移植到其他电脑上执行，即使是同型号的电脑也不行。
 到了1964年，IBM System/360推出了一系列用途与价位都不同的大型电脑，
 而它们都共用代号为OS/360的操作系统（而非每种产品都用量身订做的操作系统）。
 让单一操作系统适用于整个系列的产品是System/360成功的关键，
 且实际上IBM目前的大型系统便是此系统的后裔，
 为System/360所写的应用程序依然可以在现代的IBM机器上执行。
 OS/360也包含另一个优点：永久贮存装置—硬盘机的面世（IBM称为DASD）。
 另一个关键是分时概念的建立：将大型电脑珍贵的时间资源适当分配到所有用户身上。
 分时也让用户有独占整部机器的感觉；
 而Multics的分时系统是此时众多新操作系统中实践此观念最成功的。
 **1963年，奇异公司与贝尔实验室合作以PL/I语言建立的Multics，**
 **是激发1970年代众多操作系统建立的灵感来源，**
 **尤其是由AT&T贝尔实验室的丹尼斯·里奇与肯·汤普逊所建立的Unix系统，**
 **为了实践平台移植能力，此操作系统在1973年由C语言重写；**
 **另一个广为市场采用的小型电脑操作系统是VMS。**

2. 1980年代
>第一代微型计算机并不像大型电脑或小型电脑，没有装设操作系统的需求或能力；
 它们只需要最基本的操作系统，通常这种操作系统都是从ROM读取的，
 此种程式被称为监视程式（Monitor）。
 1980年代，家用电脑开始普及。
 通常此时的电脑拥有8-bit处理器加上64KB内存、显示器、键盘以及低音质音响。
 而80年代早期最著名的套装电脑为使用微处理器6510（6502芯片特别版）的Commodore C64。
 此电脑没有操作系统，而是以一8KB唯读记忆体BIOS初始化彩色显示器、键盘以及软驱和打印机。
 它可用8KB唯读记忆体BASIC语言来直接操作BIOS，并依此撰写程式，大部分是游戏。
 此BASIC语言的直译器勉强可算是此电脑的操作系统，当然就没有内核或软硬件保护机制了。
 此电脑上的游戏大多跳过BIOS层次，直接控制硬件。
 早期最著名的磁盘启动型操作系统是CP/M，它支援许多早期的微电脑，且被MS-DOS大量抄袭其功能。
 最早期的IBM PC其架构类似C64。
 当然它们也使用了BIOS以初始化与抽象化硬件的操作，甚至也附了一个BASIC直译器！
 但是它的BASIC优于其他公司产品的原因在于他有可携性，并且相容于任何符合IBM PC架构的机器上。
 这样的PC可利用Intel-8088处理器（16-bit暂存器）定址，并最多可有1MB的内存，然而最初只有640KB。
 软式磁盘机取代了过去的磁带机，成为新一代的储存装置，并可在他512KB的空间上读写。
 为了支援更进一步的档案读写概念，磁盘操作系统（Disk Operating System，DOS）因而诞生。
 此操作系统可以合并任意数量的磁区，因此可以在一张磁盘片上放置任意数量与大小的档案。
 档案之间以档名区别。IBM并没有很在意其上的DOS，因此以向外部公司购买的方式取得操作系统。
 1980年微软公司取得了与IBM的合约，并且收购了一家公司出产的操作系统，
 在将之修改后以MS-DOS的名义出品，此操作系统可以直接让程式操作BIOS与档案系统。
 到了Intel-80286处理器的时代，才开始实作基本的储存装置保护措施。
 MS-DOS的架构并不足以满足所有需求，
 因为它同时衹能执行最多一个程式（如果想要同时执行程式，
 只能使用ISR（中断处理常式）的方式来跳过OS而由程式自行处理多工的部分），
 且没有任何内存保护措施。对驱动程式的支援也不够完整，因此导致诸如音效装置必须由程式自行设置的状况，
 造成不相容的情况所在多有。某些操作的效能也是可怕地糟糕。
 许多应用程序因此跳过MS-DOS的服务程式，而直接存取硬件装置以取得较好的效能。
 虽然如此，但MS-DOS还是变成了IBM PC上面最常用的操作系统（IBM自己也有推出DOS，称为IBM-DOS或PC-DOS）。
 MS-DOS的成功使得微软成为地球上最赚钱的公司之一。
 **而1980年代另一个崛起的操作系统异数是Mac OS，此操作系统紧紧与麦金塔电脑捆绑在一起。**
 **此时一位全录伯拉图实验室的员工Dominik Hagen访问了苹果电脑的史提夫·乔布斯，**
 **并且向他展示了此时全录发展的图形化用户界面。**
 **苹果电脑惊为天人，并打算向全录购买此技术，**
 **但因伯拉图实验室并非商业单位而是研究单位，因此全录回绝了这项买卖。**
 **在此之后苹果一致认为个人电脑的未来必定属于图形用户界面，因此也开始发展自己的图形化操作系统。**
 **现今许多我们认为是基本要件的图形化界面技术与规则，**
 **都是由苹果电脑打下的基础（例如下拉式选单、桌面图示、拖曳式操作与双点击等）。**
 **但正确来说，图形化用户界面的确是全录创始的。**

3. 1990年代
>延续1980年代的竞争，1990年代出现了许多影响未来个人电脑市场深厚的操作系统。
 由于图形化用户界面日趋繁复，操作系统的能力也越来越复杂与巨大，
 因此强韧且具有弹性的操作系统就成了迫切的需求。
 此年代是许多套装类的个人电脑操作系统互相竞争的时代。
 上一年代于市场崛起的苹果电脑，由于旧系统的设计不良，使得其后继发展不力，
 苹果电脑决定重新设计操作系统。经过许多失败的专案后，
 苹果于1997年释出新操作系统——Mac OS X的测试版，而后推出的正式版取得了巨大的成功。
 让原先失意离开苹果的史提夫·乔布斯风光再现。
 **除了商业主流的操作系统外，从1980年代起在开放源码的世界中，**
 **BSD系统也发展了非常久的一段时间，但在1990年代由于与AT&T的法律争端，**
 **使得远在芬兰赫尔辛基大学的另一股开源操作系统——Linux兴起。**
 **Linux内核是一个标准POSIX内核，其血缘可算是Unix家族的一支。**
 **Linux与BSD家族都搭配GNU计划所发展的应用程序，**
 **但是由于使用的许可证以及历史因素的作弄下，Linux取得了相当可观的开源操作系统市占率，**
 **而BSD则小得多。相较于MS-DOS的架构，**
 **Linux除了拥有傲人的可移植性（相较于Linux，MS-DOS衹能运行在Intel CPU上），**
 **它也是一个分时多行程内核，以及良好的内存空间管理（普通的行程不能存取内核区域的内存）。**
 **想要存取任何非自己的内存空间的行程衹能透过系统调用来达成。**
 一般行程是处于用户态（User mode）底下，而执行系统呼叫时会被切换成内核态（Kernel mode），
 所有的特殊指令衹能在内核态执行，此措施让内核可以完美管理系统内部与外部装置，
 并且拒绝无权限的行程提出的请求。
 因此理论上任何应用程序执行时的错误，都不可能让系统崩溃。
 另一方面，微软对于更强力的操作系统呼声的回应便是Windows NT于1999年的面世。
 1983年开始微软就想要为MS-DOS建构一个图形化的操作系统应用程序，
 称为Windows（有人说这是比尔·盖茨被苹果的Lisa电脑上市所刺激）。
 一开始Windows并不是一个操作系统，只是一个应用程序，其背景还是纯MS-DOS系统，
 这是因为当时的BIOS设计以及MS-DOS的架构不甚良好之故。
 在1990年代初，微软与IBM的合作破裂，微软从OS/2（早期为命令列模式，
 后来成为一个很技术优秀但是曲高和寡的图形化操作系统）专案中抽身，
 并且在1993年7月27日推出Windows 3.1，一个以OS/2为基础的图形化操作系统。
 并在1995年8月15日推出Windows 95。
 直到这时，Windows系统依然是建立在MS-DOS的基础上，
 因此消费者莫不期待微软在2000年所推出的Windows 2000上，
 因为它才算是第一个脱离MS-DOS基础的图形化操作系统。
 底下的表格为Windows NT系统的架构：在硬件阶层之上，
 有一个由微内核直接接触的硬件抽象层（HAL），
 而不同的驱动程式以模组的形式挂载在内核上执行。
 因此微内核可以使用诸如输入输出、档案系统、网络、资讯安全机制与虚拟内存等功能。
 而系统服务层提供所有统一规格的函式呼叫库，可以统一所有副系统的实作方法。
 例如尽管POSIX与OS/2对于同一件服务的名称与呼叫方法差异甚大，
 它们一样可以无碍地实作于系统服务层上。
 在系统服务层之上的副系统，全都是用户态，因此可以避免用户程式执行非法行动。
 另一方面，微软对于更强力的操作系统呼声的回应便是Windows NT于1999年的面世。
 1983年开始微软就想要为MS-DOS建构一个图形化的操作系统应用程序，
 称为Windows（有人说这是比尔·盖茨被苹果的Lisa电脑上市所刺激）。
 一开始Windows并不是一个操作系统，只是一个应用程序，其背景还是纯MS-DOS系统，
 这是因为当时的BIOS设计以及MS-DOS的架构不甚良好之故。
 在1990年代初，微软与IBM的合作破裂，
 微软从OS/2（早期为命令列模式，后来成为一个很技术优秀但是曲高和寡的图形化操作系统）专案中抽身，
 并且在1993年7月27日推出Windows 3.1，一个以OS/2为基础的图形化操作系统。
 并在1995年8月15日推出Windows 95。直到这时，Windows系统依然是建立在MS-DOS的基础上，
 因此消费者莫不期待微软在2000年所推出的Windows 2000上，
 因为它才算是第一个脱离MS-DOS基础的图形化操作系统。
 底下的表格为Windows NT系统的架构：在硬件阶层之上，
 有一个由微内核直接接触的硬件抽象层（HAL），
 而不同的驱动程式以模组的形式挂载在内核上执行。
 因此微内核可以使用诸如输入输出、档案系统、网络、资讯安全机制与虚拟内存等功能。
 而系统服务层提供所有统一规格的函式呼叫库，可以统一所有副系统的实作方法。
 例如尽管POSIX与OS/2对于同一件服务的名称与呼叫方法差异甚大，
 它们一样可以无碍地实作于系统服务层上。
 在系统服务层之上的副系统，全都是用户态，因此可以避免用户程式执行非法行动。

4. 今日&未来
**Mainstream Operating System**

| [Windows][lnk_Windows] | [MacOS][lnk_MacOS] | [Unix][lnk_Unix] | [Linux][lnk_Linux] |
| :---: | :---: | :---: | :---: |
| <img src="operating-system-windows.png" width = "30" height = "30" alt="Windows" align=center /> | <img src="operating-system-ios.png" width = "30" height = "30" alt="MacOS" align=center /> | <img src="operating-system-unix.png" width = "30" height = "30" alt="Unix" align=center /> | <img src="operating-system-linux.png" width = "30" height = "30" alt="Linux" align=center /> |


**List of Linux Distributions**

| [Suse][lnk_Suse] | [Debian][lnk_Debian] | [CentOS][lnk_CentOS] | [FreeBSD][lnk_FreeBSD] | [Ubuntu][lnk_Ubuntu] | [Fedora][lnk_Fedora] | [Gentoo][lnk_Gentoo] | [Red Hat][lnk_RedHat] | [Solaris][lnk_Solaris] |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| <img src="operating-system-suse.png" width = "30" height = "30" alt="Suse" align=center /> | <img src="operating-system-debian.png" width = "30" height = "30" alt="Debian" align=center /> | <img src="operating-system-CentOS.png" width = "30" height = "30" alt="centos" align=center /> | <img src="operating-system-freebsd.png" width = "30" height = "30" alt="FreeBSD" align=center /> | <img src="operating-system-ubuntu.png" width = "30" height = "30" alt="Ubuntu" align=center /> | <img src="operating-system-fedora.png" width = "30" height = "30" alt="Fedora" align=center /> | <img src="operating-system-gentoo.png" width = "30" height = "30" alt="Gentoo" align=center /> | <img src="operating-system-redhat.png" width = "30" height = "30" alt="Red Hat" align=center /> | <img src="operating-system-solaris.png" width = "30" height = "30" alt="Solaris" align=center /> |

**Other Operating System**

| [Android][lnk_Android] | [Blackberry][lnk_Blackberry] | [Symbian][lnk_Symbian] | [ChromeOS][lnk_ChromeOS] |
| :---: | :---: | :---: | :---: |
| <img src="operating-system-windows.png" width = "30" height = "30" alt="Android" align=center /> | <img src="operating-system-ios.png" width = "30" height = "30" alt="Blackberry" align=center /> | <img src="operating-system-unix.png" width = "30" height = "30" alt="Symbian" align=center /> | <img src="operating-system-linux.png" width = "30" height = "30" alt="ChromeOS" align=center /> |

[lnk_OSWiki]: https://zh.wikipedia.org/wiki/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F "Operating System"
[lnk_Windows]: https://zh.wikipedia.org/wiki/Microsoft_Windows "Windows"
[lnk_MacOS]: https://zh.wikipedia.org/wiki/MacOS "MacOS"
[lnk_Unix]: https://zh.wikipedia.org/wiki/UNIX "Unix"
[lnk_Linux]: https://zh.wikipedia.org/wiki/Linux "Linux"
[lnk_Suse]: https://zh.wikipedia.org/wiki/SUSE "Suse"
[lnk_Debian]: https://zh.wikipedia.org/wiki/Debian "Debian"
[lnk_CentOS]: https://zh.wikipedia.org/wiki/CentOS "CentOS"
[lnk_FreeBSD]: https://zh.wikipedia.org/wiki/FreeBSD "FreeBSD"
[lnk_Ubuntu]: https://zh.wikipedia.org/wiki/Ubuntu "Ubuntu"
[lnk_Fedora]: https://zh.wikipedia.org/wiki/Fedora "Fedora"
[lnk_Gentoo]: https://zh.wikipedia.org/wiki/Gentoo_Linux "Gentoo"
[lnk_RedHat]: https://zh.wikipedia.org/wiki/Red_Hat_Linux "Red Hat"
[lnk_Solaris]: https://zh.wikipedia.org/wiki/Solaris "Solaris"
[lnk_Android]: https://zh.wikipedia.org/wiki/Android "Android"
[lnk_Blackberry]: https://zh.wikipedia.org/wiki/BlackBerry_OS "Blackberry"
[lnk_Symbian]: https://zh.wikipedia.org/wiki/Symbian "Symbian"
[lnk_ChromeOS]: https://zh.wikipedia.org/wiki/Chrome_OS "ChromeOS"