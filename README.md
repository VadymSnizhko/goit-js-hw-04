Second Home Work

audit task 1: console.log( isEnoughCapacity({ apples: 2, grapes: 3, carrots: 1
}, 8) ); // true

console.log( isEnoughCapacity({ apples: 4, grapes: 6, lime: 16 }, 12) ); //
false

console.log( isEnoughCapacity({ apples: 1, lime: 5, tomatoes: 3 }, 14) ); //
true

console.log( isEnoughCapacity({ apples: 18, potatoes: 5, oranges: 2 }, 7) ); //
false

audit task 2: console.log( calcAverageCalories([ { day: "monday", calories: 3010
}, { day: "tuesday", calories: 3200 }, { day: "wednesday", calories: 3120 }, {
day: "thursday", calories: 2900 }, { day: "friday", calories: 3450 }, { day:
"saturday", calories: 3280 }, { day: "sunday", calories: 3300 } ]) ); // 3180

console.log( calcAverageCalories([ { day: "monday", calories: 2040 }, { day:
"tuesday", calories: 2270 }, { day: "wednesday", calories: 2420 }, { day:
"thursday", calories: 1900 }, { day: "friday", calories: 2370 }, { day:
"saturday", calories: 2280 }, { day: "sunday", calories: 2610 } ]) ); // 2270

console.log( calcAverageCalories([]) ); // 0

audit task 3: console.log(filterArray([1, 2, 3, 4, 5], 3)); // [4, 5]
console.log(filterArray([1, 2, 3, 4, 5], 4)); // [5] console.log(filterArray([1,
2, 3, 4, 5], 5)); // [] console.log(filterArray([12, 24, 8, 41, 76], 38)); //
[41, 76] console.log(filterArray([12, 24, 8, 41, 76], 20)); // [24, 41, 76]
