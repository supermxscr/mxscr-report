---
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Welcome to Meeting
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# Welcome to Meeting

<div pt-12>
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Let's start <carbon:arrow-right class="inline"/>
  </span>
</div>

---
transition: slide-left
---

# <span class="text-green">已上线</span> LIST

- <span text-orange mr-1 >Update</span> 创作者首页顶部图片和视频数量统计，按照实际图片和视频来显示
- <span text-orange mr-1 >Update</span> 订阅优惠即折扣不能大于 60%
- <span text-orange mr-1 >Update</span> post未解锁按钮文案 按3种方式 显示不同的内容
- <span text-orange mr-1 >Update</span> post 详情 顶部增加 时间及解锁信息价格
- <span text-orange mr-1 >Update</span> collections 里 点到 Subscribed 菜单，tab里默认显示 Active
- <span text-orange mr-1 >Update</span> 底部 去除地址显示  登录页 去除 18+ 字样 


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #ff59a2 0%, #ffd200 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---
transition: slide-left
---

# <span text-orange>待上线</span> LIST

- <span text-orange mr-1 >Update</span> 背景的那个虚化，这个不用按照 OF 的来了 ，按照我们在以前的 增加模糊度
- <span text-orange mr-1 >Update</span> ADD SOCIAL LINKS 按钮间距
- <span text-orange mr-1 >Update</span> collection 页面不显示购买者列表
- <span text-orange mr-1 >Update</span> Instagram 禁止在浏览器内使用谷歌登录；当在 INS 里用户点击 Google 登录后，引导用户使用默认浏览器打开登录
- <span text-orange mr-1 >Update</span> Post 正文显示在图片上方
- <span text-orange>In progress</span> <span text-red mr-1 >New</span> 黑白主题 & 优化及统一代码
<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #ff59a2 0%, #ffd200 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: slide-left
---

# TODO LIST

1. <span text-red mr-1 >待联调</span> 用户绑定创作者 <span text-orange>(与朝峰对接)</span> 

2. <span text-red mr-1 >待联调</span> 用户互动任务 - 10-22已与沟通好需要的接口及逻辑<span text-orange>(与朝峰对接)</span> 

3. <span text-red mr-1 >待联调</span> 桌面通知 及 桌面入口 web app <span text-orange>(与浩哥对接)</span> 

- <span text-orange>In progress</span> 对接 <a href="https://firebase.google.com/docs/cloud-messaging/js/client?authuser=0" text-red>Google Firebase</a> 进行接受推送系统消息 

4. else 处理日常群里的问题
<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #ff59a2 0%, #ffd200 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: slide-left
---

# 黑白主题切换

#### 主要做的几件事
1. <span text-green mr-1 >Done</span> UI 层面黑白色的兼容修改
2. <span text-green mr-1 >Done</span> 废弃的代码<span text-red>删除不做修改</span>
3. <span text-green mr-1 >Done</span> 原来没有按照规范使用类名的 统一写法 并抽取 公共的样式在 main.less 及 unocss.config
4. <span text-green mr-1 >Done</span> 原来使用 n-button 组件的 全部改为公共的 DfansButton
5. <span text-green mr-1 >Done</span> naive-ui 的表单样式 黑白主题兼容
6. <span text-orange>In progress</span> varlet/ui 的表单样式 黑白主题兼容
7. <span text-orange>In progress</span> 公共组件抽取 及 替换已在使用的地方<span text-orange>(后续我会出个文档描述下具体的组件功能及使用)</span>
8. <span text-orange>In progress</span> 全局滚动加载 不依赖 window 的滚动, 使内部盒子作为滚动层
9. <span text-orange>In progress</span> <span text-red>删除本地的 icon 图片(减少代码体积及静态资源请求)</span>能在 icones.js.org 里找到替换的就不适用图片 📢 特殊情况才使用图片
10. <span text-orange>In progress</span> 删除废弃的接口定义 及 整合组件的目录结构

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #ff59a2 0%, #ffd200 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: slide-left
---

# 接下来需要做的事情

1. naive-ui 及 varlet/ui 的表单组件 更换为 vuetify3


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #ff59a2 0%, #ffd200 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
class: text-center
background: https://cover.sli.dev
---


# THANKS ALL


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #ff59a2 0%, #ffd200 65%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>
