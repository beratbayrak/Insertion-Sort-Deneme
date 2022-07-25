# Insertion-Sort-Deneme
[22, 27, 16, 2, 18, 6] -> Insertion Sort 
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1. Adım: [2,| 27, 16, 22, 18, 6]
2. Adım: [2, 6,| 16, 22, 18, 27]
3. Adım: [2, 6, 16,| 22, 18, 27]
4. Adım: [2, 6, 16, 18,| 22, 27]
Sonuç: [2, 6, 16, 18, 22, 27]

Big-O gösterimini yazınız.

Insertion Sort algoritmasında küçükten büyüğe doğru sıralama yapılırken ilk işlemde n kadar işlem yapılmakta ve her işlemde bir işlem azaltılarak (n-1) sonuca varılmaktadır. Buradaki örnekte:
n+(n-1)+(n-2)+(n-3)+….1= kadar işlemde sonuca varmaktayız. Bu ise bize n’ sayısına kadar olan  sayıların toplamını vermektedir. Bu işlemin formülü ise  (n(n+1))/2  yani (n^2+n)/2  olmakla Big-O gösterimine göre dominant karakter alındığında buradaki dizinin Big-O gösterimi= O(n2) olmaktadır.

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Best Case: [2, 6, 16, 18, 22, 27]

Worst Case: [27, 22, 18, 16, 6, 2]

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizi: [2, 6, 16, 18, 22, 27]
Dizi sıralandıktan sonra 18 sayısı ortada yer almakla average case kapsamına girmektedir.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
Dizi: [7,3,5,8,2,9,4,15,6]
1. Adım: [2,|3, 5, 8, 7, 9, 4, 15, 6]
2. Adım: [2, 3,| 5, 8, 7, 9, 4, 15, 6]
3. Adım: [2, 3, 4,| 8, 7, 9, 5, 15, 6]
4. Adım: [2, 3, 4, 5, | 7, 9, 8, 15, 6]
