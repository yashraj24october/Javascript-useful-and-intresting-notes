In Javascript, we can store data about some thing as key:value pairs using Object.

Let's understand, when should we use Object in js:
-------------------------------------------------
1. Grouping Related Data
When we need to store data about something, like a user, product, or any specific entity, it's better to group related data together. 
Instead of using separate variables for each item, we can store all the data in an object or an array of objects.


2. Mapping Data with Custom Keys
If we need a dictionary-like structure to associate keys with values, objects are the way to go.
For example, to store contact numbers of some persons:
Eg: 
 const contactNumbers = {
  A: 9122334567,
  B: 7286351234,
  C: 2273367890,
};
console.log(contactNumbers.A);

Here, you can access any contact number using its key (like A, B, or C).

3.	Adding Methods for Data
-	With Object, we have option to add method too in object associated to data.
-	That make our code cleaner,encapsulated and efficient.
-	When we perform any method on data, we can add method in object itself.
Eg:
const product = {
  name: "Laptop",
  price: 75000,
  discount: 0.1,
  getDiscountedPrice: function () {
    return this.price - this.price * this.discount;
  },
};
console.log(product.getDiscountedPrice()); 

4. We can group related methods in an object
Eg: const calculator = {
  add: (a, b) => a + b,
  subtract: (a, b) => a - b,
  multiply: (a, b) => a * b,
  divide: (a, b) => (b !== 0 ? a / b : "Cannot divide by zero"),
};
console.log(calculator.add(10, 5));

5. Getting total count of each items in array
- In Case, when we have an array and we need to access total occurence of each item of array, we can use object for making this task more easier.
Eg: const items = ["apple", "banana", "apple", "orange", "banana", "apple"]; 
    const count = {};
    items.forEach(item => { count[item] = (count[item] || 0) + 1; }); 
console.log(count); //It will console log total occurence of each item of array as key value pair in object
