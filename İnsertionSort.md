# <strong> Veri Yapileri Ve Algoritmalar "InsertionSort" Sorular:

## <strong> [22,27,16,2,18,6] -> Insertion Sort 

<br>
<br>

### 1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız:
<br>

```

[22,27,16,2,18,6] 

[2,27,16,22,18,6] n

[2,6,16,22,18,27] n-1

[2,6,16,18,22,27] 1

```
<br>
<hr>
<br>

### 2. Big-O gösterimini yazınız:

```

n * (n-1)  * 1  

n.(n-1)/2   

n2+n/2  

O(n²)

```
<br>
<hr>
<br>

### 3. Time Complexity: 
<br>

#### Average Case: Aradığımız sayının ortada olması,
#### Worst Case: Aradığımız sayının sonda olması, 
#### Best Case: Aradığımız sayının dizinin en başında olması.
<br>

```
[2,6,16,18,22,27]

Average Case: 16-18
Worst Case: 27
Best Case: 2

```
<br>
<hr>
<br>

### 4. Dizi sıralandıktan sonra "18" sayısı hangi case kapsamına girer?
<br>


```
[2,6,16,18,22,27]

Average Case: "18"

```
<br>
<hr>
<br>

### 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre "ilk 4 adımını" yazınız:
<br>


```

[7,3,5,8,2,9,4,15,6] 

[2,3,5,8,7,9,4,15,6] 

[2,3,4,8,7,9,5,15,6] 

[2,3,4,5,7,9,8,15,6] 


-- 4 adımdan sonrasını merak edenler için: --

[2,3,4,5,6,9,8,15,7] 

[2,3,4,5,6,7,8,15,9] 

[2,3,4,5,6,7,8,9,15]

```
<br>
<hr>
<br>

## <b> Teşekkürler
<br>

```