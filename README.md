Second Home Work

audit task 1: console.log(
  isEnoughCapacity({ apples: 2, grapes: 3, carrots: 1 }, 8)
); // true

console.log(
  isEnoughCapacity({ apples: 4, grapes: 6, lime: 16 }, 12)
); // false

console.log(
  isEnoughCapacity({ apples: 1, lime: 5, tomatoes: 3 }, 14)
); // true

console.log(
  isEnoughCapacity({ apples: 18, potatoes: 5, oranges: 2 }, 7)
); // false

audit task 2: console.log(makeArray(["Mango", "Poly"], ["Ajax", "Chelsea"], 3));
// ["Mango", "Poly", "Ajax"] console.log(makeArray(["Mango", "Poly", "Houston"],
["Ajax", "Chelsea"], 4)); // ["Mango", "Poly", "Houston", "Ajax"]
console.log(makeArray(["Mango"], ["Ajax", "Chelsea", "Poly", "Houston"], 3)); //
["Mango", "Ajax", "Chelsea"] console.log(makeArray(["Earth", "Jupiter"],
["Neptune", "Uranus"], 2)); // ["Earth", "Jupiter"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 4)); //
["Earth", "Jupiter", "Neptune", "Uranus"] console.log(makeArray(["Earth",
"Jupiter"], ["Neptune", "Uranus", "Venus"], 0)); // []

audit task 3: console.log(filterArray([1, 2, 3, 4, 5], 3)); // [4, 5]
console.log(filterArray([1, 2, 3, 4, 5], 4)); // [5] console.log(filterArray([1,
2, 3, 4, 5], 5)); // [] console.log(filterArray([12, 24, 8, 41, 76], 38)); //
[41, 76] console.log(filterArray([12, 24, 8, 41, 76], 20)); // [24, 41, 76]
