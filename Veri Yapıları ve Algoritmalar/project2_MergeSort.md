# Merge Sort Projesi

## Proje 2
**[16,21,11,8,12,22]** -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

***

## [16,21,11,8,12,22] (Merge Sort)
1. Diziyi ortasından ikiye ayırırız.
[16,21,11] ve [8,12,22]
2. Yeni oluşan dizileri de aynı şekilde ikiye ayırırız. Tek sayıda elemanlı dizileri birinde bir eleman fazla kalacak şekilde ayırırız.
[16], [21,11], [8], [12,22]
3. Aynı işlemi tüm elemanlar tek kalıncaya kadar tekrarlarız.
[16], [21], [11], [8], [12], [22]
4. Ardından birleştirme işlemleri başlar. Birleştirirken ikili gruplar büyüklüğüne bakarak sıralanır. Küçük sayılar sola, büyük sayılar sağa yazılır.
[16,21], [8,11], [12,22]  -> Burada [11] ve [8] birleşirken küçük olan [8] sola, büyük olan [11] sağa yazıldı.
5. Birleştirme ikili veya daha fazla elemanlı gruplar birleştirilirken her bir eleman birleşeceği grubun elemanlarıyla kıyaslanır.
Mesela, ikinci dizinin küçük elemanı diğer dizinin önce küçük sonra da büyük elemanıyla kıyaslanarak yeni elemanın dizinin başına mı, sonuna mı yoksa ortasına mı geleceği görülür.Aynı işlem diğer elemanlar için de yapılır.
[8,11,16,21], [12,22]
6. Yukarıdaki işlem tek bir dizi elde edilinceye kadar devam eder.
[8,11,12,16,21,22]

## Big-O Gösterimi
O(nlogn)
