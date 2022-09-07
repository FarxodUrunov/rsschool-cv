![My photo](/photo.jpg)
 **Urunov Farxod**
=================

________________________

## **Contact information**
### **Tel:** +998 (93) 995-94-98
### **Email:** urunovfar@gmail.com
________________________

## **About Me**
#### *Extremely motivated all the time develop your skills and grow professionally. Confident in your ability offer interesting ideas for campaigns*

___

## **Skills**

#### HTML, Tailwind, React, Vue 3 js, CSS, Bootstrap, Next.js, Git, SASS, JavaScript, Redux, GitHub, VS Code
___

## **Portfolio**
## [GitHub link](https://github.com/FarxodUrunov/intex-admin)

___

## **Code examples** *Codewars*

### *5 kyu Valid Parentheses*
```JavaScript
function validParentheses(parens) {
  let a = '(';
  let b = ')';
  let obj = { ')': '(' };
  let arr = [];
  if (parens === '') return true;

  for (let i = 0; i < parens.length; i++){
    if (a.includes(parens[i])) {
      arr.push(parens[i])
    } else if (b.includes(parens[i])) {
      if (arr.length === 0) return false;
      if (arr[arr.length - 1] === obj[parens[i]]) {
        arr.pop();
      } else {
        return false
      }
    }
  }
  return arr.length === 0;
}
```
___

## **Experience**

### *May 2022 - present* - *Support IT Solution Ташкент, supportsolution.uz/*

___

## **Education**

#### *Tashkent University information technologies*
#### *PDP Academy Bootcamp - Frontend developer*
#### *Udemy - JavaScript + React - from scratch to result*

__________