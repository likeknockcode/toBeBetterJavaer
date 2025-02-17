---
title: 从纠结到放过自己——2022 年终总结 - 菜狗の日常
shortTitle: 从纠结到放过自己——2022 年终总结 - 菜狗の日常
category:
  - 其他网站
---

# 从纠结到放过自己——2022 年终总结

发布于 24 天前 143 次阅读

* * *

> If you miss the train I'm on
> 
> You'll know that I'm gone
> 
> You can hear the whistle blow
> 
> A hundred miles

2022 年，距离 2017 年已相去五年，离 2021 年也有一年之远。然而就是这区区一年，产生影响之深远更要远胜先前四年。对于我个人来说，是生活方式的根本性转变，使得我不能再以学生的身份自居，而不得不站在一个“社会人”的角度去思考问题了。

早先四年，以至于工作的前半年（2021 年下半年），可谓混沌一片。即无短期目标，亦无远大志向，只想着过一日是一日。于是 2020 年下半年考研将近，并未做什么深远考虑，即选择了考研，目标院校也没经过深思熟虑，直接延续了高考失败的目标——浙大。更可笑的是，当年选择浙大的理由，在考研时早已记不清了。然浑噩三年之久，早就丧失了潜心学习的能力。于是在复习一个月高数后，学而不得的焦躁和装模作样的负疚感就让我无法继续。放弃的过程也很“顺滑”，仅仅是一个早晨的突然决定。这何尝不是一种逃避选择，选择了更擅长的代码而非科研，但仍以“迟早都要工作”的理由麻痹自己。于是就是背八股、做项目、实习找工作。后续的事情倒还算顺利，找到工作后毕业入职，并幸而在裁员大潮中得以保全，并未受过大影响。而剧变的降临，又有谁能完全不受影响，但这又是 2022 年的事了，后面会说到。

然而纵使是找到工作，仍延续之前习气难改。这或许不是一个转折关系，更像是个因果关系：正因为过于顺利，于是便没有理由去寻求改变。一个典型，也是现在最为后悔的事，就是在找到工作到毕业这段时间，大约一年有余，竟完全未学习任何新内容。彼时女朋友正在考研，那这段时间大概又可分为两个区间，即以女朋友考研初试为界：前半段每日十一点起床，接着就是去图书馆陪女朋友学习。表面上是陪伴学习，实际上大部分是在看剧和打游戏中度过。晚上则约同学或好友去酒吧，那时已不能称之为“小酌”，而可称为“酗酒”，总是到半夜方才大醉而归。后半段生活甚至现在已无甚印象，更可见颓废到何种程度，以至无标志事件可供回忆。

找工作过程的过于顺滑，更易让人目空一切。古人云“人之患在好为人师”，诚哉此言！早早结束校招，更给了以“过来人”身份说话的资本。而沉溺其中，终会使陷于此身份，从而失去前进之动力。一口一句“大佬”，已使人飘飘然，更何况有些所谓“技术群”聊天，言必称“神”，一个小小的微信群竟能封神几十位，无神论者无法接受，一神论者亦觉得不可思议。于是忽有一天感到厌倦，毕竟不能一辈子吃校招的饭（更何况我还无此饭可吃），既与我本心违背，亦不利于进步。于是痛定思痛，一天之内退掉了所有的所谓“技术群”，甚至牛客都卸载了（对不起）。然而这又是 2022 年的事情了，本身校招就只准备了三个月，无夯实的基础，更有很多运气成分，这损失的一年光阴又愈加令人惋惜了。

以上是对前四年的总结。转变大都发生在 2022 年，无论何时发生转变都乃万幸，希望悬崖勒马尤未晚矣。

工作自然无甚长期内容可说，毕竟我仅仅入职一年半，但纵使是这十几个月之经历，亦可称为风云变幻了，令我领略了拥抱变化之深刻含义。

