# Insertion-Sort-Project-Patika.dev

## [22,27,16,2,18,6] -> Insertion Sort

## 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

  [~~2~~,27,16,22,18,6] => (n)
  <br>
  [~~2,6~~,16,22,18,27] => (n-1) 
  <br>
  [~~2,6,16~~,22,18,27] => (n-2) 
  <br>
  [~~2,6,16,18~~,22,27] => (n-3)
  <br>
  [~~2,6,16,18,22~~,27] => (n-4)
  <br>
  [2,6,16,18,22,27] => 1

## 2) Big-O gösterimini yazınız.

(n) + (n-1) + (n-2) + ... + 1 = [n * (n+1)] / 2 = (n^2 + n) / 2
<br>
Big-O notation => O(n^2)

## 3) Time Complexity

Average case: The number we are looking for is in the middle.
<br>
Worst case: The number we're looking for is at the end.
<br>
Best case: The number we are looking for is in the first place.

## 4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average case.

## 5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[~~2~~,3,5,8,7,9,4,15,6]
<br>
[~~2,3~~,5,8,7,9,4,15,6]
<br>
[~~2,3,4~~,8,7,9,5,15,6]
<br>
[~~2,3,4,5~~,7,9,8,15,6]
