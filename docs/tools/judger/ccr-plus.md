author: Ir1d, zhengqingyu0311

## CCR Plus

**CCR Plus** 是一款适用于 NOI 系列比赛的开源的跨平台测评环境，使用 Qt 编写，目前支持 Windows 和 Linux。

源代码托管于 [sxyzccr/CCR-Plus](https://github.com/sxyzccr/CCR-Plus)。

## CCR-Plus 使用配置指南
### 一、前言
> CCR Plus 是一款适用于 NOI(National Olympiad in Informatics) 系列比赛的开源的跨平台测评环境，使用 Qt 编写，是对原版 CCR 测评器的重大改进。CCR Plus 目前支持 Windows 和 Linux 两大操作系统，可以方便地配置与评测传统题、提交答案题等题型。
 ***
## 使用方法
### 下载 CCR-Plus
1. 首先在 CCR-Plus 官网地址下载 CCR-Plus ，如 GitHub 响应太慢的话可以在 CSDN 下载：
 - **[GitHub下载地址，点击以下载](https://github.com/sxyzccr/CCR-Plus/releases)**
 - **[CSDN 下载地址，点击以下载](https://download.csdn.net/download/zhengqingyu0311/86396623)**
2. 下载完成后，打开CCR-Plus。
![在这里插入图片描述](https://img-blog.csdnimg.cn/763dbb23bcb74a4385e596373baa3333.png)
如图就是正常界面

***
### 创建试题

如下图，单击 `` 竞赛 - 新建`` 或打开竞赛。

![在这里插入图片描述](https://img-blog.csdnimg.cn/e79a5415aaab4fd9a3c23643dc7d1e59.png)
***

**由于我们现在还没有选手文件，不用理会，单击"==是=="即可。**

![在这里插入图片描述](https://img-blog.csdnimg.cn/7a84a04b74494c7aac738d940a866dfd.png)
***

然后我们就来到了一个空白的比赛界面。

![在这里插入图片描述](https://img-blog.csdnimg.cn/5d3498dfc9fb4212b6f0e0a66b03f9cf.png)
***

***
现在我们打开刚刚比赛所在文件夹（刚刚提示创建的文件夹）。   

![在这里插入图片描述](https://img-blog.csdnimg.cn/7a83d742c25440ceb805c6cff3586599.png)

***

然后导入题目，在``data``中导入输入数据，文件目录应像下面所示。
```document
比赛文件夹(如 03.11 第一次测试，名字自定)
| -- data
|    | -- Problem 1 (第一题，名字自定，如 “a+b”，“num” 等，数据前缀名可以自己改，但 ".in" , ".out" 必须要对应)
|    |     |   `-- <data01>.in
|    |     |   `-- <data01>.out
|    |     |   `-- <data02>.in
|    |     |   `-- <data02>.out
|    |     |   `-- <data03>.in
|    |     |   `-- <data03>.out
|    |     |   `-- <data04>.in
|    |     |   `-- <data04>.out
|    |     |   ...
|    | -- Problem 2 (第二题，名字自定，如 “a+b”，“num” 等)
|    |     |   `-- <data01>.in
|    |     |   `-- <data01>.out
|    |     |   `-- <data02>.in
|    |     |   `-- <data02>.out
|    |     |   `-- <data03>.in
|    |     |   `-- <data03>.out
|    |     |   `-- <data04>.in
|    |     |   `-- <data04>.out
|    |     |   ...
|   ...
|    | -- Problem n (第 n 题，名字自定，如 “a+b”，“num” 等)
|    |     ...
|   ...

```
如下图，这里只有一题，您可以创建多道题目。

![在这里插入图片描述](https://img-blog.csdnimg.cn/63dac135fbab44aaab7f3073c7938278.png)
***

输入数据必须以``.in``和``.out``结尾，如下图。

![在这里插入图片描述](https://img-blog.csdnimg.cn/bd3f06264619469b954f8d9f910ca3b3.png)
***

### 配置试题

如下图，单击 ``竞赛 - 配置试题`` 进行测试数据配置。

![在这里插入图片描述](https://img-blog.csdnimg.cn/72697ae0d1414d12a1660e5aa6873eae.png)![在这里插入图片描述](https://img-blog.csdnimg.cn/5b054a28ec60475db60429211635e178.png)
### 点击“ 高级配置” 

![在这里插入图片描述](https://img-blog.csdnimg.cn/1b6450d0307c4ee180485708ea5daa3c.png)
可以在这里进行相应 数据后缀名自定义，捆绑测试，数据点配置，编译指令设置（点击 “编译器，测试点” 目录）。

点击“应用”，退出界面，按 F5 刷新。

![在这里插入图片描述](https://img-blog.csdnimg.cn/359705a875fe48628e31f0b7b47cdaef.png)
### 环境变量

如果你没有配置环境变量，这时候测评是没有用的，出现下面的情况：

![在这里插入图片描述](https://img-blog.csdnimg.cn/d0f8adcbf3d74faa9e201472653fe66e.png)

> 由于使用须添加==环境变量==，所以出现下图**无效的编译器**的情况，且如何配置是一个很大的问题，[具体配置方法可以参考这篇文章](https://blog.csdn.net/chenz71/article/details/128280185)
 
***

配置完后，刷新，在测评中按相应操作即可。

![在这里插入图片描述](https://img-blog.csdnimg.cn/6f4e3ff7199e4febac51657f511fe53a.png)

（效果图）

***
下次使用时，直接拖动比赛文件夹至评测器即可。

码字不易，点个赞再走呗。（后续内容完善中）




