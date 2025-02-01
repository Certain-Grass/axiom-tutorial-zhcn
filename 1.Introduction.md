
> 感谢闽高联 AB 帮助我将这篇教程转移至Github Repository
> 本教程作者 某个草 ，原文位置 https://hi-ysumc.feishu.cn/wiki/QDJBwtCBEi5eLakfWCvcRtErnvb?from=from_copylink 请勿二次转载。

# Axiom 的基础科普与使用方法

> [!TIP]
> **该文章为前言，左上角点选出左栏可进入子页面介绍。**
> **您也可以直接点击下方高亮块转到子文章。**

Axiom 是一个新锐的世界编辑模组。有一系列可以拓展创造模式的功能，还有一个完全嵌入游戏内的图形界面编辑软件供使用。**该模组可谓是近乎颠覆了早先世界编辑模组以一系列专属指令为核心的操作模式，转而使用了高度简明的图形化界面来进行编辑，这让该模组很容易上手，非常适合新人学习。**

> [!TIP]
> 如果想象不出来差别多大的话，想一想 MS-DOS 和 Windows 的区别。

本文将以从外到内的逻辑形式介绍 Axiom。

（安装方式省略）

# 基础功能

当一个 Minecraft 世界的“允许作弊”选项设置为“开”时，**无论游戏模式，Axiom 均可正常使用。**

## 游戏内编辑功能（Builder Mode）

Axiom 会在创造模式的物品栏中增加一个“功能”栏位，这代表着玩家现在可以使用的编辑功能。玩家可以通过鼠标滚轮或“0”键选择该功能。

![](static/NWxwbhOLXownLkx5pckcP0djn0e.png)

**游戏内功能选择**
当玩家物品栏的选择光标在“功能”栏位上时，按住 `LAlt` 键，可以呼出 Axiom 的游戏内功能选择菜单，松开 `LAlt` 键菜单即关闭。

![](static/DTACbBzWnoQmSsxOOPccHTRvn5f.png)
**游戏内编辑选项**
当玩家物品栏的选择光标不在“功能”栏位上时，按住 `LAlt` 键，可以呼出 Axiom 的创造模式附加菜单，松开 `LAlt` 键菜单即关闭。
![](static/UCW3beI0noFTgGxHFxrcTzz7nUe.png)

如果你想了解更多，请参看本知识库的《游戏内编辑功能》。

## 编辑器功能（Editor Mode）

如果你想了解更多，请参看本知识库的《可视化编辑器功能》。

Axiom 最具特色的功能就是嵌入在游戏中，类似于游戏引擎或专业软件的可视化编辑器功能了。

按下 `Rshift` 键，即可进入 Axiom 的可视化编辑器功能。再次按下 `Rshift` 键退出该功能。

![](static/Idafbu9w3oeK8rxkeXVcPXkAnfe.png)

## 展示实体编辑功能

1.19.4 后，Minecraft 加入了“展示实体”（Display）以灵活展示多种内容。但此类展示实体只能通过 `/summon` 指令生成，这需要建筑师有一定的指令基础知识才能玩转展示实体。

**Axiom 提供了一整套基于图形化 UI 的展示实体创建编辑方案，从而让建筑师更优雅从容地创建并编辑展示实体。**笔者认为这种图形化的方案相当具有革命性，是 Axiom 最强大的闪光点。

如果你想了解更多，请参看本知识库的《展示实体编辑功能》。

![](static/YpU6bfBvsokL40xf53jcgJponTc.png)
![](static/SehJbHgxrolrnbxO16ScHrtenMg.png)

# 使用感受

作为一名半吊子 MC 建筑师，笔者在工作中引入 Axiom 已经很久了。目前，笔者是同时使用 Axiom 和 WorldEdit 进行建筑工作，并根据不同的需求使用不同的模组。

Axiom 最独特的自然是基于 imGUI 的图形操作界面了，在此之前只有第三方软件才会有这样的界面（如 MCEdit），如今这种界面嵌入了游戏，这让 Axiom 相比于需要记一堆指令的 we 而言更加方便上手掌握。

