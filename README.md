Merge Sort'da yapı elemanları tek kalana kadar ikiye bölünür, sıralama yaparak tekrar birleştirilir, rekürsif bir sıralamadır.

[16,21,11,8,12,22] Diziyi 16,21,11 ve 8,12,22 olarak 2 parçaya ayırıyoruz.
2 Ayırma işlemini devam ettiriyoruz; 16,21 - 11 8,12 -22

İkilileri kendi arasında sıralıyoruz (burada sıralanmış) ve tekrar diğer parçalarla sıralayarak birleştiriyoruz. 11,16,21 8,12,22

Kalan iki diziyi de sıralayarak birleşiriyoruz. [8,11,12,16,21,22]

Merge sort rekürsiftir, işlem uzunluğu fazladır. Her satırda array ikiye bölündüğü için 2**x=n ==> yalnız n tane işlem olduğundan; O(n*logn) olur.