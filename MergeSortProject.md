# Merge Sort Project

[16,21,11,8,12,22] 

## 1) Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız.

[16,21,11,8,12,22]
<br>
[16,21,11] --------- [8,12,22]
<br>
[16] -- [21,11] --------- [8] -- [12,22]
<br>
[16] - [21] - [11] --------- [8] - [12] - [22]
<br>
[16,21] - [11] --------- [8,12] - [22]
<br>
[11,16,21] --------- [8,12,22]
<br>
[8,11,12,16,21,22]

## 2) Big-O gösterimini yazınız.

Her dizinin kendi içinde sıralanması O(n) notasyonu şeklinde gösterilir.
<br>
Merge sort algoritmasında baştan sona ortadan ikiye bölerek ilerliyoruz.
<br>
Bu yüzden 2^x = n olursa, x = logn olur. logn işlem sayımız. => O(nlogn)
