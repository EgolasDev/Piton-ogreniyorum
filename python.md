<h1>Değişkenler</h1>

String yani metinleri " sembolünü kullanarak tanımlarız. Buarada tüm değişken isimleri üyük harf yada rakamla başlamaz ve türkçe karakter kullanılmaz.
Örnek: `string = "Metin"`

Rakamları yani integer ları tanımlarken özel sembol kullanmayız.
Örnek: `integer = 9`

Virgüllü sayıları yani float ları integer lar gibi tanımlarız ama en önemlisi python dilinde virgül yerine nokta (.) kullanılır. Aksi takdirde hata ile karşılaşırsınız
Örnek: `float = 9.1`

<h1>Substring</h1>
Ek Bilgiler: float(), int() ve str() fonksiyonları ile değişkenleri tipini değişebiliriz. type() fonksiyonu ile değişkenlerin tipini anlayabiliriz.
Örnek:

```js
text = "Hi world!"
print(type(text))

text = "Hi world!"
print(text[1])
```
Kodunu çalıştırıp görelim. Gördüğünüz gibi mesajdaki 2. karakteri gönderdi. Burda python dilinin saymaya sıfırdan başladığını anlıyoruz. Gelin bu özelliği biraz daha açalım.

```js
text = "Hi world!"
print(text[1:5])
```
Burdada : sembolünü kullandık. Koddan anlaşıldığı gibi "i wo" çıktısını verdi yani boşluklarda birer karakter olarak göürülüyor. ve [1:5] koduda değişkene şunu emrediyor: 1den 5e kadar devam et ve yazdır. Peki 1: yazıp 5in yerini boş bırakırsak nolur yada tam tersi :5 yazsaydık nolurdu? 1: kodu 1den başla ve herşeyi yazdır mantığında olurdu diğer olasılıkla birlikte.
<h1>Len Fonksiyonu</h1>
Len fonksiyonunun karşılığı length dir. Ve length in türkçe karşılığı uzuluktur. Pythondaki karşılığı verideki karakter sayısını hesaplar.
Örnek:

```js
text = "Hi world!"
print(len(text))
```
Kodun console daki karşılığı 9 olacaktır.
<h1>Lower ve Upper</h1>
Lower fonksiyonu metnin tüm karakterlerini küçük harfe çevirir. Upper ise büyük harfe çevirir. 
Örnek:

```js
text = "Hi world!"
print(text.lower())
```
Ek bilgi: capitalize() fonksiyonu ise İlk harfi büyük harfe çevirir.
<h1>Replace</h1>
Replace fonksiyonu metindeki karakterleri değiştirir.
Örnek:

```js
text = "Selam dünya"
print(text.replace("a","e"))
```
Bu kodda a karakterini e karakteri diye değiştik.
<h1>Split ve Strip</h1>
Split fonksiyonu metni ayırmaya yarar.
Örnek:

```js
text = "Hi world!"
print(text.split())
```
Kodunda gördüğümüz gibidir. Gelin birde ayırdığımız metinden kelime seçelim.

```js
text = "Hi world!"
print(text.split()[0])
```
Ve sıfırıncı kelimeyi seçtik. Şimdi detaylara girelim. Split fonksiyonun ayrıcısı standart olarak boşluktur. Yani split(" ") dır. Ve " " sembolü tarafından ayrılır. Ve Strip fonksiyonuda standart olarak gelir ve bu fonksiyon metindeki baştaki ve sondaki boşlukları görmezden gelmeye yarar

```js
text = "   Hi world!    ".strip()
print(text.split(" "))
```
Başka bir örneğe bakalım:

```js
text = "   Hi;world!    ".strip()
print(text.split(;))
```
Fonksiyonumuz bu kadardı.
<h1>İnput</h1>
İnput fonksiyonu kullanıcıdan veri almaya yarar. Önemli birşey daha: İnputdan alınan veri her zaman string dir. Ama bunu sonradan int() ve float() ile değişebiliriz.

```js
text = input("Bu gün nasılsınız? ")
print("Bu günki durumunuz: " + text)
```
<h1>Listeler</h1>
Listeler javascript'te array olarak geçiyordur. Peki nedir bu listeler gelin bir bakalım;<br>

`list = ["ilk","ikinci","ucuncu"]`
ilk, ikinci ve ucuncu'yü list değişkeni içine listeledik peki bunları nasıl çağıracağız?<br>

`print(list[0])`
0 yerine listedeki almak istediğiniz verinin indexini yazmalısınız. Index almayı bilmeyenler için en baştaki veriden başlayarak 0,1,2 diye devam eder.
<h1>Sonraki Ders..</h1>

Yakında