# js-tasks

Transform from a decimal number system to binary one
```js
const decimalToBinary = (decimalNumber) => {
// Your code
}

console.assert(decimalToBinary(5) === "101");
console.assert(decimalToBinary(798) === "1100011110");
```
[Soluction](decimalToBinary.md)

---

Transform from a binary number system to decimal one
```js
const binaryToDecimal = (binaryNumber) => {
// Your code
}

console.assert(binaryToDecimal("101") === 5);
console.assert(binaryToDecimal("1100011110") === 798);
```
[Soluction](binaryToDecimal.md)

---

Summarize two binary numbers
```js
const summarizeBinaries = (x, y) => {
// Your code
}

console.assert(
  summarizeBinaries("101", "11101") === "100010"
);
console.assert(
  summarizeBinaries("1100011110", "10101010101") === "100001110011"
);
```
[Soluction](summarizeBinaries.md)

---

Substruct two binary numbers
```js
const substructBinaries = (x, y) => {
// Your code
}

```
[Soluction](substructBinaries.md)

---

Change a bit value of a bit vector (32 bits).
```js
const changeBitOfVector = (index, bitVector) => {
// Your code
}

let bitVector = [255, 3, 7];

changeBitOfVector(0, bitVector); // 255 to 254, or ..11111111 to ..11111110
console.log(bitVector); //-> [254, 3, 7]

changeBitOfVector(33, bitVector); // 3 to 1, or ..11 to ..10
console.log(bitVector); //->  [254, 1, 7]

changeBitOfVector(66, bitVector); // 7 to 3, ..111 to ..011
console.log(bitVector); //-> [254, 1, 3]

```
[Soluction](changeBitOfVector.md)

---
