# Insertion Sort Projesi

## Sorular:

[22,27,16,2,18,6] -> Insertion Sort

1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2- Big-O gösterimini yazınız.

3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız

5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Cevaplar:

1-  Başlangıç  => 1. Adım => 2. Adım => 3. Adım => 4. Adım

    [22,27,16,2,18,6] => [16,22,27,2,18,6] => [2,16,22,27,18,6] => [2,16,18,22,27,6] => [2,6,16,18,22,27] 

2- O(n^2)

3- Linear Search olarak arama yapılırsa: Average case: O(n/2), Worst case : O(n), Best case: O(1)

4- Sıralandıktan sonra 18 sayısı dizinin ortasında sayılacağından Average Case kapsamına girer.

5-  Başlangıç  => 1. Adım => 2. Adım => 3. Adım => 4. Adım

    [7,3,5,8,2,9,4,15,6] => [3,7,5,8,2,9,4,15,6] => [3,5,7,8,2,9,4,15,6] => [2,3,5,7,8,9,4,15,6] => [2,3,4,5,7,8,9,15,6]
