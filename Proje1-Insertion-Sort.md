# 1-INSERTION SORT PROJESİ

---

---

## **1)[22,27,16,2,18,6]**

---

---

- 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- 2. Big-O gösterimini yazınız.
- 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case:Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

## **_1.a) Verilen dizinin sort türüne göre aşamaları_**

---

1.  Dizinin insertion sort türüne göre adımları:

```
1. [22,27,16,2,18,6]
2. [2,27,16,22,18,6]
3. [2,6,16,22,18,27]
4. [2,6,16,18,22,27]
```

### Aşamalar şu şekilde olacaktır ;

## 1. Aşama

- En küçük eleman olan en baştaki sayıyla yer değiştirir. (En küçük sayı 2, En baştaki sayı 22)

```
1. [2,27,16,22,18,6]
```

## 2. Aşama

- En küçük sayıyı başa yerleştirdikten sonra, ikinci sıradaki en küçük sayı 2. sıradaki sayıyla yer değiştirir. (27 ve 6)

```
2. [2,6,16,22,18,27]
```

## 3. Aşama

- En son olarak devam eden sırada kalan en küçük sayı 4. sıradakiyle yer değiştirir.
  (18 ve 22)

```
3. [2,6,16,18,22,27]
```

## **_1.b) Big-O Gösterimi_**

---

**Worst Case:** O(n^2)

**Average Case:** O(n^2)

**Best Case:** O(n)

## **_1.c) Time Complexity_**

---

### **Worst Case:**

```
[27,22,18,16,6,2]
```

### **Average Case:**

```
[6,16,22,2,18,27]
```

### **Best Case:**

```
[2,6,16,18,22,27]
```

## **_1.d) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız._**

---

```
Sıralamanın ortasında bulunduğu için Average Case kapsamına grirer.
```

---

---

## **2. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

---

---

```
1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [2,3,5,7,8,9,4,15,6]
```
