## 1. [22,27,16,2,18,6] -> Insertion Sort Aşamaları

22  ||  27	16	2	18	6

22	27 	|| 16	2	18	6

16	22	27 	|| 2	18	6

2	16	22	27 	|| 18	6

2	16	18	22	27|| 	 6

2	6	16	18	22	27

## 2. Dizinin Big-O gösterimi

Step 1 -> n

Step 2 -> n-1

Step 3 -> n-2

....

Step n-1 -> 1


sum = (n*(n-1))/2 -> O(n^2)


## 3. Time Complexity
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.


## 4. 18 sayısı Average case kapsamına girmekte

[7,3,5,8,2,9,4,15,6] -> Insertion Sort – ilk dört aşama

7||	3	5	8	2	9	4	15	6

3	7||	5	8	2	9	4	15	6

3	5	7	||8	2	9	4	15	6

3	5	7	8	||2	9	4	15	6


