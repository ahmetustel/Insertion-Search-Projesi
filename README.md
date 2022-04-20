# Insertion-Search-Projesi

Veri Yapıları ve Algoritmalar Dersi - Insertion Search Projesi

---

---

[22,27,16,2,18,6]

## 1.Yukarıda verilen dizinin sort türüne göre aşamaları;

1.Adım --> [22,27,16,**2**,18,6] -- En küçük sayıyı bulur

2.Adım --> [**2**,27,16,**22**,18,6] -- Birinci eleman ile en küçük sayıyı yer değiştirir.

3.Adım --> [2,**6**,16,22,18,**27**] -- İkinci eleman ile en küçük sayıyı yer değiştirir.

4.Adım --> [2,6,**16**,18,22,27] -- Üçüncü elemanın en küçük sayı olduğu tespit edilir, yer değişikliği olmaz.

5.Adım --> [2,6,16,**18**,22,27] -- Dördüncü elemanın en küçük sayı olduğu tespit edilir, yer değişikliği olmaz.

6.Adım --> [2,6,16,18,**22**,27] -- Beşinci elemanın en küçük sayı olduğu tespit edilir, yer değişikliği olmaz.

7.Adım --> [2,6,16,18,22,**27**] -- Altıncı elemanın en küçük sayı olduğu tespit edilir, yer değişikliği olmaz.

## 2. Big O Notation gösterimi;

1.İşlem --> [22,27,16,2,18,6] n adet kontrol -- 6

2.Adım --> [2,27,16,22,18,6]

3.Adım --> [2,6,16,22,18,27]

4.Adım --> [2,6,16,18,22,27]

--> O(n^2)

## 3. Time Complexity

Average Case:
