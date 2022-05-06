#  Insertion Sort Project
1.  [22, 27, 16, 2, 18, 6]
 
2. [**22, 27**, 16, 2, 18, 6]

3. [**16, 22, 27**, 2, 18, 6]

4. [**2, 16, 22, 27**, 18, 6]

5. [**2, 16, 18, 22, 27**, 6]

6. [**2, 6, 16, 18, 22, 27**]


# Big O Notation- worst case

































# Selection Sort Project
1. [**22**,27,16,2,18,6] 

2. [2,**27**,16,22,18,6] Now we now that 2 is the smallest, we will start checking it from the second number.

3. [2,6,**16**,22,18,27] There is no change in arrey because the next number is already in the right plase.

4. [2,6,16,**22**,18,27] 

5. [2,6,16,18,**22**,27]

6. [2,6,16,18,22,**27**]

# Big O Notation- worst case

> let n represent the size of the list,

> in the 1. step all values must be checked. (n)

> in each consequitive step the amounth of checks decreased by 1. (n-1,n-2,n-3.......1)

> this means the total amount of checks is n!

> n!= n*(n-1)/2= (n^2-n)/2  n^2 is dominant here, 

> so **O(n^2)**

# Time comp.
