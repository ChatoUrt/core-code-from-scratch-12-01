# core-code-from-scratch-12-01

## ---Convert strings to numbers---

* [Test](https://www.codewars.com/kata/544675c6f971f7399a000e79/train/javascript)

Solution / /
``` javascript
const stringToNumber = function(srt){
  return Number(str);
}
```

---
## ---Convert number to reversed array of digits---

* [Test](https://www.codewars.com/kata/5583090cbe83f4fd8c000051/train/javascript)

``` javascript
function digitize(n){
  return Array.from(String(n), Number).reverse();
}
```

---

---
## ---Truthy && Falsy---
* [true and false values](https://developer.mozilla.org/en-US/docs/Glossary/Truthy)
* [Test](https://www.codewars.com/kata/595c2988d946a13298000157/train/javascript)

Solution / /

``` javascript
const truthy = [true, 1, {}, "false", 5];
const falsy = [null, undefined, 0, false, ""];
```

---
## ---Training basic data types :---

* [Test](https://www.codewars.com/kata/571effabb625ed9b0600107a/train/javascript)

Solution / /
``` javascript
function getLength(arr){
  //return length of arr
  return arr.length;
}


function getFirst(arr){
  //return the first element of arr
  return arr[0];
}


function getLast(arr){
  //return the last element of arr
  return arr[arr.length - 1];
}


function pushElement(arr){
  var el = 1;
  arr.push(el);
  
  return arr;
}


function popElement(arr){
  //pop an element from arr
  arr.pop();
  return arr;
}
```

---
## ---Knowledge Base---

1. [Type Conversions](https://developer.mozilla.org/en-US/docs/Glossary/Type_Conversion)
2. [JS type conversions](https://www.programiz.com/javascript/type-conversion)
3. [Number() | paserInt()?](https://thisthat.dev/number-constructor-vs-parse-int/)
