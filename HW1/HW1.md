# HW1

1a. Convert 757.25_10 to hex then binary

757 + 0.25

757 / 16 = 47 r 5

47 / 16 = 2 r 15

2 / 16 = 0 r 2

.25 * 16 = 4.00

2F5.4 = 0010 1111 0101

---

1b. Convert 123.17_10 to hex then binary

123 + .17

123 / 16 =  7.6875 .. .6875* 16 = 11 = B

7 / 16 = 7

.17 * 16 = 2.72

.72 * 16 = 11.52

.52 * 16 = 8.32

.32 * 16 = 5.12

.12 * 16 = 1.92

7B.2B85 = 0111  1011 . 0010  1011 1000 0101 0001

---

1c. Convert 356.89_10 to hex then binary

356 + .89

356 / 16 = 22.25 .. .25*16 = 4

22 / 16 = 1.375 .. .375*16 = 6

1/16 = 1

.89 * 16 = 14.24

.24 * 16 = 3.84

.84 * 16 = 13.44

.44 * 16 = 7.04

164.E3D7 = 0001 0110 0100 . 1110 0011 1101 0111

---

3. Convert to base 6: 3BA.25_14

3 * 14^2 = 588

B * 14^1 = 154

A * 14^0 = 10

2 * 14^-1 = .14

5 * 14^-2 = .03

752.17_10

752 + .17 

752/6 = 125.33...   .333*6 = 2

125/6 = 20.83333...   .8333*6 = 5

20/6 = 3.333...  .333*6 = 2

3/6 = 0.5..  0.5*6 = 3

.17 * 6 = 1.02

.02 * 6 = 0.12

.12 * 6 = 0.72

.72 * 6 = 4.32

## 3252.1004_10

---

5a.  Add subtract and multiply in binary 

1111 and 1010

1111 + 1010 = 11001

1111 - 1010 = 0101

1111 * 1010 = 10010110

---

5b. Add subtract and multiply in binary

110110 + 11101 = 1010011

110110 - 11101 = 011001

110110 * 11101 = 1100001110

---

5c. Add subtract and multiply in binary 

100100 + 10110 = 111010

100100 - 10110 = 01110

100100 * 10110 = 1100011000

---

7. Add the following numbers in binary using 2’s complement to represent negative numbers. Use a word length of 6 bits (including sign) and indicate if an overflow occurs.

a. 21 + 11

10101 + 1011 = 100000 (overflow)

b. -14+(-32)

11 0010 +10 0000 = (1)010010 (overflow)

c. (-25) + 18

10 0111 + 01 0010 = 11 1001

d. -12 + 13

110100 + 001101 = 00 0001

e. -11 + -21

110101 + 101011 = (1)10 0000

---

9.

7-3-2-1 code

3-6-5-9

    

0 0000

1 0001

2 0010

3 0100

4 0101

5 0110

6 0111

7 1000

8 1001

9 1010

# 0100 0111 0110 1010

---

11. Convert to octal. Convert to hexadecimal. Then convert both of your answers to decimal, and verify that they are the same.

101111010100.101 _ 2

101 111 010 100 = 5 7 2 4 . 5 _ 8

1011 1101 0100. 1010 = B D 4 . A _ 16

5 * 8^3 = 2560

7 * 8^2 = 448

2 * 8^1 = 16

4 * 8^0 = 4

5 * 8^-1 = 0.625

3028.625

B * 16^2 = 2816

D * 16^1 = 208

4 * 16^0 = 4

A * 16^-1 = .625

3028.625

---

100001101111.01 _ 2

100 001 101 111 . 010  = 4_1_5_7. 2 

1000 0110 1111 . 0100 = 8_6_F. 4

4 * 8 ^ 3 = 2048

1 * 8 ^ 2 = 64

5 * 8 ^ 1 = 40

7 * 8 ^ 0 = 7

2 * 8 ^-1 = .25

2159.25

8 * 16^2 = 2048

6 * 16^1 = 96

F * 16^0 = 15

4 * 16^-1 = .25

2159.25

---

13. Convert to hexadecimal then to binary: 544.1_9

544 + 0.1 

5 * 9^2 = 405

4 * 9^1 = 36

4 * 9^0 = 4

1 * 9^-1 = .111...

445.111...

445 + .111..

445/16 = 27.8125 ... r 13

27/16 = 1.6875 r 11