其次令人注意到的是 Axiom 的流畅度和顺滑度，在此之前即便是大伙都比较认可的 VoxelSniper，其操作也会显得一顿一顿的（大约 0.2 秒一次有效操作）。**Axiom 几乎做到了“绝对跟手”的人机交互**，这一点非常值得肯定，尤其是笔者这种被 we 的笔刷折磨的不轻的人。当然，过大规模的操作也会卡慢。

**Axiom 也引入了很多原本只有多插件才有的功能**（如自由曲面放样（Loft-Tool），基于噪声的笔刷插件(Arceon)等），甚至有一些功能还要比插件做得更好。要知道不是所有人都有自己独立开设一个服务端自己使用的能力，这些原本只能在服务器使用的功能被整合起来，引入单人游戏，真的是可喜可贺。

> [!TIP]
> “技术封锁”实际上也是一个影响新 MC 建筑师提升水平的隐性障碍，早期各路插件齐飞的时候这算是常态。

## ↓ 更理科的评价体系 ↓

笔者基于自己制作建筑时常用的办法或常遇到的场景。总结了如下优劣评价表。

评价基于主观，仅供参考，在这里也加入了 FAWE 以进行对比。

<table>
<tr>
<td>**表现良好/很容易**<br/></td><td>**表现一般/较挣扎**<br/></td><td>**表现较差/很艰难**<br/></td><td>**几乎无法操作/不可能完成**<br/></td></tr>
<tr>
<td>😄<br/></td><td>😐<br/></td><td>☹️<br/></td><td>💀<br/></td></tr>
</table>

