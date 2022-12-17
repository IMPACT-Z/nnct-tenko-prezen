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

<!-- 
それでは，これから「衝撃のイナズマZ」のTENTENについて発表を始めます．
-->

---
layout: center
class: 'text-center'
preload: false

---

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<h1 style="font-size: 88px;" class="flex items-center">What's <span class="flex mx-6"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-24"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-24"></span>？</h1>


</div>

<!--
まず，TENTENについてです．TENTENとは―
-->

---
layout: center
class: 'text-center'
preload: false

---

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">


<h1 style="font-size: 56px;">A. オンライン寮点呼サービス</h1>

</div>

<!--
オンライン寮点呼サービスです．
-->
---
preload: false
---

<h1 class="flex pb-4"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-15"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-15"></h1>

<img class="absolute right-10 top-10 w-55" src="https://cdn.discordapp.com/attachments/719199923782025257/1053478052446867516/tenko.png">

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<div style="font-size: 18px;">

- 寮点呼[^1]を**オンライン**で行えるサービス
- **PC/スマートフォン**のブラウザから点呼
- **不正対策**

  - IPチェック
  - 顔認証
  - 3チャレンジ
  
</div>

</div>

<div class="h-25" />

[^1]: [1]毎晩弊高専で行われる，学生の在寮を確認するプロセス

<!--
毎晩行われる寮点呼をオンラインで実施できるサービスで，PC/スマートフォンからアクセスできます．
-->


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

<h1 style="font-size: 64px;" class="flex items-center"><span class="flex mx-6"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-20"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-20"></span>の特徴</h1>

</div>

<!--
次に，TENTENのイチオシ機能を紹介します．それはずばり―
-->

---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<h1 style="font-size: 64px;">

不正対策

</h1>
</div>

<style>
h1 {
  color: #b00000;
  /* background-color: #2B90B6;
  background-image: linear-gradient(45deg, #500000 10%, #e00000 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent; */
}
</style>

<!--
不正対策です
-->
---
preload: false
---

<div style="font-size: 28px;" class="flex items-center"><span class="flex mx-2"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-8"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-8"></span>の特徴</div>

<h1 style="font-size: 40px; color: #b00000;" class="mt-6"> 不正対策</h1>

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<div class="h-2"></div>
<div style="font-size: 18px;">

- 今まで顔合わせでやってきた点呼
- オンラインにすれば当然**不正が懸念される**

</div>


</div>

<img class="absolute right-10 top-30 w-100" src="/images/undraw_problem_solving_re_4gq3.svg">

<style>
h1 {
  color: #b00000;
  /* background-color: #2B90B6;
  background-image: linear-gradient(45deg, #500000 10%, #e00000 30%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent; */
}
</style>

<!--
今まで顔合わせでやってきた点呼ですので，当然オンラインにすれば，その特性上不正を行われることを懸念する必要があります．
-->
---
preload: false
---

<div style="font-size: 28px;" class="flex items-center"><span class="flex mx-2"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-8"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-8"></span>の特徴</div>

<h1 style="font-size: 40px; color: #b00000;" class="mt-6"> どんな不正が想定されるか？</h1>

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<div class="h-2"></div>
<div style="font-size: 18px;">

- **寮にいるのか？**
- **本人が**おこなっているのか？
- そのオペレーションは**人間によるもの**か？

</div>

</div>


<img class="absolute right-10 top-30 w-100" src="/images/undraw_questions_re_1fy7.svg">

<!--
実際に想定される不正としましては，(読み上げ)といったものがあります．では―
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
<!--
TENTENがどうやってその不正を防いだのかを，これからご紹介します
-->
---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<div style="font-size: 36px;">
不正対策1
</div>
<div class="h-6"></div>
<h1 style="font-size: 64px;">
    IPチェック
</h1>
</div>

<style>
h1 {
  color: #007000;
  /* background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 40%, #00C000 60%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent; */
}
</style>

---
preload: false
---
<div style="font-size: 28px;">
    不正対策1
</div>
<div class="h-2"></div>
<h1 style="font-size: 44px;">
    IPチェック[^1]
</h1>
<div class="h-2"></div>

<div style="font-size: 18px;">
<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

- 寮には寮生が使用できるネットワークがある(通称: **寮ネット**)
- 寮ネットは**同一グローバルIP**
- **寮ネットに接続しているか否か**を判定できる
</div>
</div>

<div class="h-12" />

## **→寮にいるかを判定できる！**

<img class="absolute right-10 top-35 w-80" src="/images/undraw_security_on_re_e491(1).svg">

<style>
h1 {
  color: #007000;
  /* background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 10%, #00C000 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent; */
}
</style>

<div class="h-38"/>

[^1]: [1](展覧会で用いる)デモ版ではIPチェックが無効化されています

<!--
寮生が使えるネットワーク: 寮ネットでは，同じIPアドレスが割り振られているため，この性質を使って在寮を確認しています
-->

