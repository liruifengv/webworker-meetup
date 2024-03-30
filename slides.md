---
theme: seriph
title: 我的开源之旅 & 开源趣事
info: 一个开源爱好者的分享
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
colorSchema: dark
---

# 我的开源之旅 & 开源趣事

liruifengv

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/liruifengv" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
transition: fade-out
---

# Who is liruifengv

- 📝 **前端开发者** - 聚焦于 web 开发，后端 junior 水平
- 🎨 **Astro Maintainer** - 翻译和维护 Astro 中文文档
- 🧑‍💻 **开源爱好者** - 爱好开源，终极目标是能全职开源
- 🤹 **bloger** - 在自己的博客写点技术文章
- 🎥 **想做数字游民**
<br>
<br>


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---
---

# 开源之旅

<div v-click>

2019 年 7月 在 GitHub 提交了我的第一个 PR。

https://github.com/geoman-io/leaflet-geoman/pull/466
</div>

<div v-click>
给 vue-cli 提交了一个 PR。

https://github.com/vuejs/vue-cli/pull/4347
</div>

<div v-click>
给 Deno 贡献 PR。

https://github.com/denoland/deno/pulls/liruifengv
</div>

---
preload: false
---

## 开始 Astro 的贡献

<div class="w-40 relative mt-6">
  <div class="relative w-20 h-20">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="/astro-icon.png"
      alt=""
    />
  </div>

  <div
    class="text-5xl absolute top-10 text-purple left-40 -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Astro
  </div>
</div>

<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div class="flex gap-10 mt-10">
<div v-click >
2022 年 11 月提交了 Astro 的第一个 PR。

https://github.com/withastro/astro/pull/5401
</div>


<div v-click>
2023 年 7 月和 WebWorker 结缘

<img width="200px" height="500px" src="/webworker.jpg">

</div>
</div>

---

<div class="grid grid-cols-4 gap-5 pt-4 -mb-6">

<img src="https://bucket.liruifengv.com/astro-awards/x1.jpg">
<img src="https://bucket.liruifengv.com/astro-awards/x2.jpg">
<img src="https://bucket.liruifengv.com/astro-awards/winner.png">
<img src="https://bucket.liruifengv.com/join-astro/invite.jpg">
</div>

---

# 开源趣事

<img width="500" src="/pr-1.png">
<img width="500" src="/page.png">

---

# 开源趣事
<div class="grid grid-cols-2 gap-5 pt-4 -mb-6">

<img v-click width="300" src="/pair-1.png">
<img v-click width="300" src="/pair-2.webp">
<img v-click width="300" src="/pair-3.png">
<img v-click width="300" src="/pair-4.png">
</div>

---

# 开源趣事

<img src="/first-contributor.png">
<img width="500" src="/cabbage.png">

---

# 新手如何参与开源
### 如何寻找可以贡献的开源项目
- 从 fix typo 开始
- 贡献自己开发中用到的开源项目
- 新兴的开源项目
- 中文文档翻译

<br>

### 提交 PR 的注意事项
- 第一步要阅读你目标项目的贡献指南。
- 代码风格校验。
- 单元测试。
- 约定式提交。
- PR 的描述清楚。
- GitHub CI。


---
class: text-center
layout: center
---

# Thank you!