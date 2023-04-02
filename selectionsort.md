[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


[22,27,16,2,18,6]
[2,27,16,22,18,6] --> 22 ve 2 yer degistirdi
[2,6,16,22,18,27] --> 27 ve 6 yer degistirdi.
[2,6,16,22,18,27] --> bu adimda herhangi bir degisiklik yapilmadi.
[2,6,16,18,22,27] --> 22 ve 18 yer degistirdi.
[2,6,16,18,22,27] --> bu adimda herhangi bir degisiklik yapilmadi.



Big-O gösterimini yazınız.
Insertion sort'un Big-O notasyonu O(n^2)'dir.


Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması (+) --> [2, 6, 16, 18, 22, 27] --> dizi siralandiktan sonra 18 sayisi dizinin ortasında kaldigi icin average case kapsamina girer.
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


-------------------------------------------------------------------------------

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6] --> 7 ve 2 yer degistirdi.
[2,3,5,8,7,9,4,15,6] --> 2'den sonra en kucuk deger 3 oldugu icin bu adimda herhangi bir degisiklik yapilmadi.
[2,3,4,8,7,9,5,15,6] --> 5 ve 4 yer degistirdi.
[2,3,4,5,6,9,8,15,7] --> 7 ve 6 yer degistirdi.
[2,3,4,5,6,7,8,15,9] --> 9 ve 7 yer degistirdi.
[2,3,4,5,6,7,8,15,9] --> 7'den sonra en kucuk deger 8 oldugu icin bu adimda herhangi bir degisiklik yapilmadi.
[2,3,4,5,6,7,8,9,15] --> 15 ve 9 yer degistirdi.
