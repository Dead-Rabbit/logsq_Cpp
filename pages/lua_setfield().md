---
title: lua_setfield()
---

## 原型：void lua\_setfield (lua\_State \*L, int index, const char \*k);
## 解释：这个函数将把这个值弹出堆栈。 跟在 Lua 中一样，这个函数可能触发一个 "newindex" 事件的元方法。