本组事务，最初仅是为活动提供技术支持。组内分工明确，一部分负责开发框架和组件化，力图让业务需求无需特殊开发，或只需稍加定制即可满足；剩下成员则是纯业务开发，高并发细节几乎无需考虑，所有的细节已由框架处理好。原则上来说，业务组织的活动，大部分由组件化即可直接满足，业务仅需拖拖拽拽即可搭建好一个活动，无需开发的介入。仅剩其中很小一部分的活动需要特殊开发，然而即使是这一小部分，亦会消耗巨大的人力。于是本组发力于组件化功能之完善，在我入职之前，组件化已完善到，业务开发仅需配 json 而无需具体去编写定制代码，即可完成定制逻辑开发。组里框架已高度成熟化，组里分工也理所当然地接近凝固。

待我入职之时，业务开发已无需如先前巨大之人力，除非是在重大活动期间，才会增添人力以示重视，否则，一个较大的活动仅需一位业务研发去负责，如果较为熟练甚至可以同时开发两三个活动。在此背景下，我便“理所当然”地闲下来了。此时恰好，北京的一个负责 ToB 平台的组正陷于人力困扰中，向大部门请求抽调借人。于是我被选中，开始了远程开发之路。

坦言之，在公司内部，ToB 开发一般不会比 ToC 开发更受重视，对于校招生来说，ToC 业务的第一直觉，就是可以接触大流量高并发场景，但那实际上仅限业务刚起步之时。在一个已经有高度成熟框架的业务中，底层的细节已被巨大的抽象所屏蔽，在承担更重要职责时也通常会为了求稳而非求变，对框架的一点点修改都是不可控而风险巨大的，更何况还是在倒排压力下。无论什么原因，对底层做修改都是很难的，除非彻底无法满足业务需求，不得不完全推翻整个框架，而这种情况下，上级会质疑这个组存在的意义，而倾向于将新框架的开发交由其他组，除非这种对框架的升级和迁移是渐进式的而非一刀切，但这又回到了上面所说的投资产出比（ROI）上去了。

总而言之，ToC 不见得都能接触高并发，这里算是澄清这个误区。

和北京同事合作的过程是十分愉快的，整个组内氛围十分放松，不会因为你的一点错误而对你横加指责，亦无甚惩罚措施。再加上我是远程合作，上班时间可随心所欲，经常十一点半才到达工区，坐上十五分钟就去排队吃饭，接着就是午休时间，实际工作时间是从下午开始的。就这样度过了快乐的半年，我甚至以为这种生活可以一直延续，而外界那些“卷”的传闻仅仅停留在传闻的程度而已，不会真的有人这样卷。

转变来自于产品经理的变动，具体原因已不甚清晰，但结果却很奇怪。本组要放弃原本的活动业务，转而接下那个 ToB 平台作为主要业务，而原本北京那组人则集体转岗。整个交接过程混乱而冗长，这个平台年轻而苍老，年轻在于，21 年 56 双月该平台刚刚经历过一次重构，代码都很新，而苍老在于，该平台已发展了 3 年，自 19 年该平台立项以来，无数积累下来的历史逻辑，已无任何可能被完整了解，堆积起来的业务定制逻辑，即使找到当时提出的产品也无法完整地说出个所以然。与此同时，原本的部门领导，转岗到了一个新业务，令他的下属们：各组的领导，和各领导的嫡系，蠢蠢欲动。在新任部门领导尚未有所动作之时，几乎是打包似的向新业务转岗。这种情况直到新任部门领导锁住本部门转岗后才有所平息。而在此之前，本组的领导已和组内几个嫡系都已成功转岗出去了。

人员变动导致人心惶惶，整个 22 年上半年几乎没有做成什么事情。我由于提前参与平台业务，负责其中主要的两个模块的交接，然而交接后依旧是我来负责，如同左手倒右手一般。

