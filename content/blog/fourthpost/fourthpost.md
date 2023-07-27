---
title: Pseudocode.
description: example of Pseudocode and Javascript written from it.
date: 2023-03-25
tags: Pseudocode
---
Hi, here is an example of some Pseudocode (very difficult to spell!) I wrote for a bootcamp task, followed by the Javascript written from it:

Define
recipe
<br>
1st Object elements  <br>recipe name:
      <br> servings:
      <br> ingredients:
      <br> directions:
<br>2nd Object elements recipe name:
     <br>  servings:
     <br>  ingredients:
     <br>  directions:
<br>3rd Object elements  recipe name:
     <br>servings:
     <br>ingredients:
     <br>directions:
<br>Call ingredients from object 2
<br>Call directions from object 1

## Javascript

```js
 const recipe = {
    recipeTitle1: 'Lasagne',
   recipeTitle2: 'Spaghetti vongole',
   recipeTitle3: 'Bean Casserole',
    servings1:8,
   servings2:2,
   servings3:10,
    ingredients1:['Mince', 'Tomatos', 'onions', 'garlic', 'Carrots', 'celery', 'herbs', 'seasoning'],
   ingredients2:['Vongole', 'Spaghetti', 'fresh tomatos', 'Garlic', 'seasoning'],
   ingredients3:['onions', 'tinned tomatos', 'courgettes', 'mushrooms', 'red pepper', 'cannalini, berlotti beans', 'peas', 'sweatcorn'],
    directions1: ['Brown mince', 'add onions, garlic, carrots and celery', 'add tomatos and seasoning', 'simmer for hours'],
   directions2: ['Put Spaghetti on to boil', 'skin the fresh tomatos after blanching', 'heat oil in pan', 'add garlic and tomatos', 'add clams and seasoning', 'add pasta when cooked'],
   directions3: ['fry the onion, courgettes, mushrooms and red pepper', 'add beans and tinned tomatos', 'add any seasoning you like', 'simmer for 2 hours', 'add peas and sweetcorn', 'serve with bulgar wheat']
  } 
 
for (const ingredient of recipe.ingredients2){
    console.log(ingredient);
  }
  for(const direction of recipe.directions1){
    console.log(direction);
  }
// function letsCook(recipe){
//   console.log(`I'm hungry, lets cook ${recipe.recipeTitle3}`);
// } 
//letsCook(recipe);
for (const [key,value] of Object.entries (recipe))
  {
    console.log(`${value}`);
  }
```

## Console Output

Go to the below code pen and have a try!

<a href="https://codepen.io/AnnaBiondo/pen/KKxjVMj">Recepies</a>

