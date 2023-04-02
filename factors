#!/usr/bin/python3
import sys


# function to factorize n = p * q
def factorize(n):
    for i in range(2, n):
        if n % i == 0:
            return i, n//i
        return None, None


# input file
filename = sys.argv[1]
with open(filename, 'r') as f:
    for line in f:
        # parse number from line
        n = int(line.strip())

        # factorize
        p, q = factorize(n)

        # print factorization
        print(f"{n}={p}*{q}")
