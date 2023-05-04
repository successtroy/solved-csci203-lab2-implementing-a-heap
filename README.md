Download Link: https://assignmentchef.com/product/solved-csci203-lab2-implementing-a-heap
<br>
For this exercise you are to implement a heap, using an array as shown in the lectures. The heap will be built by repeatedly reading the values in the file into sequential locations in the array and then converting the array into a heap using makeheap() as seen in lectures.

Once you have built the heap  you are to print out the first five elements of the heap array. Your heap should be able to hold 100 integers. A pseudo‐code outline for the program is given below:

<strong>Begin main display a prompt for the file name read in the file name try to open the file if the file fails to open </strong>

<strong>       print an error message on the screen and exit fi </strong>

<strong>       while we can read an int from the file </strong>

<strong>             insert the int into the array </strong>

<strong>       elihw </strong>

<strong>close the file makeheap() </strong>

<strong>    for i = 1 to 5 </strong>

<strong>              print the i<sup>th</sup> element of the heap     rof </strong>

<strong>End main </strong>

Do not implement the heap using a class or with STL. The heap must be implemented using a fixed size array of integers (100 entries should be enough). The heap array and the index to the last item in the heap should be global variables.


