# Concatenation
You're given two strings, A and B. A new string C is formed by concatenating B and A ( in the same order) and a '-' between them. Print C. Input The first line of the input contains two space separated strings P and Q.  Constraints: 1 ≤ |P| ≤ 103 1 ≤ |Q| ≤ 103 Output Print the resulting string.

def concatenate_strings(P, Q):
    return Q + '-' + P

# input
P, Q = input().split()

# Output 
print(concatenate_strings(P, Q))
