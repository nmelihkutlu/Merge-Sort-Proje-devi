# Merge Sort Proje Ödevi
>**[patika.dev](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje) platformu öğrenme projesidir.**
Profil için tıklayınız: [app.patika.dev/nmelihkutlu](https://app.patika.dev/nmelihkutlu)

Merge Projesi


## Soru

![](https://raw.githubusercontent.com/nmelihkutlu/mergeSortProjeOdevi/main/Merge%20Sort%20Question.png)

```
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
```


## Cevaplar
1. Merge Sort aşamaları:

    ```
    [16,21,11,8,12,22]
    1. [16,21,11] [8,12,22]
    2. [16,21] [11] [8,12] [22]
    3. [16] [21] [11] [8] [12] [22]
    4. [16,21] [8,11] [12,22]
    5. [8,11,16,21] [12,22]
    6. [8,11,12,16,21,22]

    *1.adım: 2ye ayır,
    *2.adım: tekrar ikiye ayır,
    *3.adım: hepsi tek kalana kadar ayır,
    *4.adım: 2li olarak sırala ve birleşti,
    *5.adım: tekrar sırala ve birleştir,
    *6.adım: sıralama bitene kadar birleştir.
    ```
    
2. Big-O gösterimini yazınız.
    ```
    O(nlogn)
    ```