<table>
<tr>
<td>使用场景/细节<br/></td><td>FastAsyncWorldEdit<br/></td><td>WorldEdit<br/></td><td>Axiom<br/></td><td>备注<br/></td></tr>
<tr>
<td colspan="5">**游戏与兼容性**<br/></td></tr>
<tr>
<td>单人游戏<br/></td><td>☹️<br/></td><td>😄<br/></td><td>😄<br/></td><td>1.12后，FAWE不再支持单人，需要搭建单人服务端。<br/></td></tr>
<tr>
<td>多人游戏<br/></td><td>😄<br/></td><td>😄<br/></td><td>😄<br/></td><td>Axiom原生多人支持需要付费。<br/></td></tr>
<tr>
<td>可拓展性<br/></td><td>😄<br/></td><td>😄<br/></td><td>😄<br/></td><td>WE支持外挂插件或代码，A可以写Lua脚本。<br/></td></tr>
<tr>
<td>程序稳定<br/></td><td>😐<br/></td><td>😄<br/></td><td>😐<br/></td><td>FAWE的鲁棒性需要看服务器情况，A则是小Bug一堆。<br/></td></tr>
<tr>
<td>优化程度<br/></td><td>😄<br/></td><td>😐<br/></td><td>😄<br/></td><td>WE的优化绝对是最糟糕的，没有异议。<br/></td></tr>
<tr>
<td colspan="5">**学习成本**<br/></td></tr>
<tr>
<td>直观性<br/></td><td>😐<br/></td><td>😐<br/></td><td>😄<br/></td><td><br/></td></tr>
<tr>
<td>熟悉基础操作<br/></td><td>😄<br/></td><td>😄<br/></td><td>😄<br/></td><td><br/></td></tr>
<tr>
<td>进一步学习<br/></td><td>😐<br/></td><td>😐<br/></td><td>😄<br/></td><td>WE需要背指令。<br/></td></tr>
<tr>
<td>几乎完全掌握<br/></td><td>☹️<br/></td><td>☹️<br/></td><td>☹️<br/></td><td>不管是什么都没那么容易完全掌握的。<br/></td></tr>
<tr>
<td colspan="5">**操作舒适度**<br/></td></tr>
<tr>
<td>手不离鼠标<br/></td><td>☹️<br/></td><td>☹️<br/></td><td>😄<br/></td><td>有一说一，手不离鼠标对操作顺滑性真的非常重要。<br/></td></tr>
<tr>
<td>不打断心流<br/></td><td>😐<br/></td><td>😐<br/></td><td>😄<br/></td><td>WE键入长指令时容易打断心流，很玄学但确实会影响到人。<br/></td></tr>
<tr>
<td>顺滑操作<br/></td><td>☹️<br/></td><td>☹️<br/></td><td>😄<br/></td><td>试试Axiom的笔刷吧，太顺滑了。<br/></td></tr>
<tr>
<td colspan="5">**宏观编辑**<br/></td></tr>
<tr>
<td>小规模编辑<br/></td><td>😄<br/></td><td>😄<br/></td><td>😄<br/></td><td><br/></td></tr>
<tr>
<td>中规模编辑<br/></td><td>😄<br/></td><td>😄<br/></td><td>😄<br/></td><td><br/></td></tr>
<tr>
<td>大规模编辑<br/></td><td>😄<br/></td><td>😐<br/></td><td>😐<br/></td><td>WE和A均可能出现卡慢现象。<br/></td></tr>
<tr>
<td>超大规模编辑<br/></td><td>😄<br/></td><td>☹️<br/></td><td>😐<br/></td><td>WE有卡死风险，A可能出现渲染错误或者无休止的操作。<br/></td></tr>
<tr>
<td>极大规模编辑<br/></td><td>😄<br/></td><td>💀<br/></td><td>💀<br/></td><td>除FAWE，其余的都会卡死且救不回来。<br/></td></tr>
<tr>
<td>自由旋转结构<br/></td><td>😐<br/></td><td>☹️<br/></td><td>😄<br/></td><td>FAWE表现不如A的优秀，WE无损旋转需要调用函数。<br/></td></tr>
<tr>
<td>镜像结构<br/></td><td>😄<br/></td><td>😄<br/></td><td>☹️<br/></td><td>不知道A为什么几乎没有有效的镜像操作。<br/></td></tr>
<tr>
<td colspan="5">**细节制作**<br/></td></tr>
<tr>
<td>精确定距离<br/></td><td>😄<br/></td><td>😄<br/></td><td>😐<br/></td><td>WE只需要输个数字就行了，A还需要滚轮并一个个数。<br/></td></tr>
<tr>
<td>距离/尺寸微调<br/></td><td>😐<br/></td><td>😐<br/></td><td>😄<br/></td><td>滚轮的优势体现出来了。<br/></td></tr>
<tr>
<td>超精细雕花<br/></td><td>☹️<br/></td><td>☹️<br/></td><td>😄<br/></td><td>编辑器模式的小功能救大命。<br/></td></tr>
<tr>
<td>非法拼搭<br/></td><td>😐<br/></td><td>😐<br/></td><td>😄<br/></td><td>A的编辑器模式小功能避免了WE需要的复杂操作。<br/></td></tr>
<tr>
<td>纹理编辑<br/></td><td>😄<br/></td><td>☹️<br/></td><td>😄<br/></td><td>Axiom有些功能比Arceon还要好。<br/></td></tr>
<tr>
<td>配色方案布置<br/></td><td>😐<br/></td><td>☹️<br/></td><td>😐<br/></td><td>FAWE配色笔刷纯凑合，这方面还是**GoPaint**比较好。<br/></td></tr>
<tr>
<td colspan="5">**编辑稳定性**<br/></td></tr>
<tr>
<td>预防方块更新<br/></td><td>😄<br/></td><td>💀<br/></td><td>😄<br/></td><td>WE每次操作，方块必更新（咬牙切齿）。<br/></td></tr>
</table>

# 注意事项

> [!TIP]

**注意：虽然 Axiom 社区版是免费的，但原则上讲，使用 Axiom 制作盈利项目（例如建筑商单）时，您需要购买商业许可版权。**
**截至文章撰写时，Axiom 授权费用如下：**
**个人使用授权（仅限一个用户）：**
月费：7.99$/月
年费：94.99$/年
**服务器使用授权（仅限 1 个 IP）**
月费：24.99$/月

（注：除原生多人游戏支持外，商业许可版权与社区版功能没有区别，您并不需要因为某些特殊功能而去购买商业许可版权。）

# 还有一件事情：Axiom 的全部操作均可用 `Ctrl`+`Z` 撤销。

多爽啊这！
