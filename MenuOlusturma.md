## While döngüsü ile  Menu Oluşturma ##

```python


while True:
    print("\n"*20)
    print("*****Yapılacak İşlemler******")
    print("1- Yeni Kayıt Ekle")
    print("2- Sınıf ortalamasını Hesapla")
    print("3- Kalan Öğrencileri Göster")
    print("4- Geçen Öğrencileri Göster")
    print("5- Çıkış")
    secim=int(input("Lütfen Seçiminizi Yapınız(1-5):"))
    if secim==5:
        break;
    elif secim==1:
        print("\n"*20)
        print("Seçim: 1- Yeni Kayıt Ekle Seçildi")
        input("Devam Etmek İçin Enter'a basınız...")
    elif secim==2:
        print("\n"*20)
        print("Seçim: 2- Sınıf ortalamasını Hesapla")
        input("Devam Etmek İçin Enter'a basınız...")
    elif secim==3:
        print("\n"*20)
        print("Seçim: 3- Kalan Öğrencileri Göster")
        input("Devam Etmek İçin Enter'a basınız...")
    elif secim==4:
        print("\n"*20)
        print("Seçim: 4- Geçen Öğrencileri Göster ")
        input("Devam Etmek İçin Enter'a basınız...")
    else:
        print("\n"*20)
        print("Lütfen 1-5 arası rakam Giriniz..")
        input("Devam Etmek İçin Enter'a basınız...")

print("Çıkış Yapıldı..")



```
