---
title: Learning & Practicing
date: "2020-04-21T22:12:03.284Z"
description: "Fizz Buzz in C#"
---
I've been wanting to blog, but I've been extremely busy with school 
and other projects. 

####Solution to my problem

Blog about potential interview questions with my
take on the solution!

####This is my take on fizz buzz (In C#)



🙋‍♂️ Public Service Announcement 👇

I used a ternary conditional operator (because I need practice using them), and I used the foreach loop (I'm just now getting familiar with).

Here we go...

Fizz buzz = Print numbers 1 through 100. When a number is divisible by 3, print fizz. If a number is divisible by 5, print buzz. And if a number is divisible by both 3 and 5, print fizz buzz. 
```js

Console.WriteLine ("\t Practicing the foreach loop and ternary \n" +
                   "\t conditional operators to run the infamous \n" +
                   "\t FIZZ BUZZ interview program!!! \n\n");

```


```js
using System;

namespace foreachFizzbuzz
{
    class Program
    {
        static void Main(string[] args)
        {
            int[] fizzBuzzArr = new int [100]; // array set to 100 different integers
            int i = 0; // our counter to fill            

            foreach(int value in fizzBuzzArr) // begin loop
            {                
                i++;                
                Console.Write((i % 3) == 0 && (i % 5) == 0 ? ($"{i} (fizz buzz)\n\n")  // initial if
                    : (i % 3) == 0 ? ($"{i} (fizz), ") // else if
                    : (i % 5) == 0 ? ($"{i} (buzz)\n\n") // else if
                    : ($"{i}, ")); // else                
            } // end loop


            Console.ReadLine();

        }
    }
}
```
Out put should look something like this
```js

        Practicing the foreach loop and ternary
        conditional operators to run the infamous
        FIZZ BUZZ interview program!!!


1, 2, 3 (fizz), 4, 5 (buzz)

6 (fizz), 7, 8, 9 (fizz), 10 (buzz)

11, 12 (fizz), 13, 14, 15 (fizz buzz)

16, 17, 18 (fizz), 19, 20 (buzz)

21 (fizz), 22, 23, 24 (fizz), 25 (buzz)

26, 27 (fizz), 28, 29, 30 (fizz buzz)

31, 32, 33 (fizz), 34, 35 (buzz)

36 (fizz), 37, 38, 39 (fizz), 40 (buzz)

41, 42 (fizz), 43, 44, 45 (fizz buzz)

46, 47, 48 (fizz), 49, 50 (buzz)

51 (fizz), 52, 53, 54 (fizz), 55 (buzz)

56, 57 (fizz), 58, 59, 60 (fizz buzz)

61, 62, 63 (fizz), 64, 65 (buzz)

66 (fizz), 67, 68, 69 (fizz), 70 (buzz)

71, 72 (fizz), 73, 74, 75 (fizz buzz)

76, 77, 78 (fizz), 79, 80 (buzz)

81 (fizz), 82, 83, 84 (fizz), 85 (buzz)

86, 87 (fizz), 88, 89, 90 (fizz buzz)

91, 92, 93 (fizz), 94, 95 (buzz)

96 (fizz), 97, 98, 99 (fizz), 100 (buzz)

```

And just like that, you now have a functioning fizz buzz program in c#!    

<!-- <a name="abcd">`youtube: https://www.youtube.com/watch?v=xJVHWhO9bJY&t=2046s`</a> -->


![A picture I found on the internet](./connect.svg)

```js

string name = "uKnowAguy"

```


