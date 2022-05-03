# Proje 1
[22,27,16,2,18,6] -> Insertion Sort
1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
---
---
##Cevap 
**Insert aşamaları** --                               **Big-O Notation**
[22,27,16,2,18,6]                                >  n         
[2,22,27,16,18,6]                                >  (n-1)
[2,6,22,27,16,18]                                >  (n-2)
[2,6,16,22,27,18]                                   ...
[2,6,16,18,22,27]                                   
[2,6,16,18,22,27]
[2,6,16,18,22,27]                                >  +1     
                             
**insertion küçükten büyüğe tamamlandı**         


***2-liste 6 elemanlı olduğu için n=6 ve Big-O (n * (n+1)/2) 'den n^2 değeri baz alınır yani O(36)'dır***

***3-Insertion sort için Worst ve Average case  O(n²)'dir. Yani, buradaki liste için O(36)'dır.Listeyi sıralamak için geçen süre, listedeki eleman sayısının karesiyle orantılıdır.
Best case ise O(n)'dir, yani bu liste zaten küçükten büyüğe sıralı bir halde verilmiş olsaydı; her elemanın üzerinden sadece bir kere geçeceğinden best case n'dir, dolayısıyla O(6)'dır.***

***4-18 sayısı liste sıralandıktan sonra ortadaki iki sayıdan biri olduğu için average case kapsamına girer***

***[7,3,5,8,2,9,4,15,6] insertion sorta göre ilk dört adımı;
1.step (2 sayısı başa gelir)        [2,7,3,5,8,9,4,15,6]
2.step (3 sayısı 2. sıraya gelir)   [2,3,7,5,8,9,4,15,6]
3.step (4 sayısı 3. sıraya gelir)   [2,3,4,7,5,8,9,15,6] 
4.step (5 sayısı 4. sıraya gelir)   [2,3,4,5,7,8,9,15,6]***

---













