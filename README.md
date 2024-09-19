# BinarySearchTree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Dizinin ilk elemanı (7) kök düğüm olarak alınır.
- İkinci eleman (5) 7'den küçük olduğu için 7'nin soluna eklenir.
- Üçüncü eleman (1) 7'den ve 5'ten küçük olduğu için 5'in soluna eklenir.
- Dördüncü eleman (8) 7'den büyük olduğu için 7'nin sağına eklenir.
- Beşinci eleman (3) 7'den ve 5'den küçük, ama 1'den büyük olduğu için 1'in sağına eklenir.
- Altıncı eleman (6) 7'den küçük ama 5'den büyük olduğu için 5'in sağına eklenir.
- Yedinci eleman (0) 7,5 ve 1'den küçük olduğu için 1'in soluna eklenir.
- Sekizinci eleman (9) 7'den büyük olduğu için 8'in sağına eklenir.
- Dokuzuncu eleman (4) 7 ve 5'den küçük, 1 ve 3'den büyük olduğu için 3'ün sağına eklenir.
- Onuncu eleman (2) 7 ve 5'den küçük, 1'den büyük ve 3'ten küçük olduğu için 3'ün soluna eklenir.
```

Sonuç olarak, verilen diziyi kullanarak oluşturduğumuz Binary Search Tree (BST) şu şekildedir:

      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```

**Hiyerarşik Yapı:**
- Root: 7
    - Sağ Düğüm: 8
        - Sağ Düğüm: 9
    - Sol Düğüm: 5
        - Sağ Düğüm: 6
        - Sol Düğüm: 1
            - Sağ Düğüm: 3
                - Sağ Düğüm: 4
                - Sol Düğüm: 2
            - Sol Düğüm: 0