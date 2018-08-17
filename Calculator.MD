# Calculator Expansion


## Snippet : 
```javascript
// calculator for celine
function add(a, b) {
   return a + b;
};
function higher_order_calc(operation, a, b) {
  return operation(a, b);
}; 
let num_1 = 1;
let num_2 = 2;
let sum = higher_order_calc(add, num_1, num_2)
```
