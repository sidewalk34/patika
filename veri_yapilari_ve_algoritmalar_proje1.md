# patika
Patika.dev Çalışmalarını içerir
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6] n
[2,27,16,22,18,6] n-1
[2,6,16,22,18,27] n-2
[2,6,16,18,22,27] 1

2) Big-O gösterimini yazınız.
n + (n-1) + (n-2) + 1 = n(n+1)/2 
Big O (n^2)

3) Time Complexity
Average Case: O (n) = O(6)
Worst Case: O (n^2) = O(36)
Best Case: O (n^2) = O(36)

4) 18 Case. Avarage Case
----
Insertion Sort’a göre ilk 4 aşama
[7,3,5,8,2,9,4,15,6] 1. aşama
[2,3,5,8,7,9,4,15,6] 2. aşama
[2,3,4,8,7,9,5,15,6] 3. aşama
[2,3,4,5,7,9,8,15,6] 4. aşama