---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<div style="font-size: 36px;">
不正対策2
</div>
<div class="h-6"></div>
<h1 style="font-size: 64px;">
    顔認証
</h1>
</div>

<style>
h1 {
  color: #007000;
  /* background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 40%, #00C000 60%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent; */
}
</style>

---
preload: false
---

<div style="font-size: 28px;">
    不正対策2
</div>
<div class="h-2"></div>
<h1 style="font-size: 44px;">
    顔認証
</h1>
<div class="h-2"></div>

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<div style="font-size: 18px;">
顔を登録し，顔の認証を行う
</div>
</div>


<video class="absolute right-10 top-5 h-120" loop controls>
  <source src="/videos/Screenrecorder-2022-12-14-21-36-11-235(1).mp4" >
</video>


<style>
h1 {
  color: #007000;
  /* background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 10%, #00C000 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent; */
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
<div style="font-size: 36px;">
不正対策3
</div>
<div class="h-6"></div>
<h1 style="font-size: 64px;">
    3チャレンジ
</h1>
<div class="h-2"></div>
</div>

<style>
h1 {
  color: #007000;
  /* background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 40%, #00C000 60%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent; */
}
</style>

---
preload: false
---

<div style="font-size: 28px;">
    不正対策3
</div>
<div class="h-2"></div>
<h1 style="font-size: 44px;">
    3チャレンジ
</h1>
<div class="h-2"></div>

<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<div style="font-size: 18px;">

ランダム方向をユーザーに指示することで，**人間であることを証明**

</div>
 
</div>


<video class="absolute right-10 top-5 h-120" loop controls>
  <source src="/videos/Screenrecorder-2022-12-14-21-36-11-235.mp4" >
</video>

<style>
h1 {
  color: #007000;
  /* background-color: #2B90B6;
  background-image: linear-gradient(45deg, #005000 10%, #00C000 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent; */
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

<h1 style="font-size: 56px;" class="flex items-center">システム構成</h1>
</div>

---
preload: false
---

# システム構成

<img width="700" class="mx-auto" src="https://user-images.githubusercontent.com/52094083/205087008-723967ad-33a2-4bb3-bc06-cb6ec1571b1b.png">

---

# システム構成

<div class="flex mt-35">

<div class="w-1/2 text-center">

## 顔認証
# facenet-pytorch

</div>
<div class="w-1/2 text-center">

## 3チャレンジ
# dlib


</div>


</div>

---
layout: center
class: 'text-center'
preload: false
---


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<h1 style="font-size: 56px;" class="flex items-center">ユーザーからの評価</h1>
</div>

---
preload: false
---

<div style="font-size: 28px;">

## ユーザーからの評価

</div>
<div class="h-2"></div>
<div style="font-size: 36px;">

# 良い評価[^1]

</div>


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<div style="font-size: 18px;">

- **うおおすげえ**
- 明るいと割とうまくいく
- **声がかわいい**
- 次の指示で振動するのがわかりやすい
- **使う分には問題なさそう**

</div>

</div>

<img class="absolute right-10 top-35 h-60" src="/images/undraw_order_confirmed_re_g0if.svg">

<div class="h-12" />

<div>

[^1]: [1]寮生4人に対してクローズドベータテストを実施

</div>

---
preload: false
---


<div style="font-size: 28px;">

## ユーザーからの評価

</div>
<div class="h-2"></div>
<div style="font-size: 36px;">

# 改善点[^1]

</div>


<div v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">

<div style="font-size: 18px;">

- 方向を指示するイラストがあるとわかりやすい
- **iPhoneでも動くようにしてほしい**
- **声がかぶるのが良くない**
- なにか点呼で問題があったときの報告フォームみたいなのがほしい
- **寮ネットが使えないひとはどうするのか**

</div>

</div>

<img class="absolute right-10 top-35 h-60" src="/images/undraw_access_denied_re_awnf.svg">

<div class="h-12" />


[^1]: [1]寮生4人に対してクローズドベータテストを実施
---

# 今後の展望

<div style="font-size: 18px;">

- ユーザーから得た**改善案をシステムに反映**
- 不正対策案の再考案 / 実装
- 認証フローの精度向上
- 実際に**点呼**として組み込んで頂く

</div>


<img class="absolute right-10 top-35 h-60" src="/images/undraw_flowers_vx06.svg">

---
layout: center
class: text-center
---

<h1 class="flex pb-4"><img src="https://cdn.discordapp.com/attachments/1038262445560565824/1050994403256303696/tenten_icon.png" class="h-40"><img src="https://media.discordapp.net/attachments/1038262445560565824/1050994403633807360/tenten_logo.png?width=720&height=268" class="h-40"></h1>


## 衝撃のイナズマZ / IMPACT-Z

ご清聴ありがとうございました

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