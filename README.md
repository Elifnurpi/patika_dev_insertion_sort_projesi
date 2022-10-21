[Patika.dev](https://www.patika.dev/tr) 

   Proje 1 [22,27,16,2,18,6] -> Insertion Sort
   
   1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
            [22, 27, 16, 2, 18, 6] (başlangıç)
            [2, 27, 16, 22, 18, 6] (2 ve 22 yer değiştirdi)
            [2, 6, 16, 22, 18, 27] (6 ve 27 yer değiştirdi)
            [2, 6, 16, 18, 22, 27] (18 ve 22 yer değiştirdi)
            
   2) Big-O gösterimini yazınız.
   
   Verilen dizinin en küçük ifadesini bulmak için n tane işlem yapıyoruz
   En küçük solda sabit kalıyor. ardından (n-1) tane ifade arasında en küçüğü bulmaya çalışıyoruz
   Bu sıralama işlemi en büyüğü en sağa yerleştirene kadar devam ediyor
   n+ (n-1)+ (n-2)....+1 = 1'den n'e kadar olan sayıların toplamı = [n*(n+1)]/2
   [n*(n+1)]/2 = (n^2+ n)/2 olur
   Big-O gösteriminde domine değeri alıyoruz, bu nedenle;
    - O(n^2)
    
   3) Time Complexity: 
   
   Average case: Aradığımız sayının ortada olması,
   Worst case: Aradığımız sayının sonda olması, 
   Best case: Aradığımız sayının dizinin en başında olması.
   
   4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
   
   18 sayısı verilen dizinin sonunda veya başında olmadığından dolayı Average case kapsamında değerlendirebiliriz. 
   Sonuç olarak Time Complexity: Average case'dir.
   
   5)  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
   
       [7, 3, 5, 8, 2, 9, 4, 15, 6] (başlangıç)
       [2, 3, 5, 8, 7, 9, 4, 15, 6] (2 ve 7 yer değiştirdi)
       [2, 3, 4, 8, 7, 9, 5, 15, 6] (4 ve 5 yer değiştirdi)
       [2, 3, 4, 5, 7, 9, 8, 15, 6] (8 ve 5 yer değiştirdi)
       [2, 3, 4, 5, 6, 9, 8, 15, 7] (7 ve 6 yer değiştirdi)
       [2, 3, 4, 5, 6, 7, 8, 15, 9] (9 ve 7 yer değiştirdi)
       [2, 3, 4, 5, 6, 7, 8, 9, 15] (9 ve 15 yer değiştirdi)
