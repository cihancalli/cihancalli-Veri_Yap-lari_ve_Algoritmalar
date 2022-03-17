# Kodluyoruz Merge Sort Projesi


[16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
````
1- [16,21,11,8,12,22]
2- [16,21,11] [8,12,22]
3- [16,21] [11] [8,12] [22]
4- [16] [21] [11] [8] [12] [22]

5- [16,21] [8,11] [12,22]
6- [8,11,16,21] [12,22]
7-[8,11,12,21,22]
````
*Big-O gösterimini yazınız.

ilk işlem n tane 
ikinci işlem n/2 tane
üçüncü işlem n/4 tane
x. işlem 1 tane

2^x = n tane işlem ise

Big-O Natation = O(logn) olur
