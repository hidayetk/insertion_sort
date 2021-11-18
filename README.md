Proje 1
[22,27,16,2,18,6] -> Insertion Sort

**Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

1.Elemanı Kontrol Ediyoruz.  
 [2,27,16,22,18,6]  
2.Elemanı Kontrol Ediyoruz.  
 [2,6,16,22,18,27]  
3.Elemanı Kontrol Ediyoruz.  
 [2,6,16,22,18,27]  
4.Elemanı Kontrol Ediyoruz.  
 [2,6,16,18,22,27]  
5.Elemanı Kontrol Ediyoruz.  
 [2,6,16,18,22,27]  

**Big-O gösterimini yazınız.**  
O(n^2)  
**Time Complexity:**  
- Average case: Aradığımız sayının ortada olması: O(n) -> O(6)  
- Worst case: Aradığımız sayının sonda olması: O(n^2) -> O(36)  
- Best case: Aradığımız sayının dizinin en başında olması: O(n^2) -> O(36)  
    
**Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**  

- Average case kapsamına girer

**[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**
1. [2,3,5,8,7,4,15,6]
2. [2,3,4,8,7,5,15,6]
3. [2,3,4,5,7,8,15,6]
4. [2,3,4,5,6,8,15,7]
