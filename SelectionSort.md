# Proje 1 Selection Sort

## [22,27,16,2,18,6] --> insertion sort

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki caselerden hangisinin kapsamına girer?   
   * Average case: Aranılan sayı ortadaysa
   * Worst case: Aranılan sayı sondaysa
   * Best case: Aranılan sayı en baştaysa

   ## CEVAPLAR

   ### 1. [22,27,16,2,18,6] en küçük sayı seçilir ve en baştakiyle yeri değiştirilir. Bu işlem diğer sayılarada yapılır
   * * [22,27,16,2,18,6] n
   * * [2,27,16,22,18,6] n-1
   * * [2,6,16,22,18,27] n-2
   * * [2,6,16,18,22,27] n-3

   ### 2. Big-O gösterimi: n+(n-1)+(n-2)+(n-3)....+1= n.(n+1)/2=> baskın ifade n^2 olduğu için Big-O=>(n^2)

   ### 3. Dizi sıralanınca 18 sayısı  Average Case olur


## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1. [7,3,5,8,2,9,4,15,6] n
2. [2,3,5,8,7,9,4,15,6] n-1
3. [2,3,4,8,7,9,5,15,6] n-2
4. [2,3,4,5,7,9,8,15,6] n-3 


