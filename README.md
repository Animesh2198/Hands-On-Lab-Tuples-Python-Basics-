# Hands-On-Lab-Tuples-Python-Basics-
In this repository we will learn about basics of python (Tuples)

Tuple is created with different data types such as sting, float, int. It can be created within simple brackets not as same as lists which are created in "[]". 
For an Ex - tuple1 = ("disco",10,1.2 )
tuple1

The type of the tuple is Tuple

Indexing in the tuple is same as indexing in list . 
Where object can be obtained by including following 
print(tuple1[0])
print(tuple1[1])
print(tuple1[2])

This will give output as the values present at the index of 0,1, 2 which is disco,10,1.2. 

We can access the objects present in the tuples with negative indexing also. 

for ex - tuple1[-1] the output will be 1.2 (-ve indexing always start from the last element present in the list.)

We can combine two tuples or just strings or data types to create a new tuple 
for ex - 
tuple2 = tuple1 + ("hard rock", 10)
tuple2
 
output  - ('disco', 10, 1.2, 'hard rock', 10)

We can slice the tuple with the following 
tuple2[0:3] The output will be the index of 0 which is disco to third index which is "1.2".

If we want to know the length of the tuple we will simply use len("Tuple name") 

for ex - len(tuple2) 
 
We can sort the tuple with the help 
Ratings = (0, 9, 6, 5, 10, 8, 9, 6, 2)
Ratings_Sort = Sorted(Ratings)
Ratings_Sort 

The output will be : [0, 2, 5, 6, 6, 8, 9, 9, 10] 

We can nest tuple 
NestedT =(1, 2, ("pop", "rock") ,(3,4),("disco",(1,2)))

We can access the index value with the help of 

print("Element 0 of Tuple: ", NestedT[0])
print("Element 1 of Tuple: ", NestedT[1])
print("Element 2 of Tuple: ", NestedT[2])
print("Element 3 of Tuple: ", NestedT[3])
print("Element 4 of Tuple: ", NestedT[4])

Element 0 of Tuple:  1
Element 1 of Tuple:  2
Element 2 of Tuple:  ('pop', 'rock')
Element 3 of Tuple:  (3, 4)
Element 4 of Tuple:  ('disco', (1, 2))

print("1st value of 2nd element of tuple", NestedT[2][0])
We can dig more into indexes 
NestedT[2][1][1]

To find the first index of disco 
genres_tuple.index("disco") 




