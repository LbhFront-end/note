# Number
## 原因
计算机的底层实现就无法完全精确表示一个无限循环的数，转换成二进制出现计算误差。
比如在 JavaScript 中计算 0.1 + 0.2
```
// 百度进制转换工具
0.1 -> 0.0001100110011001...
0.2 -> 0.0011001100110011...
```

## 判断 -1
!!~ -1 => false


## 参考资料
- [JavaScript 精度丢失问题](https://segmentfault.com/a/1190000007649282)