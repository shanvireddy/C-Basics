

# Date of submission 11-Sep by 4:00 PM 
## Submission has to be made through github only 



1. Read an array of 1000  numbers from a file

1. Implement Binary search to check whether
the given number is there or not.
Algorithm for Binary search is give below.

1. HOw to generate 1000 nums

1.Write a program in C to generate 1000 random numbers

1. Copy paste that to excel Use MS excel as a col

1.Sort it using Excel function and copy paste it back
into your input file

1. Implement Linear search as discussed in class.

1. Compare the difference in terms of number of
comparisons made by  Linear and Binary search
Also find the time difference of execution to
between Binary search and linear search

1. Learn HTML basics from w3 Tutorials and 
write the output of the above program into HTML file
properly formatted


## Algorithm for Binary Search
Procedure binary_search
   A ← sorted array
   n ← size of array
   x ← value to be searched

   Set lowerBound = 1
   Set upperBound = n 

   while x not found
      if upperBound < lowerBound 
         EXIT: x does not exists.
   
      set midPoint = lowerBound + ( upperBound - lowerBound ) / 2
      
      if A[midPoint] < x
         set lowerBound = midPoint + 1
         
      if A[midPoint] > x
         set upperBound = midPoint - 1 

      if A[midPoint] = x 
         EXIT: x found at location midPoint

   end while
   
end procedure

</HTML>