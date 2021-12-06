## While döngüsü ile  Menu Oluşturma ##

```python

while True:
    
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
        print("Seçim: 1- Yeni Kayıt Ekle Seçildi")
    elif secim==2:
        print("Seçim: 2- Sınıf ortalamasını Hesapla")
    elif secim==3:
        print("Seçim: 3- Kalan Öğrencileri Göster")
    elif secim==4:
        print("Seçim: 4- Geçen Öğrencileri Göster ")
    else:
        print("Lütfen 1-5 arası rakam Giriniz..")

print("Çıkış Yapıldı..")


```
