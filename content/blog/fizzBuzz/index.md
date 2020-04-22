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

And just like that, you now have a functioning fizz buzz program in c#!    

<!-- <a name="abcd">`youtube: https://www.youtube.com/watch?v=xJVHWhO9bJY&t=2046s`</a> -->


![A picture I found on the internet](./connect.svg)

```js
string name = "uKnowAguy"
```


