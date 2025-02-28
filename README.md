# Patika.dev_Algoritmalar_Projeler

Bu README dosyasında, Patika.dev'deki Veri Yapıları ve Algoritmalar eğitimi kapsamında tamamladığım projeler bulunmaktadır.  

Proje 1: Insertion Sort  
Proje 2: Merge Sort  
Proje 3: Binar Search Tree

# Proje 1: Insertion Sort

**[22,27,16,2,18,6]** -> Insertion Sort

### Soru 1: Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
**Insertion Sort Aşamaları;**  
[22,27,16,2,18,6]  
[16,22,27,2,18,6]  
[2,16,22,27,18,6]  
[2,16,18,22,27,6]  
[2,6,16,18,22,27]  

### Soru 2: Dizinin Big-O gösterimini yazınız.
•	Best Case: O(n) — Sıralıysa, elemanlar sadece bir kez kontrol edilir.  
•	Average Case: O(n²)  
•	Worst Case: O(n²) — Tersten sıralıysa, her eleman için sıralı kısmın tamamını kontrol etmek gerekir.  

### Soru 3: Time Complexity, Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?  
Dizi sıralandıktan sonra 18 sayısı dizinin ortalarına gelmiş oluyor bu nedenle Average Case uygun oluyor.

### Soru 4: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

**Selection Sort'a göre ilk 4 Adım:**  
[7, 3, 5, 8, 2, 9, 4, 15, 6]  
[2, 3, 5, 8, 7, 9, 4, 15, 6] -> 1  
[2, 3, 5, 8, 7, 9, 4, 15, 6] -> 2   
[2, 3, 4, 8, 7, 9, 5, 15, 6] -> 3  
[2, 3, 4, 5, 7, 9, 8, 15, 6] -> 4


# Proje 2: Merge Sort

**[16,21,11,8,12,22]** -> Merge Sort

### Soru 1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
**Insertion Sort Aşamaları:**  
[16,21,11,8,12,22]  
[16,21,11]   ____  [8,12,22]  
[16,21] [11]  ____  [8,12] [22]  
[16] [21] [11] ____  [8] [12] [22]  
[11,16,21] ____ [8,12,22]  

**Merge Sort ile sıralanmış hali:**  
[8,11,12,16,21,22]

### Soru 2: Dizinin Big-O gösterimini yazınız.
Merge Sort, her zaman O(n log n) zaman karmaşıklığına sahiptir.

# Proje 2: Binary Search Tree

### Soru 1: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. 

**Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.**
 
- Öncelikle 7'yi root olarak seçelim. Root'un sağında kendisinden büyükler, solunda ise kendisinden küçükler bulunur.  
- Root'un sağında 8, solunda 5 bulunur.

**Root'un sağ kısmı:**
- 8'in sağında 9 bulunur.
   
**Root'un sol kısmı:**
- 5'in sağında 6, solunda 1 bulunur.  
- 1'in solunda 0, sağında 3 bulunur.
- 3'ün sağında 4, solunda 2 bulunur.

```bash
Binary Search Tree:
        7
       / \
      5   8
     / \    \
    1   6    9
   / \
  0   3
     / \
    2   4
```
