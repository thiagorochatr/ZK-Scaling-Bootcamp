## Maths Introduction

### Some modular arithmetic

1. Working with the following set of Integers S = {0,1,2,3,4,5,6}  

What is

a) 4 + 4

mod7, because the largest number in S is 6 (max remainder of 7)

1 (8 mod7)

b) 3 x 5

1

c) what is the inverse of 3 ?

(a * b) modn = 1

(3 * b) mod7 = 1

b = 5

2. For S = {0,1,2,3,4,5,6}

Can we consider 'S' and the operation '+' to be a group ?

Closure: since we are working with mod7, every two elements results in a mod7.

Associativity: (a + b) + c = a + (b + c). Mod is associative, so it's ok.

Identity: Yes, the 0 element. 0 + a ≡ a mod7

Inverse element: For each a ∈ S, there must exist an element a' ∈ S such that a + a' = a' + a = e (the identity element).

Let's check for each element:
0 + 0 ≡ 0 (mod 7)

1 + 6 ≡ 0 (mod 7)

2 + 5 ≡ 0 (mod 7)

3 + 4 ≡ 0 (mod 7)

4 + 3 ≡ 0 (mod 7)

5 + 2 ≡ 0 (mod 7)

6 + 1 ≡ 0 (mod 7)

Each element has an inverse in S.

So, yes.

3. What is -13 mod5 ?

2

4. Polynomials - For the polynomial $x^3 - x^2 + 4x - 12$

Find the positive root

f(2) = 0, so 2 is one of the roots.

Dividing f(x) by (x-2):

$(x^3 - x^2 + 4x - 12) / (x-2)$

$(x^3 - 2x^2 + x^2 - 2x + 6x -12) / (x-2)$

$(x^2 (x - 2) + x (x - 2) + 6(x - 2)) / (x-2)$

$(x^2  + x  + 6)(x-2) / (x-2)$

$(x^2  + x  + 6)$

In this polynomial, $\Delta = 1^2 - 4*1*6 = -23$, so the other 2 roots are complex.

What is the degree of this polynomial ?

3

### Use Cases
In your teams discuss any systems you have used that involved zero knowledge proofs. Have you seen any applications of zero knowledge proofs other than with a blockchain ? What is to you, the most important feature of zkp technology ? Think of some use cases of zero knowledge proofs that you would like to see developed.
