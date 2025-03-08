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

#### サピックスオープン開成
##### 第2回
{{< chart >}}
type: 'radar',
data: {
    labels: [
        '算数',
        '国語',
        '理科',
        '社会',
    ],
    datasets: [{
        label: 'Average(%)',
        data: [ 39.8/85*100, 37.1/85*100, 43.5/70*100, 39.6/70*100
        ],
    }, {
        label: 'My Score(%)',
        data: [ 74/85*100, 44/85*100, 50/70*100, 34/70*100
        ],
    }
    ]
},
options: {
    scales: {
        r: {
            beginAtZero: true,
            ticks: {
                stepSize: 10
            }
        }
    },
    plugins: {
        colors: {
            forceOverride: true
        },
    }
}
{{< /chart >}}



### 中学時代
### 定期考査
### 河野塾系