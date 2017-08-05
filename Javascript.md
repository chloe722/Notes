# Total cost of shoppingList exercise

Using `map()` (convert item array to price array) and `reduce()` (for sum caculation):

```javascript
var shoppingList=function(List){
  return List.map((item) => item['price']).reduce((a,b) => a + b);
};

```
Using `for()` loop:

```javascript
var shoppingList=function(List){
  var total = 0;
  for (var i=0; i<List.length; i++){
    total += List[i]['price'];
  }
  return total;
};
```