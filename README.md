# Digits-and-letters
s = input("Input a string: ")

d = 0
l = 0

for c in s:
    if c.isdigit():
        d = d + 1
    elif c.isalpha():
        l = l + 1
    else:
        pass

print("Letters", l)
print("Digits", d)
OUTPUT:
Input a string: Hello123
Letters 5
Digits 3
