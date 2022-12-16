---
# try also 'default' to start simple
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
backgroundColor: #b89a82
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
layout: center
---

<h1 class="flex pb-4"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-40"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-40"></h1>


## 衝撃のイナズマZ / IMPACT-Z


---
layout: center
class: 'text-center'
preload: false
---

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

# メンバー紹介

  <img width="200" src="/images/undraw_pic_profile_re_7g2h.svg">
</div>

---

# メンバー紹介

- 衝撃のイナズマZは**長野高専**の***超人ハイスぺエンジニア集団！！***
- 全員**寮生**


<div
class="flex mt-8"
style="justify-content: center;"
v-motion
v-if="$slidev.nav.currentPage === 3"
>

<div
  v-motion
  :initial="{ y: 80 }"
  :enter="{ y: 0, opacity: 1, transition: { delay: 50 }}"
  class="text-center pro-item opacity-0"
>

  <img class="rounded-full" src="https://github.com/zoronosuke.png" width=80 style="">

  ## zoroの助
  ### @zoronosuke
  <div class="h-4" />

  #### 顔認識担当
  <div class="h-4" />

  #### **リーダー**

</div>

<div
  v-motion
  :initial="{ y: 80, opacity: 0 }"
  :enter="{ y: 0, opacity: 1, transition: { delay: 150 }}"
  class="text-center pro-item opacity-0"
>

  <img class="rounded-full" src="https://github.com/jumpeace.png" width=80 style="">

  ## Jumpeace
  ### @Jumpeace
  <div class="h-4" />
  
  #### フロントエンド担当

</div>

<div
  v-motion
  :initial="{ y: 80, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 ,transition: { delay: 250 }}"
  class="text-center pro-item"
>

  <img src="https://github.com/bonychops.png" width=80 style="">

  ## Bony_Chops
  ### @BonyChops
  <div class="h-4" />

  #### バックエンド担当

  <div class="h-4" />
  
  ### スライドも担当

</div>

<div
  v-motion
  :initial="{ y: 80, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 ,transition: { delay: 450 }}"
  class="text-center pro-item"
>

  <img class="rounded-full" src="https://github.com/Token-05.png" width=80 style="">

  ## Take
  ### @Token-05
  <div class="h-4" />

  #### 顔方向推定担当

</div>

</div>

<style>
img {
  margin-left:auto; margin-right: auto;
}
.pro-item{
  margin-left: 10px;
  margin-right: 10px;
}
</style>

---
layout: center
class: 'text-center'
preload: false

---

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<h1 class="flex mb-5">What's <span class="flex mx-2"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-10"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-10"></span>？</h1>


</div>


---
layout: center
class: 'text-center'
preload: false

---

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">


# A. オンライン点呼サービス

</div>

---
layout: center
class: text-center
---

## 寮点呼とは？
# A. 学生の在寮を確認する

---
src: ./pages/cm.md

---

---
layout: center
class: 'text-center'
preload: false
---

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

# 解決すべき課題

</div>
---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

# 不正されないこと
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #500000 10%, #e00000 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
preload: false
---

## 解決すべき問題
# 不正されないこと

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

- 今まで顔合わせでやってきた点呼
- オンラインにすれば当然**不正が懸念される**

<!--
今まで顔合わせでやってきた点呼ですので，当然オンラインにすれば，その特性上不正を行われることを懸念する必要があります．
-->

</div>

<img class="absolute right-10 top-30 w-100" src="/images/undraw_problem_solving_re_4gq3.svg">

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #500000 10%, #e00000 30%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>
---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

# どんな問題があるか？
</div>

---

## 解決すべき問題
# どんな問題があるか？

<v-clicks>

- **寮にいるのか？**
- **本人が**おこなっているのか？
- そのオペレーションは**人間によるもの**か？

</v-clicks>


<img class="absolute right-10 top-30 w-100" src="/images/undraw_questions_re_1fy7.svg">

<!--
これらの問題を解決し，実際に点呼をオンラインでできるようにしたサービス，それが
-->

---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<h1 class="flex"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-40"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-40"></h1>
</div>

---
preload: false
---

<h1 class="flex pb-4"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-15"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-15"></h1>

<img class="absolute right-10 top-10 w-80" src="/images/top.png">

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

- 点呼を**オンライン**で行えるサービス
- **PC/スマートフォン**のブラウザから点呼
- **不正対策**
  - IPチェック
  - 顔認証
  - 3チャレンジ

</div>

---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

## 不正対策1
# IPチェック
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 40%, #00C000 60%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
preload: false
---
## 不正対策1
# IPチェック

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

- 寮には寮生が使用できるネットワークがある(通称: **寮ネット**)
- 寮ネットは**同一グローバルIP**
- **寮ネットに接続しているか否か**を判定できる
</div>

<div v-motion v-click
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

## **→寮にいるかを判定できる！**

</div>
<img class="absolute right-10 top-35 w-80" src="/images/undraw_security_on_re_e491(1).svg">

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 10%, #00C000 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

## 不正対策2
# 顔認証
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 40%, #00C000 60%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
preload: false
---

## 不正対策2
# 顔認証

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

顔を登録し，顔の認証を行う
</div>


<video class="absolute right-10 top-5 h-120" autoplay loop>
  <source src="/videos/Screenrecorder-2022-12-14-21-36-11-235(1).mp4" >
</video>


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 10%, #00C000 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

## 不正対策3
# 3チャレンジ
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 40%, #00C000 60%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
preload: false
---

## 不正対策3
# 3チャレンジ

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

ランダム方向をユーザーに指示することで，**人間であることを証明**
 
</div>


<video class="absolute right-10 top-5 h-120" autoplay loop>
  <source src="/videos/Screenrecorder-2022-12-14-21-36-11-235.mp4" >
</video>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 10%, #00C000 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---


<!--

# 背景
なんで?

# 取り組むにあたって必要なこと(課題)

解決した->TENTEN

特徴(顔認証->3チャレンジ)

これなら！
(いままで->これからのTENTENの対比)

デモプレイ
(時間がアレば技術の内容)

残された課題



-->