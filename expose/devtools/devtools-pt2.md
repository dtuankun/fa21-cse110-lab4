1. The bug is that in `printSum` num1 and num2 data type is string, so when it is passed to the calculateSum, the result will be the concatenated num1 and num2 rather than adding them.
2. I would fix it by converting the values from getElementById.value to number first using `Number()`
