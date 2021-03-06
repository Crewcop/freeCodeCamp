---
id: 598ee8b91b410510ae82efef
title: 可扩展的素发生器
challengeType: 5
videoUrl: ''
---

# --description--

<p>按顺序编写素数生成器，它将自动调整以适应任何合理高素数的生成。 </p>发电机应能：显示前<b>N个</b>黄金numbers.Show在range.Show的素数的素数在range.Show数<b><sup>第</sup> n <sup>个</sup></b>素数。 <p>该函数应该有两个参数。第一个将接收<b>n</b>或作为数组的范围。第二个将接收一个布尔值，它指定函数是否将素数作为数组或单个数字（范围中的素数或第<b>n <sup>个</sup></b>素数）返回。根据参数，函数应该返回一个数组。 </p>

# --hints--

`primeGenerator`是一个函数。

```js
assert(typeof primeGenerator === 'function');
```

`primeGenerator`是一个函数。

```js
assert.deepEqual(primeGenerator(20, true), [
  2,
  3,
  5,
  7,
  11,
  13,
  17,
  19,
  23,
  29,
  31,
  37,
  41,
  43,
  47,
  53,
  59,
  61,
  67,
  71
]);
```

`primeGenerator`是一个函数。

```js
assert.deepEqual(primeGenerator([100, 150], true), [
  101,
  103,
  107,
  109,
  113,
  127,
  131,
  137,
  139,
  149
]);
```

`primeGenerator`是一个函数。

```js
assert.equal(primeGenerator([7700, 8000], false), 30);
```

`primeGenerator`是一个函数。

```js
assert.equal(primeGenerator(10000, false), 104729);
```

# --solutions--

