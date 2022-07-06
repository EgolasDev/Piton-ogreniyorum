# Notlar

```js
text = "Hi world!"
print(text[1:5])
```
1den 5e kadar devam et ve yazdır.

---

```js
text = "Hi world!"
print(len(text))
```
text değişkeninde kaç adet karakter var.

# Lower ve Upper
Lower fonksiyonu metnin tüm karakterlerini küçük harfe çevirir. Upper ise büyük harfe çevirir. 
Örnek:

```js
text = "Hi world!"
print(text.lower())
```
lower() değişkendeki tüm harfleri küçük harfe çevirir. upper() ise büyük harfe.
capitalize() ise İlk harfi büyük harfe çevirir.

---

```js
text = "Selam dünya"
print(text.replace("a","e"))
```
text değişkenindeki a karakterini e olarak yer değişti

---

```js
text = "Hi world!"
print(text.split())
```
değişkendeki kelimeleri ayırır.

```js
text = "Hi world!"
print(text.split()[0])
```
indexi sıfır olan kelimeye ulaştık.

```js
text = "   Hi world!    ".strip()
print(text.split(" "))
```
split() özelliğinin standart configi budur.

```js
text = "   Hi;world!    ".strip()
print(text.split(;))
```
Kelimeleri arasında ; sembolü varsa ayırıcak.

---

```js
text = input("Bişey yaz: ")
print("Yazdığın şey: " + text)
```
Kullanıcıdan değer alır.

---

`array = ["birinci","ikinci","ucuncu"]`
`print(array[0])`
indexi 0 olan değeri verir.

`array.append("dorduncu")`
En sondan başlayarak veri ekler

`array.remove("birinci")`
"birinci" değerini sildi

`list.clear()` tüm listeyi sıfırlar.

`list.count("ikinci")` Kodu ise "ikinci" verisinin listede kaç tane olduğunu verir.

`list.index("ikinci")` Kodu ise "ikinci" değerinin listede kaçıncı index olduğunu verir ama 1 kere çalışır ilk Amasya yı bulunca kod durur.

`list.pop(2)` Kodu ise indexi 2 olan veriyi siler.

`list.insert(0,"sıfırıncı")` Kodu ise indexi verilen veriyi bir sonraki indexe gönderir yani zincirleme olur ve yeni veri verdiğimiz indexe yerleşir.

`list.reverse()` Kodu ise listeyi terse çevirir.

`list2 = list` Kodu ise list ile list2 tanımlarını birbirine eşitler. Yani list2 değişince list de değişir.

`listkopyasi = list.copy()` Kodu ise yukarda anlattığımı önlemek içindir. Yani list tanımının tamamını listkopyasi na kopyalanır. Bunu list tanımını özelleştirme kodunun üstüne koyarsak anlamlı olur.

`list.extend(list2)` Kodu ise list tanımına extradan list2 tanımını ekler. Toplar.

`list.sort()` Kodu ise listeyi Alfabetik yada sayısal olarak baştan sona sıralar.