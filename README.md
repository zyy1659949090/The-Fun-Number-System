# The-Fun-Number-System

The Fun Number System

Description

In a k bit 2's complement number, where the bits are indexed from 0 to k-1, the weight of the most significant bit (i.e., in position k-1), is -2^(k-1), and the weight of a bit in any position i (0 ≤ i < k-1) is 2^i. For example, a 3 bit number 101 is -2^2 + 0 + 2^0 = -3. A negatively weighted bit is called a negabit (such as the most significant bit in a 2's complement number), and a positively weighted bit is called a posibit. 
A Fun number system is a positional binary number system, where each bit can be either a negabit, or a posibit. For example consider a 3-bit fun number system Fun3, where bits in positions 0, and 2 are posibits, and the bit in position 1 is a negabit. (110)Fun3 is evaluated as 2^2-2^1 + 0 = 3. Now you are going to have fun with the Fun number systems! You are given the description of a k-bit Fun number system Funk, and an integer N (possibly negative. You should determine the k bits of a representation of N in Funk, or report that it is not possible to represent the given N in the given Funk. For example, a representation of -1 in the Fun3 number system (defined above), is 011 (evaluated as 0 - 2^1 + 2^0), and 
representing 6 in Fun3 is impossible.

Input

The first line of the input file contains a single integer t (1 ≤ t ≤ 10), the number of test cases, followed by the input data for each test case. Each test case is given in three consecutive lines. In the first line there is a positive integer k (1 ≤ k ≤ 64). In the second line of a test data there is a string of length k, composed only of letters n, and p, describing the Fun number system for that test data, where each n (p) indicates that the bit in that position is a negabit (posibit). 
The third line of each test data contains an integer N (-2^63 ≤ N < 2^63), the number to be represented in the Funk number 
system by your program.

Output

For each test data, you should print one line containing either a k-bit string representing the given number N in the Funk number system, or the word Impossible, when it is impossible to represent the given number.

Sample Input

2

3

pnp

6

4

ppnn

10

Sample Output

Impossible

1110

