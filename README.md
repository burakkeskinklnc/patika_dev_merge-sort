# [Patika.dev](https://www.patika.dev/tr) Veri yapıları ve algoritmalar dersi, merge sort projesi;

### [16,21,11,8,12,22] -> Merge Sort
- 1-) Yukarıdaki dizinin sort türüne göre aşamaları yazınız.
-  2-) Big-O gösterimini yazınız.
### 1-) Cevap;
- 16 - 21 - 11               --------              8 - 12 - 22
--  16 - 21  -----11------------ 8 - 12-----22
--- 16 - 21  -----11------------8  -----12 -----22
--- -- --- --  16 -21  -----11------------8-12 -----22
--- -- --- -- -- -- 11-16-21------------8-12-22
[8-11-12-16-21-22] dizimizin son hali.
### 2-) Cevap;
O(n.logn)
