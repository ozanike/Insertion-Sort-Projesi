# Patika.dev Insertion-Sort-Projesi
**[22,27,16,2,18,6]**  
*1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.   
2.Big-O gösterimini yazınız.   
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.   
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.*


**1.Soru**
___
>[22 / ,27,16,2,18,6]   
[22,27 / ,16,2,18,6]   
[16,22,27 / ,2,18,6]   
[2,16,22,27 / ,18,6]   
[2,16,18,22,27 / ,6]   
[2,6,16,18,22,27]   


**2.Soru**
___   

>**Big O** :o(n^2)   

**3.Soru**
___
> Time Complexity  
Avarage Case: o(n^2)    
Best Case : o(n)   
Worst Case: o(n^2)    

**4.Soru**   
___

Dizi sıralandıktan sonra **[2,6,16,18,22,27]** Avarage Case kapsamına girer.Çünkü dizinin tam oratasına denk gelmektedir.  
___ 


**[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
___
>* [7 / ,3,5,8,2,9,4,15,6]   
>* [3,7 / ,5,8,2,9,4,15,6]   
>* [3,5,7 / ,8,2,9,4,15,6]
>* [3,5,7,8 / ,2,9,4,15,6]