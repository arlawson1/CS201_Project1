# CS201_Project1
cpp file for a circular dynamic array template class

This program is designed to create a class of any type that stores elements in a circular dynamic array. This data
 structure is designed to hold a certain number of elements (2 by default) and expand its capacity when an element
 is added beyond its capacity. This data structure also has a circular characteristic, in that it can add or remove
 elements from either the front of the array (using a modulo operator) or the back of the array.
 
The class has a default constructor as well as an overloaded constructor, a destructor, copy constructor, and an 
 assignment operator.
 
The functions that this class supports are general functions to add an element to the end of the array (addEnd(el v)),
 add an element to the beginning of the array (addFront(el v)), and functions to delete from either end.
 Several helper functions and functions to assist in testing have been added as well (length(), capacity(), clear(),
 getTailNum(), getFrontNum(), shift(), swap(), partition(), etc.).
 
A few other basic data functions have been added, such as a quick select function, a worst-case select function, a
 linear search function, and a binary search function.

A few sorting algorithms have been implemented as part of this program (merge sort as a stable method, counting sort,
 and radix sort).
