# I'm sorry, but it's time to say goodbye.
## I've decided to stop the Debian Easy project.

Debian Easy started as a fork of Spiral Linux, stemming from some disagreements I had with the Spiral Linux developer. Overall, my goals were the same as Spiral Linux's: to build a Debian-based distribution that was more user-friendly out of the box and had better support for Btrfs and Snapper. You could say it was less of a distribution and more of a Debian installer.

The reason I started this project was the impending end of openSUSE Leap 15. SUSE was pushing the development of ALP, and for a while, the future of openSUSE, especially openSUSE Leap, was uncertain. There were many rumors that it might disappear or become a very different, immutable distribution. The original purpose of both Debian Easy and Spiral Linux was to find an easy-to-install, easy-to-transition alternative before openSUSE's potential major changes. We chose Debian because it's stable, has a good reputation, isn't controlled by a commercial company, and has a clear, predictable future.

We now know that the relationship between openSUSE and SUSE has shifted, and SUSE has slowed down the push for ALP. SLE 16 will still be a traditional distribution, and so will openSUSE Leap 16. The beta version of Leap 16 is already available and its official release is set for October 2025. This means the original urgency for Debian Easy and Spiral Linux is no longer a pressing concern. I have also moved some of my work back to openSUSE.

Since Debian 12, the Debian project has made many improvements to make installation and out-of-the-box use easier. While the official installer may still fall short of tools like YaST2, Anaconda, and Calamares in some ways, my biggest issue is limited to the inability to easily or properly set up Btrfs subvolumes. At the same time, our Calamares-based installer images didn't solve many of the fundamental problems. While tools like `grub-btrfs` and `snapper-rollback` helped, they couldn't make up for the shortcomings of using SUSE tools on a non-SUSE distribution. This meant YaST2 was unusable, and many core Snapper-based tools didn't work completely. The improvements we made were quite limited.

Over the past year, I've also realized how difficult it is to maintain these scripts. I know my kernels were often not updated in a timely manner. This is partly because I underestimated the difficulty of maintenance and partly because I've been struggling with depression and other mental health issues.

For these reasons, with Debian 13's official release approaching, I've decided to announce the end of this experimental project.

I apologize if my poor maintenance and the decision to stop this project have caused you any trouble or disappointment.

### Goodbye, and good luck.

# 抱歉，是说再见的时候了
## 我决定停止Debian Easy
Debian Easy是Spiral Linux的的fork，来自于我与Spiral Linux开发者在一些问题上的不同看法。总的来说，我与Spiral Linux的目标是一样的：在Debian的基础上，构建一个能够更开箱易用，且对于btrfs和snapper有更好支持的发行版。或者说与其说是发行版，不如说是Debian安装器。

启动这个项目的原因是，openSUSE Leap 15即将走到尽头。SUSE在推动ALP的发展。在过去的一段时间内，openSUSE特别是openSUSE Leap的前途不明朗，很多传言认为它很可能会消亡，或变成一个非常不同的不可变发行版。Debian Easy和Spiral Linux的最初目的就是在openSUSE可能的巨变来临前，寻找到一个容易安装、过渡、切换的替代品。我们看上了Debian，因为它稳定、声誉良好且不被商业公司控制，有着较为明确而可控的未来。

现在我们知道，openSUSE和SUSE的关系发生了微妙的变化，而且SUSE也放缓了ALP的推进，SLE 16仍然将是一个传统的发行版，openSUSE Leap 16也是这样。后者的Beta版本已经上线并且可用了，并将于2025年10月正式发布。因此，Debian Easy和Spiral Linux的最初目的已经不再是一个严峻的压力了。本人也将部分工作迁移回了openSUSE。

自从Debian 12以来，Debian为了更容易的安装和开箱可用做了很多改进，虽然其官方安装器在一些方面可能还是不如yast2、anaconda和calamares，但是目前就我的使用来说最大的问题已经仅限于不能自由地或合理地设置btrfs子卷。与此同时，我们采用calamares的安装镜像并没有解决太多的问题，虽然像grub-btrfs和snapper-rollback这样的工具能起到改善的作用，但是仍然无法弥补SUSE工具在非SUSE发行版上的缺憾。这不只意味着yast2不可用，而且以snapper为核心的诸多工具也不能完全正常地使用。可以说，我们做到的改善极为有限。

此外，在一年多的时间里，我也意识到了维护这些脚本的困难，我知道我的内核很多时候都是没有及时更新的。这一方面是我曾经低估了维护的困难，另一方面也是因为我受到抑郁和其他精神问题的困扰。

介于以上原因，在Debian 13即将正式发布的时刻，我决定宣布放弃这个测试性的项目。

如果我糟糕的维护和停止的决定给您带来了困扰或遗憾，我很抱歉。

### 再见了，祝好运。
