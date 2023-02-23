## Stutern SGA 1.4 JS Assignment

### Q(1). List the symbols for each of the below Javascript operators

A. Arithmetic Operators:

    - Addition operator (+);

    - Subtraction operator (-);

    - Division operator (/);

    - Multiplication operator (*);

    - Modulo operator (%);

    - Exponentiation operator (**);

    - Increment operator (++);

    - Decrement operator (--).

B. Assignment Operators:

    - Assignment operator (=);

    - Addition assignment operator (+=);

    - Subtraction assignment operator (-=);

    - Division assignment operator (/=);

    - Multiplication assignment operator (*=);

    - Modulo assignment operator (%=);

    - Exponentiation assignment operator (**=).

C. Comparison Operators:

    - Greater than (>);

    - Greater than or equal to (>=);

    - Less than (<);

    - Less than or equal to (<=);

    - Loose equality operator (==);

    - Strict equality operator (===);

    - Loose inequality operator (!=);

    - Strict inequality operator (!==).

D. Logical Operators:

    - Logical AND (&&);

    - Logical OR (||);

    - Logical NOT (!).

E. Bitwise Operators:

    - AND (&);  // Sets each bit to 1 if both bits are 1

    -  OR (|);  // Sets each bit to 1 if one of two bits is 1

    - XOR (^);  // Sets each bit to 1 if only one of two bits is 1

    - NOT (~);  // Inverts all the bits

    - Zero fill left shift (<<);    // Shifts left by pushing zeros in from the right and let the leftmost bits fall off

    - Signed right shift (>>);      // Shifts right by pushing copies of the leftmost bit in from the left, and let the rightmost bits fall off

    - Zero fill right shift (>>>);  // Shifts right by pushing zeros in from the left, and let the rightmost bits fall off

### Q(2). For each JavaScript Operator, write 2 examples

A. Arithmetic Operators:

    - Addition operator (+);

        let x = 3 + 2; // 5

        let y = 11 + 7; // 18

    - Subtraction operator (-);

        let a = 5 - 3; // 2

        let b = 27 - 15; // 12

    - Division operator (/);

        let m = 6 / 2; // 3

        let n = 45 / 3; // 15

    - Multiplication operator (*);

        let c = 3 * 3; // 9

        let d = 10 * 4; // 40

    - Modulo operator (%);

        let p = 9 % 3; // 0

        let q = 17 % 2; // 1

    - Exponentiation operator (**);

        let v = 5 ** 2; // 25

        let w = 2 ** 3; // 8

    - Increment operator (++);

        let a = 5;
            a++;
            console.log(a) // 5
            console.log(a) // 6

        let b = 9;
            b++;
            console.log(b) // 9
            console.log(b) // 10

    - Decrement operator (--);

        let c = 8;
            c--;
            console.log(c) // 8
            console.log(c) // 7

        let d = 16;
            d--;
            console.log(d) // 16
            console.log(d) // 15

B. Assignment Operators:

    - Assignment operator (=);

        let p = 50;

        const name = "Emmanuella";

    - Addition assignment operator (+=);

        let w = 51;
            w += 4; // 55

        let z = 32;
            z += 10; // 42

    - Subtraction assignment operator (-=);

        let k = 73;
            k -= 14; // 59

        let g = 62;
            g -= 31; // 31

    - Division assignment operator (/=);

        let p = 33;
            p /= 3; // 11

        let b = 16;
            b /= 4; // 4

    - Multiplication assignment operator (*=);

        let t = 6;
            t *= 5; // 30

        let d = 2;
            d *= 14; // 28

    - Modulo assignment operator (%=);

        let m = 71;
            m %= 7; // 1

        let n = 27;
            n %= 5; // 2

    - Exponentiation assignment operator (**=);

        let w = 3;
            w **= 0; // 1

        let l = 6;
            l **= 2; // 36

C. Comparison Operators:

    - Greater than (>);

        let a = 73;
            a > 14; // True

        let b = 12;
            b > 31; // False

    - Greater than or equal to (>=);

        let c = 30;
            c >= 10; // True

        let d = 7;
            d >= 34; // False

    - Less than (<);

        let e = 19;
            e < 14; // False

        let f = 2;
            f < 75; // True

    - Less than or equal to (<=);

        let z = 9;
            z <= 1; // False

        let s = 6;
            s <= 3; // False

    - Loose equality operator (==);

        let q = 5;
        q == '5';   // True

        let r = 15;
        r == '15';   // True
        
    - Strict equality operator (===);

        let p = 5;
        p === '5';   // False

        let k = 15;
        k === '15';   // False

    - Loose inequality operator (!=);

        let e = 5;
        e != '5';   // False

        let f = 15;
        f != '15';   // False

    - Strict inequality operator (!==).

        let m = 5;
        m !== '5';   // True

        let n = 15;
        n !== '15';   // True

D. Logical Operators:

    - Logical AND (&&);

        5 < 15 && 15 >= (7+8)   // True

        (25-7) == '18' && 9 <= (2**3) // False

    - Logical OR (||);

        5 > 15 || 15 < (7+8)   // False

        (25-7) == '18' && 9 <= (2**3) // True
        
    - Logical NOT (!).

        !(56 === '56')  // True

        !(3 == '3')     // False

E. Bitwise Operators:

    - AND (&);  // Sets each bit to 1 if both bits are 1

        5 & 1   // 1
        
        0101 & 0001 // 0001

    -  OR (|);  // Sets each bit to 1 if one of two bits is 1

        5 | 1   // 5
        
        0101 | 0001 // 0101

    - XOR (^);  // Sets each bit to 1 if only one of two bits is 1

        5 ^ 1   // 4
        
        0101 ^ 0001 // 0100

    - NOT (~);  // Inverts all the bits

        ~ 5 // 10
        
        ~0101   // 1010

    - Zero fill left shift (<<);    // Shifts left by pushing zeros in from the right and let the leftmost bits fall off

        5 << 1  // 10
        
        0101 << 1   // 1010

    - Signed right shift (>>);      // Shifts right by pushing copies of the leftmost bit in from the left, and let the rightmost bits fall off

        5 >> 1  // 2
        
        0101 >> 1   // 0010

    - Zero fill right shift (>>>);  // Shifts right by pushing zeros in from the left, and let the rightmost bits fall off

        5 >>> 1 // 2
        
        0101 >>> 1  // 0010

### Q(4). What is the result when the following program is executed?

    for (let i = 1; i < 20; i += 7) {
        console.log(i);
    }

    Answer - 1, 8, 15
