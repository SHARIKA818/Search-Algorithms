# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
## Program to search the item in a list one by one from start to end to find the match. (or) Use a linear search method to match the item in a list.
## Developed by : SHARIKA.R
## Register No : 212223230204


## Sample Input and Output
PROGRAM 1:
![image](https://github.com/SHARIKA818/Search-Algorithms/assets/139834761/3892ffe8-4337-4ec6-96d8-84ee3c839e79)

PROGRAM 2:

![image](https://github.com/SHARIKA818/Search-Algorithms/assets/139834761/8426663b-8179-4c48-8513-9f7b48cbe035)

PROGRAM 3:

![image](https://github.com/SHARIKA818/Search-Algorithms/assets/139834761/b01e0fc8-7e32-488d-a062-5039254301f4)




## Result
Thus the linear search and binary search algorithm is implemented using python programming.
