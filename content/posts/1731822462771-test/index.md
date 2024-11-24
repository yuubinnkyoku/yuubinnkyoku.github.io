---
title: "test"
date: 2024-11-17
draft: false
description: "test"
tags: ["test"]
---

# アラート

{{< alert icon="twitter" iconColor="#4a99e9" textColor="#b2b2b2" >}}
Twitterで[フォロー](https://twitter.com/intent/follow?screen_name=yuubinnkyoku_mk)してね！
{{< /alert >}}

<br>

# 記事へのリンク

{{< article link="/posts/1731748107742-githubprofile/" >}}

<br>

# バッジ

{{< badge >}}
New article!
{{< /badge >}}

<br>

# ボタン

{{< button href="#button" target="_self" >}}
ボタンを押す
{{< /button >}}

<br>
<br>

# スライドショー

{{< carousel images="gallery/*" >}}

<br>

# 棒グラフ

{{< chart >}}
type: 'bar',
data: {
  labels: ['yuubinnkyoku', 'kusaann', 'moa', 'kf25' , 'sawasawa' , 'sawayan'],
  datasets: [{
    label: '登録者数',
    data: [144, 187000, 54800, 16200, 9370, 1960000],
  }]
}
{{< /chart >}}

<br>

# 折れ線グラフ

{{< chart >}}
type: 'line',
data: {
  labels: ['1月', '2月', '3月', '4月', '5月', '6月', '7月'],
  datasets: [{
    label: '初めてのデータセット',
    data: [65, 59, 80, 81, 56, 55, 40],
    tension: 0.2
  }]
}
{{< /chart >}}
<br>

# 円グラフ

{{< chart >}}
type: 'doughnut',
data: {
  labels: ['赤色', '青色', '黄色'],
  datasets: [{
    label: '初めてのデータセット',
    data: [300, 50, 100],
    backgroundColor: [
      'rgba(255, 99, 132, 0.7)',
      'rgba(54, 162, 235, 0.7)',
      'rgba(255, 205, 86, 0.7)'
    ],
    borderWidth: 0,
    hoverOffset: 4
  }]
}
{{< /chart >}}
<br>

# Code Import

{{< codeimporter url="https://raw.githubusercontent.com/tsukuba-denden/tentative/refs/heads/main/index.html" type="txt" startLine="2" endLine="6" >}}

# Figure(画像挿入)

![Abstract purple artwork](abstract.jpg "Photo by [Jr Korpa](https://unsplash.com/@jrkorpa) on [Unsplash](https://unsplash.com/)")

# ギャラリー

{{< gallery >}}
  <img src="gallery/denden.png" class="grid-w33" />
  <img src="gallery/dendendirect.png" class="grid-w33" />
  <img src="gallery/ライブ.png" class="grid-w33" />
{{< /gallery >}}