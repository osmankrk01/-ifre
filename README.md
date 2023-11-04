# -ifre
import random

Chars = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ123456789!@#$%^&*()ervaaa"

sifre_len = int(input("Şifre kaç karakterden oluşturulsun : "))
sifre_count = int(input("Kaç adet şifre oluşturulsun : "))
for x in range(0, sifre_count):
    sifre = ""
    for x in range(0, sifre_len):
        sifre_char = random.choice(Chars)
        sifre = sifre + sifre_char
    print("Random Şifreniz : ", sifre)
