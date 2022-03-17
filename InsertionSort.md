# Kodluyoruz Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
````
1- [22,27,16,2,18,6]
2- [2,27,16,22,18,6]
3- [2,6,16,22,18,27]
4- [2,6,16,18,22,27]
````
* Big-O gösterimini yazınız.

1. işlemi n tane
2. işlemi (n-1) tane .... n. işlemi 1 tane



bu şekilde 1 den n kadar sayıların toplamı şeklinde olur

(n * (n+1)) / 2 = (n^2+n) / 2 den dominat bileşen olan n^2 seçilir

Big-O Notation O(n^2) olur

* Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Worst case: Big-O Notationdan O(n^2) olur

Average case: de O(n^2) olur

ilk işlemimiz n tane olduğu için 
Best case: O(n) olur

*Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

4. işlemden sonra olduğu için Average case: de O(n^2) olur
