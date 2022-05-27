# Tril-A-Year-For-Days-Challenge

This is a challenge problem to exercise your coding skillz!

The goal is to create a project with a Solidity smart contract with a correctly working function named ***payForDays*** _with unit tests verifying that it works correctly_!!

Suppose you get paid some ether every day, and it adds up to 1 trillion ethereum per year.

The function ***payForDays*** should take an argument of type _uint256_ (the number of days to consider), and it should return a value of type _uint256_ (the amount of total wei earned over that many days).

Remember, there is 10^18 wei in one ether! 

some sample test cases:

0 days --> 0 wei

1 days --> 2.739726e+27 wei

2 days --> 5.4794521e+27 wei

30 days --> 8.2191781e+28 wei

100 days --> 6.9863014e+29 wei

365 days --> 1e+30 wei

---


BONUS - have the function ***payForDays*** take a string instead of an integer, and the string can be decimals values such as "100.125"

bonus test cases:

'1' days --> 2.739726e+27 wei

'1.125' days --> 3.0821918e+27 wei

'30.5' days -> 8.3561644e+28 wei

'99.999999' days -> 2.739726e+29 wei
