# if-else-python3
#python3 basic program
import math
import os
import random
import re
import sys

if __name__ == '__main__':
    n = int(raw_input().strip())
    # Python If-Else - Hacker Rank Solution START
    if n%2 != 0:
        print("Weird")
    else :
        if(n>=2 and n<=5):
            print("Not Weird")
        elif(n>=6 and n<=20):
            
