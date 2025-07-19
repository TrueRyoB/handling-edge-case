```cpp
typedef construct {
  int b, t, r;
}btr;

auto custom = [&](int x, int y) {
  return x.b <= y.b;
};
sort(v.begin(), v.end(), custom);
```
二度とこれを使うのは、やめよう。

```cpp
#define btr tuple<int, int, int>

sort(v.begin(), v.end());
```
自然が、一番。