本组的领导转岗后，一段时间内，本组领导由部门领导兼任。六月份时，部门领导提议，将原本测试内部的质量双周会扩展为产研测都要参与的技术双周会，并同时开始狠抓平台质量。这本身是一件好事，然而粗暴的执行导致了双周会偏离了原本设置的初衷。其中最令人闻风丧胆的措施，就是统计 bug 估分比。测试阶段发现的 bug 个数，比上开发和联调的天数，即作为研发开发某个需求时的 bug 估分比，由此这也被称为“bug 比人天”。这个计算方式十分简单和直观，但是似乎没有考虑到一些边界问题，例如一个很小的需求，开发联调只需要一天，那么被测出 1 个 bug，bug 估分比就达到了 1。领导们为 bug 估分比设置一些指标，以达到保证研发质量的目的，双周会上会对 bug 估分比不达标的研发进行质询，如果该研发是外包，那么他甚至会面临被清退的危险。最初这个指标被定为 1，后面逐渐收紧到 0.5，甚至 0.3。这其中当然有严抓研发质量之功劳，但更多的是，由于研测关系此前一直十分和谐，测试同学在测试过程中可能只是口头提出问题，而不会从系统提出 bug。或者在和数据同学合作的过程中，由于数据侧不关注 bug 估分比这个数据，可以将 bug 转给数据同学。这种互相“包庇”的情形最终被测试的领导发现后，严格禁止了这种行为，如果发现某个需求的 bug 过少，测试领导甚至会亲自下场测试。这无疑加剧了研测冲突。曾有一测试同学，严格按照规章办事，她测出的 bug 过多，最终直接或间接地导致了一名正式研发主动离职和一名外包研发被清退。在后期本组领导终于意识到诸多问题后，废除了这个指标，双周会上不再关注了。

然而双周会上的另一环节，则更像一场闹剧。由于本平台是个面向运营的 ToB 平台，每天都会收到来自运营同学的 oncall，大部分是咨询平台的使用方法，少部分则是由于平台 bug 导致流程无法继续进行。在双周会上，会由测试整理出周期内 oncall 来的平台问题，一个一个讨论以找到责任人和后续避免的方法。然而实际执行中，找到责任人似乎比后续避免更为重要。有些问题历史十分悠久且模糊，难以精确定位到某个人，有些问题则是产品设计问题，而通常，如果确是研发问题，测试则有连带责任，因为他们在测试阶段没能发现而导致 bug 逃逸到线上。由于各种模糊和不准确性，其中的运作空间十分大。例如研发可以把问题推给产品或者之前开发这个模块的人，而测试则可以说在测试阶段并无此问题，可能是后续需求影响甚至是研发在测试流程结束后偷偷更改代码。于是每当这个环节，产研测三方相互攻讦，反正大部分已无证据，重要的无非是否能在气势上压倒对方。有趣的是，如果某一方没有参加双周会，那么剩下两方则会默契地将问题向未参会的一方推。否则，除了确是产品设计问题外，落入下风的通常是研发，测试通常会直接质问为何要在测试结束后更改代码，而相关研发也懒于翻出 git 记录来解释。这种质问通常直接来自于测试的领导，而本组领导由于初来乍到，似乎也不太敢于抗辩。

另一个好心办坏事的例子就是 code review。code review，本意为通过在线上同时审阅代码，来发现潜在的代码逻辑问题，以保证这种逻辑问题不至逃逸到线上，最终不可收拾。可谓为测试后的最后一道放线。在平台业务尚未交至我组时，北京一组并未建立起严格的 code review 制度，代码质量由个人把控保持。本组领导初来乍到，便要求全部上线代码必须经过 code review。然而其忽略了本组之现状，即单个业务方向，可能仅有一两个一线研发直接负责，而这些业务方向下通常又有多个细分。如前文之所言，业务已膨胀到无任何研发能够完全将某个方向的细节了然于胸，而对其他模块之业务更是一知半解。然而线上或线下的 code review 通常需要邀请三到四个人，在这种业务分隔的情况下，code review 内容更偏向一些无关紧要的问题，例如一些代码风格和命名规范问题，而一些真正的逻辑漏洞则不可能被发现，使得这些问题依旧会逸至线上。而需求负责人也不得不花上个几小时，在线上或线下的会议上，来给一些可能根本就没有听懂的人，费尽口舌地去解释代码是如何满足业务需求的。

