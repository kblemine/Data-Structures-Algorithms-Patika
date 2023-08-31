# Data-Structures-Algorithms-Patika
Repository for Data Structures and Algorithms course assignments and implementations offered by Patika

# Proje 1: Insertion Sort

* [22,27,16,2,18,6] -> Insertion Sort

    Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
```
    1. Adım : [22, 27, 16, 2, 18, 6] (27 yerleştirilir)
    2. Adım : [16, 22, 27, 2, 18, 6] (16 yerleştirilir)
    3. Adım : [2, 16, 22, 27, 18, 6] (2 yerleştirilir)
    4. Adım : [2, 16, 18, 22, 27, 6] (18 yerleştirilir)
    5. Adım : [2, 6, 16, 18, 22, 27] (6 yerleştirilir)    
```
* Big-O gösterimini yazınız.
```
    n+(n-1)+(n-2)+(n-3)+(n-4)+1= (n(n+1))/2= n^2 Big-O = n^2
```
* Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
```
    #### Cevap: Average case
```
* [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
    1. Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] 
    2. Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] 
    3. Adım: [2, 3, 4, 8, 7, 9, 5, 15, 6] 
    4. Adım: [2, 3, 4, 5, 7, 9, 8, 15, 6] 
```

# Proje 2: Merge Sort

* [16,21,11,8,12,22] -> Merge Sort

    + Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    + Big-O gösterimini yazınız.

```markdown
1. Adım:             [16,21,11]          [8,12,22]

2. Adım:           [16,21]   [11]       [8,12]   [22]

3. Adım:        [16]   [21]   [11]    [8]   [12]   [22]

4. Adım:         [16,21]   [11]        [8,12]   [22]     

5. Adım:            [11,16,21]            [8,12,22]

6. Adım:                 [8,11,12,16,21,22]
```

```
Time Complexity: O(nlogn)
```
