## Soru 1
[16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. 
## Cevap 1

 <li>[16 21 11]    [8 12 22]  -> 3 erli gruba ayıyoruz
 <li>[16] - [21 11]<-->[8 12] - [ 22]
 <li>[16]<-->[21] - [11]<-->[8]-[12]<-->[22]   
 <li>[11 16 21]   [8 12 22 ]
 <li>[8 11 12 16 21 22]
 
## Soru 2
Big-O gösterimini yazınız.
## Cevap 2
 2^x=n
 x=logn 
0(n) Her Bölme İşlemi 
 Big-O = O(nlogn)