一线研发疲于应付这些意义不大的事情，于是整体研发效率不高也是可以解释的。而纵使在人力不充足的情况下，仍然要在这么小的一个组（三十人左右）实施比较严格的上下级制度，设置了一个与小组体量不太相称的中层管理机构。中层管理们通常不负责具体需求的开发，而只是管理其负责的模块下的人力分配和 code review，导致本就不富裕的人力更加紧张。而本组在人员调配上也是较为混乱的。一些同事甚至从转为平台业务开始，就一直在其下各个子方向流转，其不稳定性更加剧了对本组业务的不满。

纵使工作一地鸡毛，然亦非完全毫无收获。ToC 到 ToB 的转变，工作重点完全不同。ToC 业务中，高并发大流量场景下，如何保证业务的高可用，成了重中之重。为此目标，甚至可以丢弃一些用户请求来保证整体的可用性。这在 ToB 平台则是完全无需考虑的事情，于是关注重点更多转移到一致性上，大多数情况下，保证最终一致性，即在上下游环境不完全可靠的情况下，保障最终（可能是在多次重试后）上下游数据一致，这一般就考虑接口的幂等性；对于需要强一致性的场景，甚至需要引入分布式事务。

除此之外，技术上似乎并未有明显的进步。大都延续了先前的浅尝辄止：年初计划编写一个 RISC-V 的模拟器（emulator）。目标定的很大：要能运行 Linux，提供 VGA 输出，并最终实现为一个比较完善的 debug 平台。然而在实现 RISC-V 的一个子集，足以运行 xv6 后，这个项目就被搁置到了现在，如果不是年度总结，它可能还会一直被搁置下去。

年中基本都在交接和内卷中度过，无甚时间关注自身的技术发展。至十月时，痛感一事无成，于是开始制定计划，准备夯实“丢失的基础”，如分布式、计网和计组。于是在学了大约两个月的 6.824 后，因为疫情在床上躺了几天后，也被搁置了。

我大概是个纠结的人，一方面不满于其他人对自己的压力，另一方面又会自己给自己施加更多的压力，纵使是对一些小事，如组内分享，也会感到压力巨大，这种心理状态甚至严重影响到了我的心理和身体健康。于是在痛苦挣扎了半年，灌了自己半年的酒后，最终还是不得不和自己和解，淡化心中强加给自己的压力，不再如此争强好胜而尝试看淡一切。杜康不能使你忘掉一切，只有你自己可以。

曾有一日，在为无穷无尽的平台 oncall 淹没后，忙里偷闲来到前端处，恰逢与我合作前端同学正在改 bug。我在他身后站了一会，看他忙于在 ide 和 oncall 窗口间切换。于是问他：“你不感到烦吗”。他转头看了我一眼，说了句：“其乐无穷吧”

是啊，其乐无穷吧，不然又能如何呢？

于是，2022 年就这么过去了，沉重而轻盈。

本想着，开头那段歌词用下面这段：

> Not a shirt on my back
> 
> Not a penny in my name
> 
> Lord I can't go home this way

但似乎尚未落魄至此，前路虽暗淡，也可望到前路将更加暗淡，然仍心存光明。这一点光明，不期照亮前路，但求照亮自己。

> 这篇总结本计划在回家的高铁上完成，却未曾想写了三天。中间思绪万千，也可见其间文风也有较大变化，基本都与我之心境有关。从描述工作时的愤懑，到最后的坦然，这篇文章同样经历了标题所述的变化。然仍会为不忿之事而不忿，足见尚未完全放下。最终在纠结中，还是觉得不如就此停笔，令新一年的我继续去纠结，或许也是其乐无穷吧

[2022](https://ziyang.moe/article/tag/2022/) [年终总结](https://ziyang.moe/article/tag/%e5%b9%b4%e7%bb%88%e6%80%bb%e7%bb%93/)

>参考链接：[https://ziyang.moe/article/2022_final.html](https://ziyang.moe/article/2022_final.html)，整理：沉默王二
