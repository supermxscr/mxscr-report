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

# 上线 LIST

<div v-click>

#### 【运营后台】- <span class="text-green">已上线</span>

- <span text-red mr-1 >NEW</span>
- <span text-red mr-1 >NEW</span>
- <span text-red mr-1 >NEW</span>

- <span text-orange mr-1 >Update</span> 0.5 USDT 改为 1 USDT
- <span text-orange mr-1 >Update</span> 修改 Post 价格这里的提示文案 Remove the PPV price before changing the post to a subscription or adding it to a collection.
- <span text-orange mr-1 >Update</span> Schedule Post 增加编辑入口
</div>

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

# 上线 LIST

<div v-click>

#### 【dFans】- <span class="text-green">已上线</span>

- <span text-orange mr-1 >Update</span>订阅列表按钮分类显示
- <span text-orange mr-1 >Update</span> vault 新增相关优化 (搜索 滚动 等)
- <span text-orange mr-1 >Update</span> videoguide 增加视频教程
- <span text-orange mr-1 >Update</span> Post编辑PPV 订阅 合约 去除15天限制, 及post分享只保留在TG里显示
- <span text-blue mr-1 >Style</span> 设置信用卡弹窗高度固定
- <span text-blue mr-1 >Style</span> 发post 选择合约及 订阅 新版样式
- <span text-blue mr-1 >Style</span> search 头像及 collections - CREATORS 头像显示
<!-- - <span text-blue mr-1 >Style</span> 修复TG 小程序ios下页面滚动底部有 34px 的安全区域 -->
<!-- - <span text-blue mr-1 >Style</span> 修复ios 不足一屏页面有滚动效果 -->
</div>

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

<div v-click>

### TG

1. <span text-red mr-1 >NEW</span> 用户绑定创作者
</div>

<div ml-6 v-click>- <span text-orange>In progress</span> Home页 绑定账号提示</div>
<div ml-6 v-click>- <span text-orange>In progress</span> Settings - account - connect dFans account 绑定入口</div>
<div ml-6 v-click>- <span text-orange>In progress</span> 邮箱验证码绑定弹窗</div>

<div v-click>

2. <span text-red mr-1 >NEW</span> 用户互动任务
</div>

<div ml-6 v-click>- <span text-orange>In progress</span> 背景图部分 需要 动画效果</div>
<div ml-6 v-click>- <span text-orange>In progress</span> Follow us on X</div>
<div ml-6 v-click>- <span text-orange>In progress</span> Invite friends</div>
<div ml-6 v-click>- <span text-orange>In progress</span> Repost dFans.xyz on x</div>
<div ml-32 text-red text-sm v-click>注:  需要提供 x 某一篇的链接</div>

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

<v-click>

### dFans

1. <span text-red mr-1 >⭐️ NEW</span> 打标签 🏷 
</v-click>
<div ml-6 v-click> - <span text-green>Done</span> 运营后台 标签管理 增加功能拓展</div>
<div ml-6 v-click> - <span text-green>Done</span> 前台Home 显示相关标签的推荐创作者的post列表</div>

<v-click>

2. <span text-red mr-1 >NEW</span> 桌面通知 及 桌面入口 web app
</v-click>

<div ml-6 v-click> - <span text-green>Done</span> 浏览器通知权限获取及开启</div>
<div ml-6 v-click> - <span text-green>Done</span> 添加说面图标及打开后是webapp 伪app 形式</div>
<div ml-6 v-click> - <span text-orange>In progress</span> 对接 <a href="https://firebase.google.com/docs/cloud-messaging/js/client?authuser=0" text-red>Google Firebase</a> 进行接受推送系统消息 (与超哥对接)</div>

<v-click>

3. <span text-blue mr-1 >Style</span> 黑白主题切换
</v-click>
<div ml-6 v-click> 📢 TG 有自己的 theme, 需要测试需不需要特殊处理</div>
<div ml-6 v-click> 📢 基于 10-15号上线后的代码版本开始修改</div>

<v-click>

else 处理日常群里的问题
</v-click>

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
