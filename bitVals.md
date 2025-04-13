| Bit no. | 8 | 7 | 6 | 5 | 4 | 3 | 2 | 1 |
|---------|---|---|---|---|---|---|---|---|
| Decimal |128| 64| 32| 16| 8 | 4 | 2 | 1 |
| Binary  | 1²| 1²| 0 | 0 | 1 | 0 | 0 | 0 | = 200¹⁰

| Operator: | Name: | Binary number operation: |
| --------- | ----- | ------------------------ |
|      \|   |   OR  | Return a 1 in each bit where either of<br> two combared bits is a 1. <br>Ex: 1010² (A¹⁶) \| 0101 (5¹⁶) = 1111 (F¹⁶) |
|     &     |   AND  | Return a 1 in each bit where both of<br> two combared bits is a 1. <br>Ex: 1010² (A¹⁶) & 1101 (C¹⁶) = 1000² (8¹⁶) |
|     ~     |  NOT   | Return a 1 in each bit where neither of<br> two combared bits is a 1. <br>Ex: 1110 ~ 0110 = 0001 |
|     ^     |  XOR   | Return a 1 in each bit where only one of<br> two combared bits is a 1. <br>Ex: 1100 ^ 0101 = 1001|
|    <<     | Shift<br>left| Move each bit that is a 1 a specified number of<br> bits to the left<br> Example: 0001² << 2¹⁰ = 0100² (5¹⁶) |
|    >>     | Shift<br>right| Move each bit that is a 1 a specified number of<br> bits to the left<br> Example: 1000² (8¹⁶) >> 2¹⁰ = 0010² (2¹⁶) |

