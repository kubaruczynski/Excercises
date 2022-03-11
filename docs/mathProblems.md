# Math problems

All problems listed below: 

- can be done without need to use OOP (Object Oriented Programming).
- can be done in any programming language (this project will have solutions in C#)
- should use console
- should be gathering user input from console at right time
- should display correct output as soon as it's possible

###### but if you want to, you can do whatever you want as long as it works properly

-----

### 1. Calculate area of the circle

In this program we will calculate area of the circle. We'll ask user for radius of the circle, then calculate radius and display it.

Example
```
Hello user! We're calculating area of circle today!
Please input radius:
>2.608
Area of circle with radius 2.608 will be: 21.37
```

<details>
  <summary>Tips</summary>

First you'll need equation for solving area of the circle, you can find it here:

<img src="https://latex.codecogs.com/svg.image?{\color{Golden}A=\pi*r^2}" title="area of circle" />

Next you might be wondering how to get PI.
You can do it in two ways:

1. Harder way - calculate PI yourself (good job if you do :+1:).
2. Easier way - use PI included in static `Math` class.

Next you might be wondering how to square your radius.
You can do it in two ways:

1. Harder way - calculate square yourself (not that hard, c'mon ;) ).
2. Easier way - use `Pow()` function included in static `Math` class.

</details>

<details>
    <summary style="color: firebrick">
        !WARNING! --- SOLUTION --- !WARNING!
    </summary>

```c#
Console.WriteLine("Hello user! We're calculating area of circle today!");
Console.WriteLine("Please input radius:");

double radius = double.Parse(Console.ReadLine());
double area = Math.PI * Math.Pow(radius, 2);

Console.WriteLine($"Area of circle with radius {radius} will be: {area:N2}");
```
</details>

### 2. Calculate the area of the circle

<details>
    <summary>
        Tips
    </summary>

<img src="https://latex.codecogs.com/svg.image?{\color{Golden}A=\frac{\alpha*r^2}2}" title="area of circle" />
</details>

### Rest of problems

3. Calculate the system of linear equations (ax + by = e; cx + dy = f)
4. Program calculating the relative position of the straight line in relation to the circle
5. List all the divisors of the given number
6. Calculate the number of PI
7. Calculate LCM of two numbers
8. Calculate the GCD of two numbers
9. Check that the number is perfect
10. List prime numbers up to a given number
11. Calculate strongly
12. Calculate the sine
13. Calculate the bisection function
14. Compute more bisection functions
15. The scalar product
16. Counting the homer polynomial