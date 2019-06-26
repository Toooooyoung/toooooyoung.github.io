---
title: "常用排序/查找算法时间复杂度"
date: 2019-06-27T04:41:38+08:00
tags:
categories:
draft: true
---
# 排序
## 插入排序
| 排序方法 | 平均 | 最坏 | 最好 | 空间复杂度 | 稳定 |
| --- | --- | --- | --- | --- | --- |
| 直接插入排序 | N | N^2 | N | 1 | T |
| 希尔排序 | NlogN | NlogN | * | 1 | F |
| 二分查找排序 | N | N^2 | N | 1 | T |

## 选择排序
| 排序方法 | 平均 | 最坏 | 最好 | 空间复杂度 | 稳定 |
| --- | --- | --- | --- | --- | --- |
| 直接选择排序 | N^2 | N^2 | N^2 | 1 | T |
| 堆排序 | NlogN | NlogN | NlogN | 1 | T |


## 交换排序
| 排序方法 | 平均 | 最坏 | 最好 | 空间复杂度 | 稳定 |
| --- | --- | --- | --- | --- | --- |
| 冒泡排序 | N^2 | N^2 | N | 1 | T |
| 快速排序 | NlogN | N^2 | NlogN | NlogN | F |

## 其他
| 排序方法 | 平均 | 最坏 | 最好 | 空间复杂度 | 稳定 |
| --- | --- | --- | --- | --- | --- |
| 归并排序 | NlogN | NlogN | NlogN | N | T |
| 基数排序 | d(n+r) | d(n+r) | d(n+r) | (n+r) | T |

# 查找
| 排序方法 | 复杂度 |
| --- | --- |
| 二分查找 | logN |
| BST | logN |