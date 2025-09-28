def Mahoathaythe(text, k):
    ma = ""
    for ktu in text:
        if ktu.isalpha():
            if ktu.isupper():
                base = ord('A')
            else:
                base = ord('a')
            c = (ord(ktu) - base + k) % 26 + base
            ma += chr(c)
        else:
            ma += ktu
    return ma
P = "NguyenThiHaiYen"
k = 53 
Bandamahoa = Mahoathaythe(P, k)
print("Ten:", P)
print("Key:", k)
print("Bản mã hóa:", Bandamahoa)
