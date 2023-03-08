# Selection Sort Projesi

## Proje 1
**[22,27,16,2,18,6]** -> Insertion Sort

>Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

>Big-O gösterimini yazınız.

>Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
  1. Average case: Aradığımız sayının ortada olması
  2. Worst case: Aradığımız sayının sonda olması
  3. Best case: Aradığımız sayının dizinin en başında olması.

***

## [22,27,16,2,18,6] (Insertion Sort)
1. Dizinin ikinci elemanı [27] ilk elemanla [22] kıyaslanarak hangisi büyük bakılır. Yani ikinci eleman anahtar görevi görür. İkisi arasındaki mevcut sıralama yanlışsa küçük olanla büyük olan yer değiştirir. Yani küçük eleman bir sola, büyük eleman bir sağa kayar.
[22,27,16,2,18,6]
2. Üçüncü elemana [16] geçilir. 
  * Bu eleman ikinci elemandan [27] küçük olduğu için yer değiştirirler. 
  * Ardından sıradaki elemanla kıyasalanır [22], bundan da küçük olduğu için en başa geçer.
[16,22,27,2,18,6]
3. Dördüncü elemana [2] geçilir. 
  * Bu eleman üçüncü elemandan [27] küçük olduğu için yer değiştirirler. 
  * Ardından sıradaki elemanla kıyasalanır [22], bundan da küçük olduğu için yine yer değiştirirler.
  * Son olarak en baştaki elemanla kıyasalanır [16], bundan da küçük olduğu için bununla da yer değiştirirler.
[2,16,22,27,18,6]
4. Beşinci elemana [18] geçilir. 
  * Önce dördüncü elemanla [27] kıyaslanır, bundan küçük olduğu için yer değiştirirler.
  * Sonra üçüncü elemanla [22] kıyaslanır, bundan da küçük olduğu için yine yer değiştirir. 
  * Ardından sıradaki elemanla kıyasalanır [16], bundan büyük olduğu için yer değiştirmezler.
[2,16,18,22,27,6]
5. Son elemana [6] geçilir. 
  * Önce beşinci elemanla [27] kıyaslanır, bundan küçük olduğu için yer değiştirirler.
  * Sonra dördüncü elemanla [22] kıyaslanır, bundan da küçük olduğu için yine yer değiştirir.
  * Daha sonra üçüncü elemanla [18] kıyaslanır, bundan da küçük olduğu için bir kez daha yer değiştirir. 
  * Ardından ikinci elemanla kıyasalanır [16], bundan da olduğu için yine yer değiştirir.
  * Son olarak ilk elemanla kıyasalanır [2], bundan daha büyük olduğu için yer değiştirmezler ve işlem sona erer.
[2,6,16,18,22,27]

## Big-O Gösterimi
O(n^2)

## Time Compexity (18 için)
18 orta sıralarda bir sayı olduğu için **Average case** olarak kabul edilir.