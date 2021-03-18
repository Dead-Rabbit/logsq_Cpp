---
title: at()
---

## array::at()是C++ STL中的内置函数，该函数返回对给定数组中位置i处存在的元素的引用
## 该方法会自动检测n在该array中是否是一个有效的值，当n大于或者等于它的size的时候，将会抛出out_of_range异常，这和成员方法operato[]是一个对比，因为operator[]不会检测n的范围
