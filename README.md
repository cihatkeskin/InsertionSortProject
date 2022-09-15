# Insertion Sort Projesi

```markdown
[22,27,16,2,18,6] -> Insertion Sort

> Soru 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```

```markdown
1. [22,16,27,2,18,6]


2. [16,22,27,2,18,6]


3. [16,22,2,27,18,6]


4. [16,2,22,27,18,6]


5. [2,16,22,27,18,6]


6. [2,16,22,18,27,6]


7. [2,16,18,22,27,6]


8. [2,16,18,22,6,27]


9. [2,16,18,6,22,27]


10. [2,16,6,18,22,27]


11. [2,6,16,18,22,27]
```

---

```markdown
> Soru 2) Big-O gösterimini yazınız.
```

```markdown
İlk aşamada dizideki her elemanı kontrol ettim yani "n" tane işlem yapmış oldum.

Sonraki aşamada ise sadece 16 sayısını sıralamıştım diğer sayılara bakacağım yani 
"n-1" tane işlem yapmış olacağım. 

16 ile 22 yi sıraladım diğer sayılara bakarak "n-2" tane işlem yapmış oldum.

=> n + (n-1) + (n-2) + ... + 1 
=> n . (n+1) / 2 
=> (n^2) + n / 2 

burada domine eden fonksiyonu alıyoruz.

Sonuç olarak Big-O gösterimi O(n^2) dir.
```

---


>## **Hatırlatma !**
> ### *Time Complexity*
> - Average case: Aradığımız sayının ortada olması.
> - Worst case: Aradığımız sayının sonda olması.
> - Best case: Aradığımız sayının dizinin en başında olması.


---

```markdown
> Soru 4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```

```
Aradığımız sayı ortada olduğu için "Average Case" kapsamına girer.
```

---

```markdown
> [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
```markdown
1. [3,7,5,8,2,9,4,15,6]

2. [3,5,7,8,2,9,4,15,6]

3. [3,5,7,2,8,9,4,15,6]

4. [3,5,2,7,8,9,4,15,6]
```

