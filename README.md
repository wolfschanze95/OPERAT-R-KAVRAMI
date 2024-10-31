
#             OPERATÖR KAVRAMI 
Python'da operatörler, veriler üzerinde işlem yapmak için kullanılan sembollerdir. Farklı türlerde operatörler vardır ve her biri belirli bir işlemi gerçekleştirir. İşte Python'da yaygın olarak kullanılan operatör türleri:

# 1. Aritmetik Operatörler
Aritmetik operatörler, matematiksel işlemler için kullanılır.

+ : Toplama
- : Çıkarma
* : Çarpma
/ : Bölme (sonuç float olur)
// : Tam Bölme (sonuç tam sayı olur)
% : Modül (kalan)
** : Üs alma
Örnek:

python
Kodu kopyala
a = 10
b = 3
print(a + b)  # 13
print(a / b)  # 3.3333...
print(a // b) # 3
print(a % b)  # 1
print(a ** b) # 1000
2. Karşılaştırma Operatörleri
Karşılaştırma operatörleri, iki değeri karşılaştırmak için kullanılır ve sonuç olarak True veya False döner.

== : Eşitlik
!= : Eşitsizlik
> : Büyük
< : Küçük
>= : Büyük veya eşit
<= : Küçük veya eşit
Örnek:

python
Kodu kopyala
print(a == b)  # False
print(a != b)  # True
print(a > b)   # True
print(a < b)   # False
3. Mantıksal Operatörler
Mantıksal operatörler, boolean (True/False) değerleri üzerinde işlem yapar.

and : Her iki koşulun da doğru olması gerekir.
or : En az bir koşulun doğru olması yeterlidir.
not : Koşulun tersini alır.
Örnek:

python
Kodu kopyala
x = True
y = False
print(x and y)  # False
print(x or y)   # True
print(not x)    # False
4. Atama Operatörleri
Atama operatörleri, bir değişkene değer atamak için kullanılır.

= : Atama
+= : Toplayarak atama
-= : Çıkararak atama
*= : Çarpıp atama
/= : Bölüp atama
Örnek:

python
Kodu kopyala
c = 5
c += 3  # c = c + 3
print(c)  # 8
5. Kimlik Operatörleri
Kimlik operatörleri, iki nesnenin aynı bellek alanını paylaşıp paylaşmadığını kontrol eder.

is : Aynı nesne olup olmadığını kontrol eder.
is not : Farklı nesne olup olmadığını kontrol eder.
Örnek:

python
Kodu kopyala
a = [1, 2, 3]
b = a
c = list(a)

print(a is b)      # True
print(a is c)      # False
print(a == c)      # True
6. Üyelik Operatörleri
Üyelik operatörleri, bir nesnenin belirli bir koleksiyonda (liste, dizi, vb.) olup olmadığını kontrol eder.

in : Nesnenin koleksiyonda olup olmadığını kontrol eder.
not in : Nesnenin koleksiyonda olmadığını kontrol eder.
Örnek:

python
Kodu kopyala
my_list = [1, 2, 3, 4]
print(2 in my_list)      # True
print(5 not in my_list)  # True
Bu operatörlerin her biri, Python'da farklı veri türleri ve işlemlerle çalışırken kullanılır. Python, bu operatörleri bir arada kullanarak daha karmaşık işlemler gerçekleştirmeye de olanak tanır.
