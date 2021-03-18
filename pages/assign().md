---
title: assign()
---

## STL中不同容器之间是不能直接赋值的，assign（）可以实现不同容器但相容的类型赋值
## `list<string> names;
vector<const char*> oldstyle = { "I","love","you" };
//names = oldstyle;错误！不同的类型不能执行"="操作
names.assign(oldstyle.cbegin(), oldstyle.cend());
list<string>::iterator it;
for (auto it = names.begin(); names.begin() != names.end(); it++)
        cout << *it << " ";`
