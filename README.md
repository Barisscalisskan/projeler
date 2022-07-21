# Kodluyoruz Frontend Başlangıç Eğitimi Veri Yapıları ve Algoritmalar Bölümü Projeleri 
## İçinde Bulunanlar
 - Insertion Sort Projesi 
- Merge Sort Projesi 
- Binary Search Tree Projesi

[Patika.dev](https://www.patika.dev  
[Patika.Dev](https://app.patika.dev/)


# Proje 1 - Insertion Sort ---  [22,27,16,2,18,6]  ## 1.) Yukarı verilen dizinin sort türüne göre aşamaları :
 - [22,27,16,2,18,6] -> n - [2,27,16,22,18,6] ->(n-1)
 - [2,6,16,22,18,27] ->(n-2) - [2,6,16,18,22,27] ->(n-3) 
●● 2.) Big-O gösterimi : 
   - Big-O : O(n²) 
●● 3.) Time Complexity Best case: Aradığımız sayının dizinin en başında olmasıdır. 
●●● Best case : O(n) Average case: Aradığımız sayının ortada olması. 
●●● Average case : O(n²) Worst case: Aradığımız sayının sonda olmasıdır. 
●●● Worst case : O(n²) 
●● 4.) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. 
☆18 sayısı ortalarda olduğu için Average case kapsamında olur. 
●●● 5.) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız. 
- [2,3,5,8,7,9,4,15,6] 
- [2,3,4,8,7,9,5,15,6] 
- [2,3,4,5,7,9,8,15,6] 
- [2,3,4,5,6,9,8,15,7]



## Proje 2 - Merge Sort ---  [16,21,11,8,12,22]  ### 1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız. [16,21,11,8,12,22] [16,21,11] [8,12,22] [16] [21,11] [8,12] [22] [16] [21] [11] [8] [12] [22] [16] [11,21] [8,12] [22] [11,16,21] [8,12,22] [8,11,12,16,21,22] ### 2.Big-O gösterimini yazınız. O(nlog(n))





## Proje 3 - Binary Search Tree ---  [7,5,1,8,3,6,0,9,4,2] 
 
### Yukarıda verilen dizinin Binary Search Tree aşamalarını yazınız. root = 7 ___[7]___ | | _[5]_ [8]__ | | | _[1]_ [6] [9] | | [0]__[3]_ | | [2] [4] ### Açıklama - Root 7'dir. 
☆ 5, 7'den küçük olduğu için root'un solunda bulunur. 
☆  1, 7'den ve 5'ten küçük olduğu için 5'in solunda bulunur. 
☆  8, 7'den büyük olduğu için 7'nin sağında bulunur. 
☆  3, 7'den ve 5'ten küçük; 1'den büyük olduğu için 1'in sağında bulunur. 
☆  6, 7'den küçük 5'den büyük olduğu için 5'in sağında bulunur.
 ☆  0, hepsinden küçük olduğu için kendinden önceki en küçük sayı olan 1'in solunda bulunur. 
☆ 9, hepsinden büyük olduğu için kendinden önceki en büyük sayı olan 8'in sağında bulunur. 
☆ 4, 7 ve 5'ten küçük; 1 ve 3'ten büyük olduğu için 3'ün sağında bulunur. 
☆ 2, 7 ve 5'ten küçük; 1'den büyük ve 3'ten küçük olduğu için 3'ün solunda bulunur.
