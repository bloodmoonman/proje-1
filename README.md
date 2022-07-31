# patika.dev

[22,27,16,2,18,6] -> Insertion Sort

    1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    2-Big-O gösterimini yazınız.
    3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının 
    dizinin en başında olması.
    4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1- 

[22,27,16,2,18,6] n
[16,22,27,2,18,6] n-1
[2,16,22,27,18,6] n-2
[2,16,18,22,27,6] n-3
[2,6,16,18,22,27] 1


## 2- 

0+1+2+3+4…..+n-1 = [n*(n-1)]/2 : n^2


## 3- 


best case: dizinin küçükten büyüğe sıralı olması durumudur, O(n)
worst case: büyükten küçüğe sıralı olmasıdır, O(n^2)
average case: O(n^2)


## 4-

18 sayısı, average case kapsamındadır.



## [7,3,5,8,2,9,4,15,6]
        
        
    [3,7,5,8,2,9,4,15,6]     
    [3,5,7,8,2,9,4,15,6]
    [2,3,5,7,8,9,4,15,6]        
    [2,3,4,5,7,8,9,15,6]

