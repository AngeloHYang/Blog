# Variable in Java Enhanced For Statement

***Last edit: 16:04:08 12/16/2019***

Java introduced a new way to iterate through Collections and arrays. It's sometimes referred as the `enhanced for statement`.

For example:`

    int[] numbers = {1,2,3,4,5,6,7,8,9,10};
    for (int number: numbers) {
        System.out.println(number);
    }

It makes for loop more compact and easier to read.

The problem is, what happens if I make some changes to `number`? Is `number` a copy of an object in `numbers` or a reference?

Here it goes:

    int[] numbers = {1,2,3,4,5,6,7,8,9,10};
    for (int number: numbers) {
        number = 2;
    }
    for (int number: numbers) {
        System.out.print(number + " ");
    }
    System.out.println();

The result is:

> 1 2 3 4 5 6 7 8 9 10

Thus, the variable created by the Enhanced For loop is a copy of the object from the array or Collection.

---

## References

1. [The for Statement, The Java™ Tutorials](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/for.html). Retrieved on Dec. 16, 2019

---

## **[⇦ Previous: To Create a Simplified Version of *ls*](https://angelohyang.github.io/Blog/Jul.%202019/ls)**

## **[⇨ Next: Yes, Emails are leaking your IP address](../Aug.%202020/Email)**

## **[🏡 Back to Home Page](https://angelohyang.github.io/Blog/)**
