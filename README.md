# binary-search-tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

root:7 
5: root'un solundadır çünkü roottan küçüktür.
1: 5'in solundadır çünkü roottan ve 5'ten küçüktür.
8: root'un sağındadır çünkü roottan büyüktür.
3: 1'in sağındadır çünkü roottan 5'ten ve 3'ten küçüktür.
6: 5'in sağındadır.
0: 1'in solundadır.
9: 8'in sağındadır.
4: 3'ün sağındadır.
2: 3'ün solundadır.

```
.         7
         / \
        5   8
       / \    \
      1   6    9
     / \
    0   3
       / \
      2   4
```
