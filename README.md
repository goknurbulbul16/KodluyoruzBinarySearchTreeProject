# Kodluyoruz Binary Search Tree Project

## Proje 3:  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

### Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

-----------
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**   root değerini 7 olarak seçiyoruz.


        7               root 7'dir. Solunda 5 bulunur. ( 7 > 5 )
       /
      5
----------------------------

            7               5'in solunda da 1 bulunur. ( 5 > 1 )
           /
          5
         /
        1 
-------------------------------

             7               7'nin sağında 8 bulunur. ( 7 < 8 )
            / \
           5   8
          /
         1 

---------------------------


             7               1'in sağında 3 bulunur. ( 3 > 1 )
            / \
           5   8
          /
         1
          \
           3 

------------------------------------


             7               5'in sağında 6 bulunur. ( 5 < 6 )
            / \
           5   8
          / \
         1   6
          \
           3 
 
--------------------------------------


             7               1'in solunda 0 bulunur. ( 1 > 0 )
            / \
           5   8
          / \
         1   6
        / \
       0   3 
 ---------------------------------------

             7               8'in sağında 9 bulunur. ( 8 < 9 )
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3 
--------------------------------------

             7               3'ün sağında 4 bulunur. ( 3 < 4 )
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
            \
             4 
------------------------------------


             7               3'ün solunda 2 bulunur. ( 3 > 2 )
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
          / \
         2   4 
-----------------------------------------

[Kodluyoruz](https://kodluyoruz.org) kapsamında Veri Yapıları ve Algoritma Eğitimi 3. Projesi

![kodluyourz](/img/kodluyoruz.png)

---------------------------------------------------------

[MIT](https://choosealicense.com/licenses/mit/)
 




