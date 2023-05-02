Download Link: https://assignmentchef.com/product/solved-coen12-project-6-quick-sorting
<br>
You only have to implement a sorting algorithm that you’ve already learned in class, and you’ll be modifying his implementation of a set ADT.

<h1>1        Interface</h1>

Only one interface function must be modified for this assignment:

<ul>

 <li>void *getElements(SET *sp); allocate and return a sorted array of elements in the set pointed to by <em>sp</em></li>

</ul>

<h1>2        Implementation</h1>

As required by Professor Loony, you will modify the getElements function to return a sorted array of elements in the set. He requires you to use the <strong><em>quicksort </em></strong>algorithm, which was discussed in class and in the text. Quicksort is a recursive sorting algorithm that is very fast in practice. The basic algorithm works as follows:

<ol>

 <li>Choose a value from the subarray to be sorted. This value is called the pivot. The choice of pivot does notaffect the correctness of the algorithm, but can affect its efficiency.</li>

 <li>Partition the subarray around the pivot so that the pivot is in the correct location, all values to the left of thepivot are less than the pivot, and all values to the right of the pivot are at least the value of the pivot.</li>

 <li>Recursively sort the subarrays to the left and right of the pivot.</li>

</ol>