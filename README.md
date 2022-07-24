# MergeSort-Patika.dev
Merge Sort Bitirme Projesi - Patika.dev 

# Merge Sort Projesi
[16,21,11,8,12,22]

- 1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- 2-Big-O gösterimini yazınız.

# 1 - Merge Sort Aşamaları
1- [16,21,11,8,12,22] dizisi ikiye bölünür.

2- [16,21,11] - [8,12,22]

3- [16,21] - [11] ve [8,12] - [22]

4- [16] [21] - [11] ve [8] [12] - [22] artık hepsi tek kaldığı için bu verileri küçükten büyüğe kendi aralarında birleştirme yapabiliriz.

5- [16,21] - [11] ve [8,12] - [22]

6- [11,16,21] ve [8,12,22] en son iki grup da bir araya getirilir.

7- [8,11,12,16,21,22]


# 2 - Big O Notation Gösterimi
Bölme yaparken : logn kere bölme işlemi yapılmış olur.
Birleştirme yaparken : n kere birleştirme işlemi yapılmış olur.

Worst Case: O(nlogn)

Average Case: O(nlogn)

Best Case: O(nlogn)

www.patika.dev
