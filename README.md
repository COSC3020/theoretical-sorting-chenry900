# Theoretical Sorting

A Computer Science researcher claims to have come up with a sorting algorithm
that can sort arbitrary elements in $O(n)$ time based on comparisons of two
elements at a time. This would be asymptotically faster than any known general
sorting algorithm. The algorithm itself is proprietary and will be sold by a
company.

How would you verify this claim? You may assume that you have access to a
black-box implementation of the sorting algorithm, i.e. you cannot examine the
source code, but you can use it to sort any list you like. Explain in detail
your method for investigating whether X is correct, including any expected
results you would get.

Also give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.

Add your answers to this markdown file.

I would check this claim by using quicksort to compare several different arrays that
are of large size and use the information given by both sorting algorithums to determine 
if the sorting algorithum is as fast as the researcher says. If the sorting is $0(n)$ then 
at large lists it should be as fast as the list is long and by using quicksort whos data is 
known to be $0(nlogn)$ we can get a fairly accurate comparaison between the two.
