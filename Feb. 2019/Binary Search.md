# Binary Search

***Last edit: 13:35:45 2/24/2019***

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

If you're going to write a program that tells the index of a specific number in the array (assuming there's no number identical), what would you do?

It isn't hard to think of **sequential search (linear search)**, which is scanning through every element in the array one by one, starting at the 0th element and ending at the last one.

For example:

    for (int whichElement = 0; whichElement < totalNumber; whichElement++)
    {
        if (array[whichElement] == theNumberLookingFor)
        {
            printf("%d\n", whichElement);
        }
    }

But you can tell how time consuming it is for it has a time complexity of `O(n)` on average.
​
That's why we need **binary search**.

In order to do so, you'll need to sort the array first. You can do it with **quick sort** `(O(n log n)`, but you can also choose whatever you like as long as the numbers are in **descending order** *or* **ascending order**.

The beauty of binary search is that it locates and narrows the interval where the number you're looking for might appear. Call it "cut in half" if you like. If there's no identical numbers in the array, the length of the interval will be 1 in the end.

Let's go back to the array.

- First, let's put the numbers in ascending order:

    Index | Value
    :---: | :---:
    0 | 3
    1 | 5
    2 | 26
    3 | 27
    4 | 31
    5 | 68
    6 | 85
    7 | 96
    8 | 96
    9 | 99

- Assume we are looking for the index of 85.

- It's obvious that `theIndex ∈ [0, 9]`.

- But theIndex is greater than `4` (*from 9/2*).

- So, we can narrow it down to `theIndex ∈ [5, 9]`.

- Is `theIndex == 7` (from (5+9)/2)`?`

- `No!` So it'll be `theIndex ∈ [5, 6]`.

- Is `theIndex == 5` (from (5+6)/2)`?`

- `No!` So it'll be `theIndex ∈ [6, 6]`.

- Therefore, theIndex shall be **`6`**.

Source Code:
  
    int left = 0, right = 9;
    while (left < right)
    {
        if (array[(left + right)/2] == 85)
        {
            return (left + right)/2;
        } else
        {
            if (array[(left + right)/2] < 85)
            {
                if ((left + right)/2 + 1 <= 9)
                {
                    left = (left + right)/2 + 1;
                }
            } else
            {
                if ((left + right)/2 + 1 >= 0)
                {
                    right = (left + right)/2 - 1;
                }
            }
        }
    }
    return left;

As for the time complexity of **binary search**

Condition | O
---- | ----
Worst-case performance | O(log n)
Best-case performance | O(1)
Average performance | O(log n)
Worst-case space complexity | O(1)

There's only one question left. What happens if the number you are looking for appears multiple times in the array? I'm sure you can figure that out on your own.

---

## **[⇦ Previous: Finding Divisors - Algorithm Simplification](https://angelohyang.github.io/Blog/Feb.%202019/Finding%20Divisors%20-%20Algorithm%20Simplification)**

## **[⇨ Next: To Create a Simplified Version of *ls*](https://angelohyang.github.io/Blog/Jul.%202019/ls)**

## **[🏡 Back to Home Page](https://angelohyang.github.io/Blog/)**
