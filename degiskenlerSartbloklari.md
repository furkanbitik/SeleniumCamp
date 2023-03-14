1) # Veri Tipleri:
  ## Numeric:
    - integer: Tam Sayılar örneğin -1,-2,-3,1,2,20,12000, -5400 
    - float: Ondalıklı sayılar örneğin 0.75, 1.78, 18.7 
    - complex: karmaşık sayılar örneğin 1i + 2j - 3z
 ## boolean: 
    True veya False tutar. Örneğin bilgi_dogru = true
 ## Sequence:
    - string: Metin verilerini temsil eder. örneğin "Türkye" ya da 'Türkiye'
    - list: Liste şeklinde farklı verilerimizi tutar ["Ali", 5, 1.75, 1j, 'a', 0.2587, true]
    - tuple: Liste şeklinde farklı verilerimizi tutar. list veri tipinden farkı ekleme, silme ve güncelleme yapılamaz. Örneğin tuple = ("banana", "grape", "cherry")
 ## set: 
    Mantığı list ve tuple ile aynıdır. Fark olarak sort ve index işlemleri yapılamaz. Örneğin set1 = {"a", "b" , "c"} / set2 = {1, 2, 3}
 ## dictionary: Python collection veri tiplerinden olan dictionary, key ve value şeklinde verileri saklayabileceğimiz bir veri tipidir. 
 - Örneğin:
 ```
 
 ogrenci = {
  "numara": "120",
  "ad": "Ahmet",
  "soyad": "Yılmaz"
}

```

2) # Kodlama.io sitesinde değişken olarak kullanıldığını düşündüğünüz verileri, veri tipleriyle birlikte örneklendiriniz.
    - integer : ilerleme değerleri, kurs ücretleri 
    - string: kurslar, eğitmenler, sekmeler
 
3) # Kodlama.io sitesinde şart blokları kullanıldığını düşündüğünüz kısımları örneklendiriniz ve Python dilinde bu örnekleri koda dökünüz.

    - giriş bölümü
```
user = "JohnSteve"
pasw = "123john45steve78"


username = input("Username:")
password = input("password:")

if(user == username and pasw == password):
    print("login successful")

else:
    print("login failed. username or password is incorrect")
    
```
