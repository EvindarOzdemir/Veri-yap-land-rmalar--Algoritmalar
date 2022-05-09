Insertion sort videosunda anlatılan selection sort'tu. Ben **selection sorta göre değil inserion sorta göre yaptım** (videonun altında verilen kaynaklardan yararlandım). Ama ödevi selection sort için de ayrıca aşağıda yaptım.

#  Insertion Sort Project
  [22, 27, 16, 2, 18, 6]   
 
1. [**22, 27**, 16, 2, 18, 6]  .... 1

2. [**16, 22, 27**, 2, 18, 6]

3. [**2, 16, 22, 27**, 18, 6]

4. [**2, 16, 18, 22, 27**, 6]  .... n-1

5. [**2, 6, 16, 18, 22, 27**]   .... n


> ## Big O Notation- worst case
n!= n*(n+1)/2= (n^2+n)/2 =>  **O(n^2)**


> ## Time complexity.
best case: the case that all numbers already sorted, O(n)

average case: O(n^2)

worst case: O(n^2)

> ## Which case for 18?
Since it is in the middle of the array 18 is in the scope of the avarage case 

> ## First 4 Insertion Sort steps
[7,3,5,8,2,9,4,15,6] 

1. [[**3,7**,5,8,2,9,4,15,6]

2. [**3,5,7**,8,2,9,4,15,6]

3. [**3,5,7,8**,2,9,4,15,6]

4. [**3,5,7,2,8**,9,4,15,6]



















-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


# Selection Sort Project
1. [**22**,27,16,2,18,6] 

2. [2,**27**,16,22,18,6] Now we now that 2 is the smallest, we will start checking it from the second number.

3. [2,6,**16**,22,18,27] There is no change in arrey because the next number is already in the right plase.

4. [2,6,16,**22**,18,27] 

5. [2,6,16,18,**22**,27]

6. [2,6,16,18,22,**27**]

> ## Big O Notation- worst case

let n represent the size of the list,

in the 1. step all values must be checked. (n)

in each consequitive step the amounth of checks decreased by 1. (n-1,n-2,n-3.......1)

this means the total amount of checks is n!

n!= n*(n-1)/2= (n^2-n)/2  n^2 is dominant here, 

so **O(n^2)**

> ## Time comp. 

worst,average and best case: **O(n^2)**

> ## First 4 Selection Sort steps

[7,3,5,8,2,9,4,15,6]

1.[**7**,3,5,8,2,9,4,15,6]

2. [2,**3**,5,8,7,9,4,15,6]

3. [2,3,**5**,8,7,9,4,15,6]

4.[2,3,4,**8**,7,9,5,15,6]


