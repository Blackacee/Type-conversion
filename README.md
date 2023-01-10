# Type-conversion


var test = (a,b) => Number(a) == Number(b);
test("", 0); // true;
test("0", 0); // true
test("", "0"); // true;
test("abc", "abc"); // false as operands are not numbers
