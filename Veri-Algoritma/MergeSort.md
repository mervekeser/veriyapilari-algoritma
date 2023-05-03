# Proje 2 Merge Sort

## [16,21,11,8,12,22] --> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamlarını yazınız
2. Big-O gösterimini yazınız.

## Cevaplar
     1.   |16|21|11|8|12|22| ortadan bölüyoruz

        |16|21|11|   |8|12|22| tekrar bölüyoruz

     |16|21| |11|     |8| |12|22| bütün kutular tek kutu olana kadar bölüyoruz. Daha sonra küçükten büyüğe doğru sıralayıp son aşamada birleştiriyoruz

     16  21  11          8  12  22

    |11|16|21|        |8|12|22|     sol ve sağ taraflardaki kutuların 1.kutularındaki küçük sayılara göre sıralama yaparak birleştiriyoruz.

      |8|11|12|16|21|22|


 2. Big-O gösterimi--> her aşamada 2'ye bölerek işlem sayısını azaltmış olduk.
 2^x=n --> x=logn       Son aşamada küçükten büyüğe doğru sıralama işleminde n kadar eleman olduğu için time complexity O(n) olur. Baştan sona bütün işlemlerin Big-O=O(nlogn) olur.
