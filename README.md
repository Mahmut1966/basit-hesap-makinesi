# basit-hesap-makinesi
print("""Hesap Makinesi
1. Toplama İşlemi
2. Çıkarma işlemi
3.Çarpma İşlemi
4.Bölme İşlemi
""")


a = int(input("Birinci Sayıyı Giriniz: "))

b = int(input("İkinci Sayıyı Giriniz: "))

islem = input("İşlem Seçiniz: ")

if islem == 1:
  print("a + b".format (a,b,a + b))
elif islem == 2:
    print("a - b".format(a,b, a - b))
elif islem == 3:
    print("a*b".format(a,b,a*b))
elif islem == 4:
    print("a/b".format(a,b,a/b))
else:
    print("Geçersiz işlem!!!!")
