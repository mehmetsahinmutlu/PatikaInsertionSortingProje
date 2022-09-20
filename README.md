# PatikaInsertionSortingProje

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.



Cevaplar:

1. Cevap:
	Insertion Sortta en kucugu bulup en sola alarak yerine o diğer degeri atar.
1. adım 2 ile 22 yer degisir.
	[2,27,16,22,18,6] olur. -> n
2. adım 6 ile 27 yer degisir.
	[2,6,16,22,18,27]		-> n-1
3. adım 16 yerinde kalır.
	[2,6,16,22,18,27] 		-> n-2
4. adım 18 ile 22 yer degisir ve sorting tamamlanir.
	[2,6,16,18,22,27]		-> 1
	
2. Cevap:
	Big-O (n^2) -> Big-O(6^2)
	
3. Cevap: 
	18 sayısı average case kapsamındadır.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Cevap:

1. Adım : [2,3,5,8,7,9,4,15,6]

2. Adım : [2,3,5,8,7,9,4,15,6] // 3 en kucuk oldugu ıcın 3. adıma gecilir.

3. Adım : [2,3,4,8,7,9,5,15,6]

4. Adım : [2,3,4,5,7,9,8,15,6]
	
