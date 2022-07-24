# Patika.dev---Insertion-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

❓ 1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
❓ 2- Big-O gösterimini yazınız.
❓ 3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
❓ 4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
❓ 5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
<br/>
Cevaplar
## 1-
[22,27,16,2,18,6] - (n)

[2,27,16,22,18,6] - (n-1)

[2,6,16,22,18,27] - (n-2)

[2,6,16,18,22,27] - (n-3)

## 2- Big O Notation Gösterimi
Worst Case: O(n²) 

Average Case: O(n²)

Best Case: O(n) 

## 3- Time Complexity

Worst Case: O(n²) = n+(n-1)+(n-2)....+1 --> artan bir sırayla dizili olan elemanları azalan bir şekilde sort etme durumunda

Average Case: O(n²)

Best Case: O(n) --> Dizi halihazırda sıralı olduğu durumda

## 4-
Dizi sıralandıktan sonra -> [2,6,16,18,22,27]  ve 18 sayısı bu dizinin ortanca değeridir. Yani average case diyebiliriz.



## 5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[3,7,5,8,2,9,4,15,6] 
[3,5,7,8,2,9,4,15,6] 
[3,5,7,2,8,9,4,15,6] 
[3,5,2,7,8,9,4,15,6] 




www.patika.dev
