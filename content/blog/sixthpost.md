---
title: Week 6.
description: introduction to Javascript
date: 2023-03-09
tags:
  - Intro JS
---
First encounter with Javascript and build my first program calculating a bill with a tip added.

## Code


```js
var preTipTotal = 45;
var tipPercentage = 15;
var tipTotal = (15 / 100) * preTipTotal;
//alert (tippercentage + "% of " + preTiptotal + " is " + tiptotal);
/*stopped the alert pop up*/
var totalBill = tipTotal + preTipTotal;
console.log(totalBill);
var value1 = "£45.00";
var value2 = "£51.75";
console.log(`Your bill of £${preTipTotal}.00, is ${value2}, including a 
${tipPercentage} % tip`);
```
## Console Output;

```js
Console

51.75
"Your bill of £45.00, is £51.75, including a 
15 % tip"
```

## Other News

<a href="/blog/firstpost/">Week 4</a>
<a href="/blog/thirdpost/">Week 3</a>