# Chap3 数组
## 3.1 概述
## 3.2 一维数组
### 3.2.1 声明方式
```
int a[] = new int[3]; 
int[] a = {3,9,8};
```
## 3.3 二维数组
## 3.4 算法（二分，排序）
## 3.5 Arrays工具类
```java
import java.util.Arrays;
boolean equals(int[] a,int[] b)// 判断两个数组是否相等。
String toString(int[] a) //输出数组信息。
void sort(int[] a) //对数组进行排序。
int binarySearch(int[] a,int key) //对排序后的数组进行二分法检索指定的值。
