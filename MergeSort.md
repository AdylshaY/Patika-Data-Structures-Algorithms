# Merge Sort Projesi

## Sorular

  [16,21,11,8,12,22] => Merge Sort

1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2- Big-O gösterimini yazınız.

## Cevaplar

Cevap 1:
1. Adım: 
 
         [16,21,11,8,12,22] => [16,21,11] , [8,12,22]
2. Adım: 

         [16,21,11] => [16,21] , [11] 

         [8,12,22] => [8,12] , [22]
3. Adım: 

         [16,21] => [16] , [21]

         [8,12] => [8] , [12]
4. Adım: 

         [16] , [21] , [11] => [16,21] , [11] 

         [8] , [12] , [22] => [8,12] , [22]
5. Adım: 

         [16,21] , [11]  => [11,16,21]

         [8,12] , [22] => [8,12,22]
6. Adım: 

       [11,16,21] , [8,12,22] => [8,11,12,16,21,22]
       
Cevap 2:

 O(nlogn)
