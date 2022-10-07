# Veri-Yapilari-ve-Algoritmalar
[Patika](https://app.patika.dev), Veri Yapıları ve Algoritmalar kursu projelerinden Merge Sort ve Binary Search Tree projesi.

[Insertion Sort](https://github.com/AyberkOzkan/Insertion-Sort-Projesi)

[Binary Search Tree](Binary_Search_Tree.md)

<br/>

# **Merge Sort**

## **Proje İsterleri** 

```[16,21,11,8,12,22]``` --> **Merge Sort**

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.


## Aşamalar:

|  |  |  |  |  |  |  |  |  |  |  |  |
|- |- |- |- |- |- |- |- |- |- |- |- |
|  |  |  |16|21|11|8 |12|22|  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |16|21|11|  |  |8 |12|22|  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |
|  |16|21|  |11|  |  |8 |  |12|22|  |
|  |  |  |  |  |  |  |  |  |  |  |  |
|16|  |21|  |11|  |  |8 |  |12|  |22|
|  |  |  |  |  |  |  |  |  |  |  |  |
|- |- |- |- |- |- |- |- |- |- |- |- |
|16|  |21|  |11|  |  |8 |  |12|  |22|
|  |  |  |  |  |  |  |  |  |  |  |  |
|  |16|21|  |11|  |  |8 |  |12|22|  |
|  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |11|16|21|  |  |8 |12|22|  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |8 |11|12|16|21|22|  |  |  |

<br/>

---