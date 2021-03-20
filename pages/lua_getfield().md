---
title: lua_getfield()
---

## lua_getfield##原型：void lua_getfield (lua_State *L, int index, const char *k);
解释：把 t[k] 值压入堆栈， 这里的 t 是指有效索引 index 指向的值。 在 Lua 中，这个函数可能触发对应 "index" 事件的元方法
## 原型：void lua_getfield (lua_State *L, int index, const char *k)
## 解释：把 t[k] 值压入堆栈， 这里的 t 是指有效索引 index 指向的值。 在 Lua 中，这个函数可能触发对应 "index" 事件的元方法
