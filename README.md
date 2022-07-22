# Insertion-Sort
Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort
1.Adım: [22|22,27,2,18,6]
2.Adım: [16,22,27|2,18,6]
3.Adım: [2,16,22,27|18,6]
4.Adım: [2,16,18,22,27|6]
5.Adım: [2,6,16,18,22,27]

Big-O gösterimini yazınız.
O(n^2)

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Worst case: [27,22,18,16,6,2]
Best case: [2,6,16,18,22,27]

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizimiz küçükten büyüğe sıraladıktan sonra 18 sayısı ortada yer almaktadır. [2,6,16,18,22,27]  18 sayısı bizim ortanca değerimizdir. Bu nedenle average case diyebiliriz.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[7|,3,5,8,2,9,4,15,6]
[3,7|,5,8,2,9,4,15,6]
[3,5,7|,8,2,9,4,15,6]
[3,5,7,8|,2,9,4,15,6]

www.patika.dev
