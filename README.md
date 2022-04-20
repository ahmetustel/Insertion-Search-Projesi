# Insertion-Sort-Projesi

Veri Yapıları ve Algoritmalar Dersi - Insertion Search Projesi

---

---

[22,27,16,2,18,6]

## 1.Yukarıda verilen dizinin insertion sort türüne göre aşamaları;

1.Adım --> [**2**,27,16,**22**,18,6] -- En küçük sayıyı bulur, birinci eleman ile en küçük sayıyı yer değiştirir,

2.Adım --> [2,**6**,16,22,18,**27**] -- En küçük ikinci sayıyı bulur,ikinci eleman ile bu sayıyı yer değiştirir,

3.Adım --> [2,6,**16**,18,22,27] -- Üçüncü elemanın en küçük üçüncü sayı olduğu tespit edilir, yer değişikliği olmaz,

4.Adım --> [2,6,16,**18**,22,27] -- Dördüncü elemanın en küçük dördüncü sayı olduğu tespit edilir, yer değişikliği olmaz,

5.Adım --> [2,6,16,18,**22**,27] -- Beşinci elemanın en küçük beşinci sayı olduğu tespit edilir, yer değişikliği olmaz,

6.Adım --> [2,6,16,18,22,**27**] -- Altıncı elemanın en küçük altıncı sayı olduğu tespit edilir, yer değişikliği olmaz, son eleman olduğu için sorting işlemi tamamlanır.

## 2. Big O Notation gösterimi;

--> O(n^2)

## 3. Time Complexity;

_Average_ Case: Aradığınız değerin **22** olması.

_Worst_ Case: Aradığınız değerin **6** olması.

_Best_ Case: Aradığınız değerin **2** olması.

## 4. Dizi sıralandıktan sonra 18 sayısının case kapsamı;

**_Average_** Case

## 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı;

1.Adım --> [**2**,3,5,8,**7**,9,4,15,6] -- En küçük sayıyı bulur, birinci eleman ile en küçük sayıyı yer değiştirir,

2.Adım --> [2,**3**,5,8,7,9,4,15,6] -- İkinci elemanın en küçük ikinci sayı olduğu tespit edilir, yer değişikliği olmaz,

3.Adım --> [2,3,**4**,8,7,9,**5**,15,6] -- En küçük üçüncü sayıyı bulur, üçüncü eleman ile bu sayıyı yer değiştirir,

4.Adım --> [2,3,4,**5**,7,9,**8**,15,6] -- En küçük dördüncü sayıyı bulur, dördüncü eleman ile bu sayıyı yer değiştirir.
