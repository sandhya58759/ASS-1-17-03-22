# ASS-1-17-03-22
program to remove ovals from the given string

s = input()
vowels = ['a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U']
for c in s:
    if c in vowels:
        s = s.replace(c, "")
print( s)
INPUT:
sandhya
OUTPUT:
sndhy
