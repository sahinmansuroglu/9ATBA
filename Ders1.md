> **1. Kisa kenarı 5 cm uzun kenarı 3 cm olan dikdörtgenin alanını hesaplatınız**

**Çözüm**
```python

kisaKenar=5
uzunKenar=3

alan=kisaKenar*uzunKenar

print(f"Dikdörtgenin Alanı:{alan}")

```

> **2. Kisa kenar ve uzun kenar uzunluğu klavyeden girdirilen dikdörtgenin alanını hesaplatınız.**

**Çözüm**
```python

kisaKenar=int(input("Uzun kenar uzunluğunu giriniz:"))
uzunKenar=int(input("Kısa kenar uzunluğunu giriniz:"))

alan=kisaKenar*uzunKenar

print(f"Dikdörtgenin Alanı:{alan}")

```

**Ekran Çıktısı**

![image](https://user-images.githubusercontent.com/28144917/137683118-d7e1fb9d-8b83-41df-ad16-7716ef27b71b.png)


> **Atama Öperatörleri Örnekler**

```python
a=5
a*=3   ## a=a*3
print(f"*= işlemi sonrasi {a}")  ## a nın değerini 15 yazar

a//=2   ## a=a // 2
print(f"//= işlemi sonrasi {a}") ## a nın değerini 7 yazar

a/=2   ## a=a / 2
print(f"/= işlemi sonrasi {a}") ## a nın değerini 3,5 yazar

a-=0.5   ## a=a - 0.5
print(f"-= işlemi sonrasi {a}") ## a nın değerini 3 yazar

a**=3   ## a=a ** 2
print(f"**= işlemi sonrasi {a}") ## a nın değerini 27 yazar

a%=5   ## a=a % 5
print(f"%= işlemi sonrasi {a}") ## a nın değerini 2 yazar

```

**Ekran Çıktısı**

![image](https://user-images.githubusercontent.com/28144917/137684933-e45d244c-24cc-414a-ae0d-cd376a056a19.png)
