---
title: 从零开始搭建一个属于自己的网站（记录学习历程）
date: 2020-12-01 16:36:55
tags:
  - 教程
  - Hexo
  - 分享
categories:
  - 小璃的教程
---
# 学习目录



![index-preview.jpg](https://i.loli.net/2020/03/23/bTmpQe6tgf35nj2.jpg)

> 一个轻、快、可爱的hexo主题。

- PV: [Yun v1.0 - Strato | bilibili](https://www.bilibili.com/video/BV17t4y1S7tz)
- Coding 镜像: [hexo-theme-yun](https://yunyoujun.coding.net/public/hexo-theme-yun/hexo-theme-yun/git/files)

## 前言

>其实该博客的搭建也是今天偶然从朋友那里得知的，通过了一上午的努力成功搭建。以下为学习文档，此外非常感谢[云游君](https://github.com/YunYouJun)的开源。！！！！

一份详细的搭建文档和使用文档

- 云游君`《教你如何从零开始搭建一个属于自己的网站》`: <https://www.yunyoujun.cn/share/how-to-build-your-site/>
- 云游君`《使用指南》`: <https://yun.yunyoujun.cn/guide/config.html#快速开始>



## 提前准备

1. 首先你需要一个[GitHub](https://github.com/)的账号，这个不用多说邮箱注册就ok。
2. 准备好终端`win+r 输入cmd`，[什么是DOS终端](https://baike.baidu.com/item/DOS/32025?fr=aladdin)。
3. 准备好你的**耐心**和**时间**~

如果你已经使用了这个主题，可以前往 [Demo Sites | 示例站点](https://github.com/YunYouJun/hexo-theme-yun/issues/3) 留下你的站点，作者大大将会将其添加到下方的示例站点中。

<table align="center">
  <tr align="center">
    <td>
      <a href="https://www.yunyoujun.cn" target="_blank">
        <img width="80px" src="https://www.yunyoujun.cn/images/avatar.jpg"/>
        <br />
        <sub title="希望能成为一个有趣的人">云游君的小站</sub>  
      </a>
    </td>
    <td>
      <a href="https://yuexiaoya.info" target="_blank">
        <img width="80px" src="https://yuexiaoya.info/photo.jpg" alt/>
        <br />
        <sub title="当然是用来记录历程啊，不好看怎么行！">落梅听风雪</sub>
      </a>
    </td>
    <td>
      <a href="https://blog.sernikki.cn/" target="_blank">
        <img width="80px" src="https://i.loli.net/2020/03/13/xzKUC1NEj5OicfA.jpg"/>
        <br />
        <sub title="有瑕人无玉">神崎日照の小窝</sub>
      </a>
    </td>
    <td>
      <a href="https://mesmerxx.github.io/" target="_blank">
        <img width="80px" src="https://mesmerxx.github.io/girl.jpeg"/>
        <br />
        <sub title="ヾ(❀╹◡╹)ﾉ~">mesmerxx</sub>
      </a>
    </td>
    <td>
      <a href="https://ddindex.github.io/" target="_blank">
        <img width="80px" src="https://ddindex.github.io/images/avatar.jpg"/>
        <br />
        <sub title="双手抓楼上的大胸">多酱的部落格</sub>
      </a>
    </td>
    <td>
      <a href="https://spreadwings-sky.github.io/" target="_blank">
        <img width="80px" src="https://spreadwings-sky.github.io/Yun.png"/>
        <br />
        <sub title="浊以静之徐清，安以动之徐生">俺たちに翼はない</sub>
      </a>
    </td>
    <td>
      <a href="https://www.nbamax.com/" target="_blank">
        <img width="80px" src="https://www.nbamax.com/images/avatar.png"/>
        <br />
        <sub title="YouTube NBA精彩视频分享博客!">NBA·Max</sub>
      </a>
    </td>
    <td>
      <a href="https://sblog.addesp.com/" target="_blank">
        <img width="80px" src="https://www.addesp.com/avatar.jpg"/>
        <br />
        <sub title="记录回忆，分享笔记。">ADD-SP的博客</sub>
      </a>
    </td>
  </tr>
  <tr align="center">
    <td>
      <a href="https://hellsakura.github.io/" target="_blank">
        <img width="80px" src="https://hellsakura.github.io/images/avatar.jpg"/>
        <br />
        <sub title="我只是一条咸鱼">琉的小窝</sub>
      </a>
    </td>
    <td>
      <a href="https://nancheng58.github.io/" target="_blank">
        <img width="80px" src="https://nancheng58.github.io/images/nancheng58.jpg"/>
        <br />
        <sub title="我好菜啊啊啊啊啊">nancheng58</sub>
      </a>
    </td>
    <td>
      <a href="https://alexzou14.github.io/" target="_blank">
        <img width="80px" src="https://cdn.jsdelivr.net/gh/AlexZou14/CDN/img/touxiang.jpg"/>
        <br />
        <sub title="笔记记录，自我激励">秩同道合的博客</sub>
      </a>
    </td>
    <td>
      <a href="https://yenpou.github.io/" target="_blank">
        <img width="80px" src="https://yenpou.github.io/images/timg.jpg"/>
        <br />
        <sub title="今朝有酒今朝醉，明日愁来明日愁">道之遠兮</sub>
      </a>
    </td>
    <td>
      <a href="http://www.romastar.cn/" target="_blank">
        <img width="80px" src="https://personalblog-1301685299.cos.ap-nanjing.myqcloud.com/MyBlog-Images/Personal-Info/Avatar.jpg"/>
        <br />
        <sub title="记录我的生活经历以及学习历程~~">柠檬君的小站</sub>
      </a>
    </td>
    <td>
      <a href="http://www.kumybryce.work" target="_blank">
        <img width="80px" src="https://kumybryce.gitee.io/myblog/img/favicon.png"/>
        <br />
        <sub title="努力一点，再努力一点">山山的掉发历程</sub>
      </a>
    </td>
    <td>
      <a href="https://hexo.cool" target="_blank">
        <img width="80px" src="https://cdn.jsdelivr.net/gh/imoshanghua/file/img/avatar.jpg"/>
        <br />
        <sub title="待我熬尽一日苦，喂你一口甜！">陌上花的小栈</sub>
      </a>
    </td>
    <td>
      <a href="https://lymtics.top" target="_blank">
        <img width="80px" src="https://gitee.com/Renen/blogpic/raw/master/sources/BlogAvatar.jpg"/>
        <br />
        <sub title="Love You More Than I Can Say.">Lymtics</sub>
      </a>
    </td>
  </tr>
  <tr align="center">
    <td>
      <a href="https://myperfect.work" target="_blank">
        <img width="80px" src="https://myperfect.work/image/20161015094748_YFfPV.jpeg"/>
        <br />
        <sub title="记录学习历程，每天进步一点点！">南楼画角的小站</sub>
      </a>
    </td>
    <td>
      <a href="https://copur.xyz/" target="_blank">
        <img width="80px" src="https://q1.qlogo.cn/g?b=qq&nk=1935576264&s=100"/>
        <br />
        <sub title="记录学习历程，每天进步一点点！">乐得自在的小破站</sub>
      </a>
    </td>
    <td>
      <a href="https://blog.zjgsujz.cn" target="_blank">
        <img width="80px" src="https://cdn.jsdelivr.net/gh/Pakchoi1/image-host/blog/avatar.jpg"/>
        <br />
        <sub title="it萌新的进阶之路">小白菜的博客</sub>
      </a>
    </td>
    <td>
      <a href="https://edenjohnson.me" target="_blank">
        <img width="80px" src="https://cdn.jsdelivr.net/gh/MEMZSONBILI/PicGoBed@master/images/20200625174516.jpg"/>
        <br />
        <sub title="去探索，去发现">Eden瞎写小屋</sub>
      </a>
    </td>
    <td>
      <a href="https://chitang233.github.io/" target="_blank">
        <img width="80px" src="https://s1.ax1x.com/2020/06/27/N63K8e.jpg"/>
        <br />
        <sub title="只是一个普通的初中生罢了">池某的小博客</sub>
      </a>
    </td>
    <td>
      <a href="https://xmuli.tech" target="_blank">
        <img width="80px" src="https://cdn.jsdelivr.net/gh/xmuli/xmuliPic@pic/2020/xmuli_yj_256px.png"/>
        <br />
        <sub title="与子偕臧">偕臧的小站</sub>
      </a>
    </td>
    <td>
      <a href="https://www.rogeroger.net" target="_blank">
        <img width="80px" src="https://rogeroger.oss-cn-beijing.aliyuncs.com/img/rogeryu.jpeg"/>
        <br />
        <sub title="啊啊啊啊啊啊啊啊">ROGEROGER</sub>
      </a>
    </td>
    <td>
      <a href="https://leostudiooo.github.io" target="_blank">
        <img width="80px" src="https://avatars0.githubusercontent.com/u/35419343"/>
        <br />
        <sub title="恰同学少年，风华正茂；书生意气，挥斥方遒。">LeoStudio</sub>
      </a>
    </td>
  </tr>
</table>

## 一定要记住的命令

本地hexo服务启动命令:
- 在本地测试肯定不能少的命令！！


    hexo server


部署到GitHub Pages:
- 线上更新网站~
 

    hexo deploy


备份文件到云端（常用）：
- 这几句命令将是你以后每次备份所需要输入


	# 添加到缓存区
	git add -A
	git commit -m "这次做了什么更改，简单描述下即可"
	# 推送至远程仓库
	git push
	# 第一次提交，你可能需设置一下默认提交分支
	# git push --set-upstream origin hexo


