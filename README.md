# PatikaDev - Sorting Types
[Patika Dev](www.patika.dev) - Java / Insertion Sort Projesi
### Titles
* [Insertion Sort](https://github.com/REFUPANKER/PatikaDev_SortingTypes#insertion-sort)
* [Merge Sort](https://github.com/REFUPANKER/PatikaDev_SortingTypes#merge-sort)
---
## Insertion Sort
```java
[22,27,16,2,18,6]
```
1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```Java
 1| [16,22,27,2,18,6]
 2| [2,16,22,27,18,6]
 3| [2,16,18,22,27,6]
 4| [2,6,16,18,22,27]
 5| [     Sorted    ]
```
2- Big-O gösterimini yazınız.
> O(  N^2 ) -> N:6 -> O(6^2) -> O(36)

#### Time Complexity
* Average case  : Aradığımız sayının ortada olması
* Worst case    : Aradığımız sayının sonda olması 
* Best case     : Aradığımız sayının dizinin en başında olması
3- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
> Average Case
### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```java
1|-> 3,7,5,8,2,9,4,15,6
2|-> 3,5,7,8,2,9,4,15,6
3|-> 2,3,5,7,8,9,4,15,6
4|-> 2,3,4,5,7,8,9,15,6
```
## Merge Sort
```java
[16,21,11,8,12,22]
```
1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
<br>
<img width="400" height="300" algin="left" src="https://user-images.githubusercontent.com/68808212/187883638-5d0316b4-7349-4427-ab4f-8984066f85f1.png"/>
<br>
2- Big-O gösterimini yazınız.
> O(nLogn) -> O(6log6) -> O(4.6689075023)
---
### Veri Yapıları ve Algoritmalar [ Insertion ve Merge sort Projeleri ]- www.patika.dev
