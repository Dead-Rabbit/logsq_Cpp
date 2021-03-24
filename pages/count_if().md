---
title: count_if()
---

## 返回符合一定条件的元素个数。compare()函数是自定义的，返回值是true就是表示符合要求
``` c++
#include <iostream>
#include <cstdio>
#include <algorithm>
#include <vector>
using namespace std;
bool comp(int num)
{
    return num % 2;
}
int main()
{
    vector <int> V;
    for(int i = 1; i <= 10; i++)
        V.push_back(i);
    cout << count_if(V.begin(), V.end(), comp) << endl;
    return 0;
}
// 输出：5
```
tor <int> V;
    for(int i = 1; i <= 10; i++)
        V.push_back(i);
    cout << count_if(V.begin(), V.end(), comp) << endl;
    return 0;
}
```
 vector <int> V;
    for(int i = 1; i <= 10; i++)
        V.push_back(i);
    cout<<count_if(V.begin(), V.end(), comp)<<endl;
    return 0;
}
```
vector <int> V;
    for(int i = 1; i <= 10; i++)
        V.push_back(i);
    cout<<count_if(V.begin(), V.end(), comp)<<endl;
    return 0;
}
````
  vector <int> V;
    for(int i = 1; i <= 10; i++)
        V.push_back(i);
    cout<<count_if(V.begin(), V.end(), comp)<<endl;
    return 0;
}
``
##
