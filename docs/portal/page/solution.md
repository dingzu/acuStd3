---
title:  解决方案页
author:  wangyihan05@baidu.com
sidebarDepth: 1
---

# 解决方案页

解决方案页面用于介绍针对行业和各个实际场景的实际应用方案。使用丰富灵活的布局和样式让页面充满变化，提升页面表现力；采用组件化设计方式提升设计和开发效率与质量。

[[toc]]

## 页面内容要求

解决方案内必须有以下的内容：

| 内容名称         | 介绍        | 样式建议|
| ------------- |------------ | -----|
| 方案场景         | 该解决方案可以适用于哪些具体的应用场景 | <cms :name="'通用板块 001 号'"/> |
| 方案优势         | 该解决方案有哪些具体的优势                   | - |
| 功能/服务介绍         | 该解决方案能提供哪些具体的技术或服务           | - | 
| 客户案例         | 使用该解决方案的客户的介绍           | - | 
| 相关产品         | 介绍这个解决方案运用了哪些产品           | - | 

### 页面内容板块组合示意

解决方案页面的基本板块示意如下：内容板块的底色可以使用 <label class="color" id="color-fff">#ffffff</label> 、<label class="color" id="color-f5">#f5f5f5</label> 以及深色背景 <label class="color" id="color-28">#282828</label> 交叉的方式区分:

![解决方案框架](http://baiduyun-guideline.bj.bcebos.com/portal%2Fpage%2Fsolution%2Fsolutionpage.png)

::: tip 注意

1. 禁止连续两个板块都是深色背景样式
2. 顶部 banner 板块下的首个内容板块禁止使用深色背景样式
3. 深色背景前后的板块样式允许使用 <c :color="'#ffffff'"/> 和 <c :color="'#f5f5f5'"/> 两种背景颜色
4. 底部页脚之上必须要有一个行为引导板块，见 [行为引导板块](#行为引导板块)

:::

## 解决方案顶部板块

头部板块为居中布局，内容为居中布局。具体如下图

![解决方案页布局](http://baiduyun-guideline.bj.bcebos.com/portal%2Fpage%2Fsolution%2Fbannersolution.png)

## 行为引导板块

每一个解决方案页面的页脚之前都需要有一个 **行为引导板块** ，如下所示:



![行为引导板块示意](http://baiduyun-guideline.bj.bcebos.com/portal%2Fpage%2Fsolution%2Fpageaction.png)

::: tip 注意

行为引导板块的背景必须有一张图片，但是要注意控制颜色保持和前后板块的区分对比度

:::



<style>

#color-fff:before,#color-fff1:before{
  background : #fff;
  border : 1px solid #ebebeb;
}


#color-f5:before,#color-f52:before{
  background : #f5f5f5;
  border : 1px solid #ebebeb;
}

#color-28:before{
  background : #282828;
}

</style>