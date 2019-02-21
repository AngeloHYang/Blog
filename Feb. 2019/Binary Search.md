# Binary Search

***Last edit: 18:46:21 2/21/2019***

You can accelerate the process of finding if a number exits in an array and where it is with **binary search**.

---

Given an array of integers:

Index | Value
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

If you're going to write an program that tells the index of a specific number in the array(assuming there's no number identical), what would you do?

It isn't hard to think of **sequential search**, which is scanning through every element in the array one by one, starting at the 0th element and ending at the last one.

For example:

    for (int whichElement = 0; whichElement < totalNumber; whichElement++)
    {
        if (array[whichElement] == theNumberLookingFor)
        {
            printf("%d\n", whichElement);
        }
    }

But you can tell how time consuming for it has
​