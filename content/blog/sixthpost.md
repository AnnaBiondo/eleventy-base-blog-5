---
title: Week 6.
description: introduction to Javascript
date: 2023-03-09
tags:
  - Intro JS
---
First encounter with Javascript and build my first program calculating a bill with a tip added.

var preTiptotal = 45;
var tippercentage = 15;
var tiptotal = (15 / 100) * preTiptotal;
alert (tippercentage + "% of " + preTiptotal + " is " + tiptotal);
var totalbill = tiptotal + preTiptotal;
console.log(totalbill);
console.log('Your bill of $ {value1}, including tip is ${value2}, tip added was ${value3}, you can add an additional ${value3}');
var value1 = "£45.00";
var value2 = "£51.75";
var value3 = "15%";
console.log(`Your bill of ${value1}, is, ${value2}, including a 
${value3} tip`);

and the output in the console was;

"Your bill of £45.00, is, £51.75, including a 
15% tip"

## Other News

<a href="/blog/firstpost/">Week 4</a>
<a href="/blog/thirdpost/">Week 3</a>