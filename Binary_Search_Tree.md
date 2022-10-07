# **Binary Search Tree**


--> [Patika](https://app.patika.dev)

--> [Insertion Sort](https://github.com/AyberkOzkan/Insertion-Sort-Projesi)

--> [Merge Sort](Merge_Sort.md)

## **Proje İsterleri** 


```[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]``` dizisinin **Binary-Search-Tree** aşamalarını yazınız.

> Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


## **Aşamalar:**

```[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]```

    root = 7

    Her sayıyı tek tek root sayımızdan yani 7'den küçük olanları sola, büyük olanları ise sağa ayıralım.

<br/>

<center>

![Tree](Tree.gif)


<br/>



|  |  |     |  |  |  |  |  |  |  |  |
|--|--|-    |- |- |- |- |- |- |- |- |
|  |  |     |  |  |  | 7|  |  |  |  |  
|  |  |     |  |  | /|  |\ |  |  |  | 
|  |  |     |  | 5|  |  |  |8 |  |  | 
|  |  |     | /|  |\ |  |  |  |\ |  | 
|  |  | 1   |  |  |  |6 |  |  |  | 9|
|  | /|     |\ |  |  |  |  |  |  |  |
| 0|  |     |  | 3|  |  |  |  |  |  |
|  |  |     | /|  |\ |  |  |  |  |  |
|  |  |2    |  |  |  |4 |  |  |  |  |
|  |  |     |  |  |  |  |  |  |  |  |


</center>