1/16 = r 1

.111*16 = 1.78

.78*16 = 12.48

.48*16 = 7.68

# 1BD.1C7

---

15. Devise a scheme for converting base 3 numbers directly to base 9. Use your method to convert the following number to base 9: 1110212.20211 

0 → 0

1 → 1

2 → 2

10 → 3

11 → 4

12 → 5

20 → 6

21 → 7

etc .. 

(01) (11) (02) (12) . (20) (21) (10)

1425.673

---

17. Add, subtract, multiply in binary:

1111 + 1001 = 11000

1111 - 1001 = 0110

1111 * 1001 = 1000 0111

1101001 + 110110 = 1001 1111

1101001 - 110110 = 11 0011

1101001 * 110110 = 1011000100110

---

19.  Divide in binary:

11101001 / 101 = 101110 r 11

110000001 / 1110 = 11010 r 101

1110010 / 1001 = 1100 r 110

---

21. Assume three digits are used to represent positive integers and also assume the following operations are correct. Determine the base of the numbers. Did any of the additions overflow?

a. 654 + 013 = 000 base 7 (overflow)

b. 024+043+013+033= 223 base 5

c. 024+043+013+033= 201base 6

---

23. Convert 0.36363636.._10 to its exact equivalent base 8 number.

 

---

25. a. Show how to represent each of the numbers (5-1), (5^2-1) and (5^3) as base 5 numbers. Generalize your answers to part a and show how to represent (b^(n) -1) as a base b number, where b can be any integer larger than 1 and n any integer larger than 0. Give a mathematical derivation of your result.

5-1 = 4

5^2 - 1 = 44

5 ^ 3 = 444

---

![](-894901f5-d9d2-45b0-909d-820b8f9698c0untitled)

27. a. Convert (0.12)_3 to a base 6 fraction.

b. Convert (0.375)_10 to a base 8 fraction.

c.

---

29. Is it possible to construct a 5-3-1-1 weighted code? A 6-4-1-1 weighted code? Justify your reasons.

Yes, 5-3-1-1 can represent all digits from 0 to 9 while 6-4-1-1 cannot represent digits 3 and 9.

---

31. Construct a 6-2-2-1 weighted code for decimal digits. What number does 1100 0011 represent in this code.

0000 → 0

0001 → 1

0010 → 2

0011 → 3

0110 → 4

0111 → 5

1000 → 6

1001 → 7

1100 → 8

1101 → 9

1100 0011 represents 83

---

33. Construct a 7-3-2-1 code for base 12 digits. Write B4A9 using this code.

0 → 0000

1 → 0001

2 → 0010

3 → 0100

4 → 0101

5 → 0110

6 → 0111

7 → 1000

8 → 1001

9 → 1010

A → 1100

B → 1101

b4a9 = 1101 0101 1100 1010

---

35. Convert to hexadecimal, and then give the ASCII code for the resulting hexadecimal number (including the code for the hexadecimal point):

a. 222.22_10

222.22

16 | 222

16 | 13   r 14

     |  0    r 13

0.22 * 16 = 3.52

.52 * 16 = 8.32

1000100 1000101 0101110 0110011 0111000 = **DE.38**

b. 183.81_10

16 | 183

16 | 11   r 7

    |   0   r 11

0.81 * 16 = 12.96

.96 * 16 = 15.36

1000010 0110111 0101110 1000011 1000110 = **B7.CF**

---

37. 

![](-c77e2b77-e0d3-4aa4-955d-806577508370untitled)

a.  01001 + 00110 = 01111  | 

     01001 + 00101 = 01110

b.  11010 + 00111 = (1)00001

     11010 + 00110 = 00001 overflow

c.   10110 + 10011 = (1)01001 overflow

      10110 + 10010 = 01001 overflow

d. 11011 + 11001 = (1)10100

11011 + 11000 = 10100

e. 11100 + 01011 = 00111

11100 + 01010 = 00111   

---

39.

![](-d5bf159c-e099-46e1-9147-3a5015d91280untitled)

---

41.

![](-c7fcfbf2-1f3d-4ccc-86bf-cd4e5c9ef067untitled)

---

43.

![](-90d11cd7-58eb-4884-a67d-c09be8fe60d5untitled)

---

45.

![](-35a1f80b-56e3-41f8-a2c0-fb008881534funtitled)

---