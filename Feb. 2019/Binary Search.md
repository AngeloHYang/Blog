# Binary Search

***Last edit: 18:32:47 2/20/2019***

You can accelerate the process of finding if a number exits in an array and where it is with **binary search**.

---

Given an array of integers:

Which One | Value
:---: | :---:
0 | 85
1 | 99
2 | 26
3 | 96
4 | 96
5 | 68
6 | 27
7 | 31
8 | 5
9 | 3

It isn't hard to think of **sequential search**, which is scanning through every element in the array one by one, starting at the 0th element and ending at the last one.

For example:

    for (int whichElement = 0; whichElement < totalNumber; whichElement++)
    
    {
    
        if (array[whichElement] == theNumberLookingFor)
    
        {
    
            printf("%d\n", whichElement);
    
        }
    
    }
