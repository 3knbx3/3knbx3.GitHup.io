<img width="1280" alt="image" src="https://github.com/3knbx3/3knbx3.GitHup.io/assets/138361341/ea4971d6-c149-49d4-b57f-6da7d174ef2f">---
layout: post
title: 敲代码进行时（一）
date: 2023-7-3
categories: blog
tags: [编程,体会]
description: 浅浅记录。
---

本身的话一开始打算建这个博客就是为了记录下敲代码的经历嘛。虽说学计算机类这门专业也快一年，但也还是似懂非懂的，学了些浅层的。现在大一小学期正好也开始上程序实践这门课，敲代码做题，那就正好可以每天来记录，学习一下。（虽说上机做着一如既往的很神呀⊙﹏⊙）

[![Fpe5m.md.jpeg](https://imglink.win/image/2023/07/03/Fpe5m.md.jpeg)](https://imglink.org/image/Fpe5m)
今天的话是一共十题。

一：判断上三角矩阵
![FpiJy.png](https://imglink.win/image/2023/07/03/FpiJy.png)
编了一下，这道题的话就是要实现当行数大于列数时，这里的数要为0.所以就先按行按列将全部数先输进去，然后判断行数大于列数时，这个数是不是0就行了。（要注意列小于行时，时j<i,不是j<x，）判断的话感觉还是要用不成立就为0，成立为1，最后再如是是0或不是0，就怎样怎样感觉方便些。
[![FpwGX.png](https://imglink.win/image/2023/07/03/FpwGX.png)](https://imglink.org/image/FpwGX)

二：时间换算
[![FpNR6.png](https://imglink.win/image/2023/07/03/FpNR6.png)](https://imglink.org/image/FpNR6)
时间换算的话感觉要注意的点首先就是关于时间的输入，要：：的输入话，现在咱会的就只有scanf("%d:%d:%d",x,y,z),其次的话就是时间转换了，用if来讨论感觉会有点麻烦，所以就全转换为对应单位，最后再输出。
![FpQEo.png](https://imglink.win/image/2023/07/03/FpQEo.png)

三：判断素数
![Fp6Bn.png](https://imglink.win/image/2023/07/03/Fp6Bn.png)
很经典的题，耗时较短的话在循环判定中要i*i<x;此外要注意的点就是首先先将1排除，然后再来比。比的话感觉还是用布尔函数这种比较方便。
![FpHJ7.png](https://imglink.win/image/2023/07/03/FpHJ7.png)

四：稳赢
[![FpJUi.png](https://imglink.win/image/2023/07/03/FpJUi.png)](https://imglink.org/image/FpJUi)
需要注意的点这里输入是字符串，要用string，平局的实现就靠循环到（k+1）的倍数实现，因为用的是while的循环，每次循环结束后i++。（一般来说不明确循环次数的都用while，知道的用for)
[![Fpmo1.png](https://imglink.win/image/2023/07/03/Fpmo1.png)](https://imglink.org/image/Fpmo1)

五：幸运彩票
[![FpzEF.png](https://imglink.win/image/2023/07/03/FpzEF.png)](https://imglink.org/image/FpzEF)
这道题的话明确是求6位数字的前，后三位之和，这6位数就做整体输进去，就用到了字符串，但是后面要进行加法，就要将字符转换成数字，然后计算就行了。
[![FpFtB.png](https://imglink.win/image/2023/07/03/FpFtB.png)](https://imglink.org/image/FpFtB)

六：大笨钟的心情
[![FpPA3.png](https://imglink.win/image/2023/07/03/FpPA3.png)](https://imglink.org/image/FpPA3)
首先就要输入24个数，每个数是分开的，所以就用数组，暂定24个全为0，然后靠循环来输入。其次的话，就是输入数字的范围，当并不在这个范围内就不运行，所以放在while循环的条件里。最后还要注意下要求输出的格式。
[![FplLJ.png](https://imglink.win/image/2023/07/03/FplLJ.png)](https://imglink.org/image/FplLJ)

七：统一一行文本的单词个数
[![Fp7lM.png](https://imglink.win/image/2023/07/03/Fp7lM.png)](https://imglink.org/image/Fp7lM)
这道题欠缺的东西确实有点多了，关于，字符串，字符数组的求其长度的函数，还有到底如何确定单词个数，怎样确定单词的位置。不能空格加1来求（空格可以是多个）虽然这个用python很好写呀，就以空格分割就行行了。print(len(list(input().split())))
[![FpaqG.png](https://imglink.win/image/2023/07/03/FpaqG.png)](https://imglink.org/image/FpaqG)

八：找最长的字符串
[![FpOBu.png](https://imglink.win/image/2023/07/03/FpOBu.png)](https://imglink.org/image/FpOBu)
这个的话主要还是就两两相比，长的保留，主要要注意的字符串的复制是strcpy.
[![FppSI.png](https://imglink.win/image/2023/07/03/FppSI.png)](https://imglink.org/image/FppSI)
 
九：出生年
[![Fp2os.png](https://imglink.win/image/2023/07/03/Fp2os.png)](https://imglink.org/image/Fp2os)
wow，虽然弄了会应该弄出来了，但不会高级的算法，就通过遍历x,来满足k的值来算的，条件的代码举例就很多。
[![FpCYZ.png](https://imglink.win/image/2023/07/03/FpCYZ.png)](https://imglink.org/image/FpCYZ)

十：查验身份证
[![Fpctf.png](https://imglink.win/image/2023/07/03/Fpctf.png)](https://imglink.org/image/Fpctf)

以上8道是小组的题目，个人两道感觉挺麻烦的，就后面再补，弄半天了现在脑壳有点旷。还是希望要多学学，多思考。那第一篇博客差不多就这样子了，很好奇弄出来是效果o>_<o
[![FptUx.jpeg](https://imglink.win/image/2023/07/03/FptUx.jpeg)](https://imglink.org/image/FptUx)













