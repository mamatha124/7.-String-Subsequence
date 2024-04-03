# 7.-String-Subsequence in python
t = input()
s = input()
if len(s) > len(t):
    print("0")
i = j = 0
while j < len(t):
    if i < len(s) and s[i] == t[j]:
        i += 1
        j += 1
    else:
        j += 1
if i == len(s):
    print("1")
else:
    print("0")
