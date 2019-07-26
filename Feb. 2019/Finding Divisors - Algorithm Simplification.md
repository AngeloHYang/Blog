# Finding Divisors - Algorithm Simplification

***Last edit: 13:35:45 2/24/2019***

What would you do if you want to find all divisors of a number?

----

## 1. Search One by One

The first question is: what is a divisor? In short, if a number can be divided with no remainder by another number, and the second number is equal to or less great than the first number, then the second number is a divisor of the first number. For example, 10 % 2 = 5 ... 0, therefore, 2 is a divisor of 10.

Based on its definition, we can easily come up with this method.

    for numberCounter in range(1, inputNumber + 1):
        if inputNumber % numberCounter == 0:
            print(numberCounter, "is a divisor of", inputNumber)

## 2. Cut in Half

The problem with the method below is that it's time consuming. Let's take a look at this graph:

![cut in half](cut-in-half.png)

It isn't hard to tell that a divisor of a number besides itself can't be greater than half the value of the number. For example, the second greatest divisor of 64 is 32, the second greatest divisors of 28 is 14, the second greatest divisor of 9 is 3.

Therefore, we can simply search from 1 to half the value of the original number.

    for numberCounter in range(1, int(inputNumber/2 + 1)):
        if inputNumber % numberCounter == 0:
            print(numberCounter, "is a divisor of", inputNumber)
    print(inputNumber, "is a divisor of", inputNumber)

## 3. Find a Match, Stop at Square Root

Yet, we can make the algorithm even quicker.

![80 match](80-match.jpeg)

Had you noticed the divisors of a number, you'll see that divisors always comes in pairs. In another word, you can always get the original number from the product of its two divisors. If you have known a divisor, you can easily get another divisor by **the number / the divisor**.

Because of which, we don't even have to search from 1 to half the value of the original number. We can stop at the square root of the original number. If the square root isn't an int, find the int less great than it.

    import math
    inputNumber = int(input())
    squareRootToInt = math.sqrt(inputNumber)
    if squareRootToInt != int(squareRootToInt):
        squareRootToInt = int(squareRootToInt)
    for numberCounter in range(1, int(squareRootToInt) + 1):
        if inputNumber % numberCounter == 0:
            print("You've fount a divisor of", inputNumber, "and it is", numberCounter)
            if numberCounter != inputNumber / numberCounter:
                print("You also found a mate for it:", int(inputNumber / numberCounter))

----

## **[⇦ Previous: How to Insert a Table to a Markdown File](https://angelohyang.github.io/Blog/Jan.%202019/How%20to%20Insert%20a%20Table%20to%20a%20Markdown%20File)**

## **[⇨ Next: Binary Search](https://angelohyang.github.io/Blog/Feb.%202019/Binary%20Search)**

## **[🏡 Back to Home Page](https://angelohyang.github.io/Blog/)**