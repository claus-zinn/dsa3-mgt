# *Complementary* Assignment 3: Sorting

## 3.1 Quicksort: median-of-3 pivot

Take the implementation of quicksort from the slides and make the
following changes:

  * Do not shuffle the array initially.
  * Use the median-of-3 pivot selection (where possible), where the
    candidates are randomly selected.
     
Can you avoid randomly selecting a pivot candidate more than once?

Can you confirm the median-of-3 pivot selection quicksort to behave better on presorted input then the
original quicksort (if you take out its shuffle as well)?

### 3.2 Quicksort: iterative version

Reimplement quicksort as given on the slides, but without using recursion.

*Hint:* The partition method remains unchanged. Introduce an auxiliary data structure, a stack to
"somehow" maintain the sub-arrays. It should not be necessary to create copies of the sub-arrays yet
to be sorted.

Under what circumstances is this implementation beneficial?

## 3.3 Book exercises

* From the [web exercises](http://algs4.cs.princeton.edu/21elementary/) for
  elementary sorts:

  * 6: Stupidsort
  * 9: Bogosort
  
