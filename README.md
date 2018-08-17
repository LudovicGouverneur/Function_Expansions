# Function_Expansions




Here are the function to study : 
```javascript
// // --- 1
// let arg = 0;
// function nyeem(param) {
//   var result = param;
//   return result;
// };
// let ret_val = nyeem(arg);

// --- 2
let arg = {};
function nyeem(param) {
  let result = param;
  result.p = "p";
  return result;
};
let ret_val = nyeem(arg);

// // --- 3
// let arg = 0;
// let nyeem = function(param) {
//   var result = param;
//   return result;
// };
// let ret_val = nyeem(arg);

// // --- 4
// let arg = 0;
// let meeyn = nyeem;
// function nyeem(param) {
//   var result = param;
//   return result;
// };
// let ret_val = meeyn(arg);

// // calculator for celine
// function add(a, b) {
//   return a + b;
// };
// function higher_order_calc(operation, a, b) {
//   return operation(a, b);
// }; 
// let num_1 = 1;
// let num_2 = 2;
// let sum = higher_order_calc(add, num_1, num_2);

// ---- trace-blocking functions ----
// function call_expression(a, b, c) {
// 	let result;
// 	result = Number(String(a).replace(b, c));
// 	return result;
// };
// --- trace blocked
// let args = {
//   a: 0,
//   b: 1, 
//   c: 2
// };
// let ret_val;
// call_expression: {
//   let result;
//   {
//     const step_1 = String(args.a);
//     const step_2 = step_1.replace(args.a, args.b);
//     const step_3 = Number(step_2);
//     result = step_3;
//   };
//   ret_val = result;
//   break call_expression;
// };
// labeled blocks:
//  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/label#Using_a_labeled_block_with_break
```



