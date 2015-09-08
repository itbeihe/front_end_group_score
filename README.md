# 前端团队评分
看软件随想录，看到了乔尔测试，就想整理一个粗略的前端团队质量测试。当然这个肯定非常业余，仅仅供参考。

### 乔尔测试
这是乔尔(软件随想录作者)在2000年提出的一个超简单的软件团队质量测试方法。

```
1. 你们用源码管理系统吗？
2. 你们能一键编译么？
3. 你们做每日编译么？
4. 你们有bug数据库么？
5. 你们在写新代码前修改以前的bug吗？
6. 你们的进度表是最新的么？
7. 你们有软件规格说明书么？
8. 程序员的工作环境安静吗？
9. 你们使用了能买到的最好工具吗？
10. 你们有测试人员吗？
11. 你们面试时会要求应聘人员写代码吗？
12. 你们做过走廊可用性测试吗？
```

每项回答只用回答是或否，不用统计每天写多少代码，代码bug率多少，bug存活周期。“是”加一分，“否”不记分。
12分是完美，11分是尚可，10分以下就说明团队问题挺多。结果是很多公司都是很低的评分，甚至二三分。

相关资料：
 [乔尔测试](http://www.joelonsoftware.com/articles/fog0000000043.html)
 [乔尔测试（翻译）](http://www.oschina.net/translate/12-steps-to-better-code)

### 前端团队测试

乔尔测试是一个很早的测试了，是针对传统软件团队的测试，对于前端团队呢？前端是个很新的工种，专业的前端团队也都是08之后开始飞速发展的，这几年也开始融入工程化的思想。变得越来越专业，质量越来越高，我们也需要一个简单的测试，去评估一个团队靠谱程度。
根据前端的一些特殊性，对乔尔测试做了一些修改，修改后如下。

```
1. 你们使用版本管理系统的分支功能么？
2. 你们能一键构建么？
3. 你们有做持续集成么？
4. 你们有正确使用bug管理软件么？
5. 你们在写新代码前修改以前的bug吗？
6. 你们的进度表是最新的么？
7. 你们有软件规格说明书么？
8. 程序员的工作环境安静吗？
9. 你们使用了能买到的最好工具吗？
10. 你们有测试人员吗？
11. 你们有足够的分享和团建活动么？
12. 你们有专业的UE人员么？
```

### 1.你们使用源码管理系统的分支功能么？

乔尔测试是在2000年编写的，现在已经2015年了，源码管理系统早已成为软件开发的标配。在git，svn大行其道的现在，我认为对代码管理的要求，应该更进一个档次，这里我暂且认为使用分支功能说明一个团队在使用版本管理系统足够成熟。
在团队中，多个需求并行开发是常有的现象，仅仅单主干开发，是会出现各种协调问题的，这在一个成熟团队当中是不应该出现的。

### 2.你们能一键构建么？

乔尔测试中是说编译，编译是编译型语言要作的事情，js是解释型语言，并没有这个步骤。早期我们开发是很欢乐的所见即所得，但是现在的前端，有一系列的工程化问题要去做:如静态资源的压缩，合并，加载;组件化和模块化等等事情。针对这些事情，如果没有对应的工具，去自动完成这些事情，甚至优化相关事情没做，可以认为是不够成熟的前端团队。

### 3.你们有做持续集成么？

这是跟工程化紧密相关的前端话题，也是当前最热的问题之一。持续集成保证第一时间发现一些很明显的bug。

### 4. 你们有正确使用bug管理软件么？

这条没变动，参照[乔尔测试（翻译）](http://www.oschina.net/translate/12-steps-to-better-code)

### 6. 你们的进度表是最新的么？

这条没变动，参照[乔尔测试（翻译）](http://www.oschina.net/translate/12-steps-to-better-code)

### 7. 你们有软件规格说明书么？

这条没变动，参照[乔尔测试（翻译）](http://www.oschina.net/translate/12-steps-to-better-code)

### 8. 程序员的工作环境安静吗？

这条没变动，参照[乔尔测试（翻译）](http://www.oschina.net/translate/12-steps-to-better-code)

### 你们使用了能买到的最好工具吗？

这条没变动，参照[乔尔测试（翻译）](http://www.oschina.net/translate/12-steps-to-better-code)

“顶尖的开发团队是不会亏待程序员的”，这句话相当赞同。在今天，浏览器随随便便几百兆内存，一个IDE近1G内存…… 而前端调试由往往多开浏览器，甚至多开虚拟机，加上IDE，各种工作软件，没个8G以上内存，双显或24寸以上大屏，你怎么能去指望一个前端开心工作。

### 10. 你们有测试人员吗？

这台也没变哦，测试人员今天应该标配了，是否把标准到升到有自动化测试？

### 11. 你们有足够的分享和团建活动么？

乔尔测试中“你们面试时会要求应聘人员写代码吗？”，这条在中国接近不现实的，大家都很忙，没几个人愿意当场写代码了。看代码也可以去应聘者的项目呀。更何况我们还有试用期呢。
本质上乔尔测试应该想看这个人与团队合不合的来，追求的是团队人员气场相合。所以这里就看团队的分享和团建活动吧，团建活动未必就是吃喝旅游，也可以是一些头脑风暴啦，团队活动拉之类的事情。

### 12. 你们有专业的UE人员么？

可用性的问题，交给专业的UE去做更好，请不要让不擅长设计的前端去搞设计呀。
