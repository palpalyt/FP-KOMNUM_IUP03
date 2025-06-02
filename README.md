|    NRP     |      Name      |
| :--------: | :------------: |
| 5025241001 | Kenzie Maheswara|
| 5025241002 | Palpal Yalmialam Tarminto |
| 5025241075 | Bismantaka Revano Dirgantara|
| 5025241168 | Naufal Bintang Brilian |
| 5025241262 | Rayen Yeriel Mangiwa |


# FP KOMNUM IUP03

## Number 19
![image](https://github.com/user-attachments/assets/16817a4e-30bd-4836-b5c3-242bc869b41b)

### Code Explanation

![image](https://github.com/user-attachments/assets/335f3ac9-19d2-4517-a02d-30c9b66b4655)

Set the inital guess for a0, a1, a2 all to 0.

#### First Iteration
![image](https://github.com/user-attachments/assets/0eee8a1f-5d10-4afd-994c-e437675f4125)

**Calculate a0**

At the first iteration substitute  a1 = 0, a2 = 0 into the first equation.

We then round(..., 2) to keep two decimal places. 

a0 = -44+3*(0)+4*(0))/2 = -22,0

**Calculate a1**

Now a0 = -22,0 (just computed) and a2 = 0.

a1 = 78+3*(-22,0)+2*(0))/9 = 1,33

**Calculate a2**

Now we use the newly computed a0 = -22.0 and a1 = 1.33.

a2 = 21+5*(-22,0)+1*(1,33))/3 = -29,22

**At this point, the iteration is done. The values are:**

a₀⁽¹⁾ = –22.00
a₁⁽¹⁾ =   1.33
a₂⁽¹⁾ = –29.22

#### Second Iteration
![image](https://github.com/user-attachments/assets/8831bcd6-3254-4ad5-9309-3af012869d77)

**Calculate a0**

Plug in a1 = 1.33, a2 = -29.22:

a0(2)= −44+3⋅(1.33)+4⋅(−29.22)/2 = -78.44

**Calculate a1**

Now a0 = -78.44 (just computed) and a2 = -29.22 (from iter 1).

a1(2)= 78+3⋅(−78.44)+2⋅(−29.22)/9 = -23.97

**Calculate a2**

Finally, use a0 = -78.44 and a1 = -23.97:

a2(2)= 21+5⋅(−78.44)+1*(-23,97)/3 = -131,72

**At this point, the iteration is done. The values are:**

a₀⁽²⁾ = –78.44
a₁⁽²⁾ = –23.97
a₂⁽²⁾ = –131.72
