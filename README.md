# String Methods (www.patika.dev)

---

## Length

String uzunluğunu verir.

## ToUpper, ToLower

Tüm harfleri büyük veya küçük yapar

## Concat

Stringing sonuna istenilen stringi ekler

## Compare, CompareTo

2 stringi karşılaştırır

string1.CompareTo(string2) 
string1.Length = string2.Length => 0
string1.Length > string2.Length => 1
string1.Length < string2.Length => -1

string.Compare(string1,string2, true)
string.Compare(string1,string2, false)
true: büyük/küçük harf duyarsız 
false:  büyük/küçük harf duyarlı

## Contains, EndsWith, StartsWith

contains string içerisinde aranan string var ise true yok ise false döndürür.
EndsWith string aranan string ile bitiyor ise true yok ise false döndürür.
StartsWith string aranan string ile başlıyorsa ise true yok ise false döndürür.

## Indexof, LastIndexOf

Indexof aranan stringin ilk bulunduğu indexi döndürür.
LastIndexOf aranan stringin en son bulunduğu indexi döndürür.

## Insert

İstenilen indexe farklı bir string ekler.

## PadLeft, PadRight

Eğer girilen ilk parametre string.Lengthen büyükse kalan parametre-string.Length kadar istenilen karakteri ekler. (default olara boşluk ekler)

## Remove

string1.Remove(x,y);
x indeksinden başlayıp y tane karakter siler.

## Replace

string1.Replace(x,y);
stringde bulunan x stringi yerine y stringini yazar

## Split

Stringi istenilen karaktere göre parçalara ayırır

## Substring

string1.Substring(x,y)
x inci indexten başlayıp y kadar karakteri alır.