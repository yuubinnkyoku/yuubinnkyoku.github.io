---
title: "努力のあしあと"
date: 2025-03-08
draft: true
description: "自分のテスト結果を晒す場所"
tags: ["Profile","Exam"]
---

## 中学受験時代
### 早稲アカ系
### 四谷大塚系
### SAPIX系

{{< chart >}}
type: 'bar',
data: {
  labels: ['トマト', 'ブルーベリー', 'バナナ', 'ライム', 'オレンジ'],
  datasets: [{
    label: '# 投票数',
    data: [12, 19, 3, 5, 3],
  }]
}
{{< /chart >}}

{{< chart >}}
  type: 'radar',
  data: {
    labels: ['Cost', 'Delivery', 'Quality', 'Process', 'Customer'],
    datasets: [{
      label: 'Product',
      data: [30, 40, 30, 40, 50],
      // データライン
      borderColor: 'green',
      borderWidth: 2,
    }],
  },
  options: {
    scales: {
      r: {
        // 最小値・最大値
        min: 0,
        max: 60,
        // 背景色
        backgroundColor: 'lightyellow',
        // グリッドライン
        grid: {
          color: 'lightseagreen',
        },
        // アングルライン
        angleLines: {
          color: 'brown',
        },
        // ポイントラベル
        pointLabels: {
          color: 'blue',
          backdropColor: '#ddf',
          backdropPadding: 5,
          padding: 20,
        },
      },
    },
  },
{{< /chart >}}


### 中学時代
### 定期考査
### 河野塾系