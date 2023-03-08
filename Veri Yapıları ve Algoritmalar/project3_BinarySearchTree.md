# Binary Search Tree Projesi

## Proje 3
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** -> dizisinin Binary-Search-Tree aşamalarını yazınız.

***

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] (dizisinin Binary-Search-Tree)
**root** 7'dir.

1. Sıradaki eleman: **5**
**7**'den küçük olduğu için sola yazılır.
  7
 /
5

2. Sıradaki eleman: **1**
**7**'den küçük olduğu için sola gider.
**5** ile kıyaslanır. Daha küçük olduğu için sola yazılır.
    7
   /
  5
 /
1

3. Sıradaki eleman: **8**
**7** ile kıyaslanır. Daha büyük olduğu için sağa yazılır.
    7
   / \
  5   8
 /
1

4. Sıradaki eleman: **3**
**7** ile kıyaslanır. Daha küçük olduğu için sola gider.
**5** ile kıyaslanır. Daha küçük olduğu için sola gider.
**1** ile kıyaslanır. Daha büyük olduğu için sağa yazılır.
    7
   / \
  5   8
 /
1 
 \
  3

5. Sıradaki eleman: **6**
**7** ile kıyaslanır. Daha küçük olduğu için sola gider.
**5** ile kıyaslanır. Daha büyük olduğu için sağa yazılır.
    7
   / \
  5   8
 / \
1   6
 \
  3

6. Sıradaki eleman: **0**
**7** ile kıyaslanır. Daha küçük olduğu için sola gider.
**5** ile kıyaslanır. Daha küçük olduğu için sola gider.
**1** ile kıyaslanır. Daha küçük olduğu için sola yazılır.
       7
      / \
     5   8
    / \
   1   6
 /  \
0    3

7. Sıradaki eleman: **9**
**7** ile kıyaslanır. Daha büyük olduğu için sağa gider.
**8** ile kıyaslanır. Daha büyük olduğu için sağa yazılır.
       7
      / \
     5   8
    / \   \
   1   6   9
 /  \
0    3

8. Sıradaki eleman: **4**
**7** ile kıyaslanır. Daha küçük olduğu için sola gider.
**5** ile kıyaslanır. Daha küçük olduğu için sola gider.
**1** ile kıyaslanır. Daha büyük olduğu için sağa gider.
**3** ile kıyaslanır. Daha büyük olduğu için sağa yazılır.
       7
      / \
     5   8
    / \   \
   1   6   9
 /  \
0    3
      \
       4

9. Sıradaki eleman: **2**
**7** ile kıyaslanır. Daha küçük olduğu için sola gider.
**5** ile kıyaslanır. Daha küçük olduğu için sola gider.
**1** ile kıyaslanır. Daha büyük olduğu için sağa gider.
**3** ile kıyaslanır. Daha küçük olduğu için sola yazılır.
       7
      / \
     5   8
    / \   \
   1   6   9
 /  \
0    3
   /  \
  2    4