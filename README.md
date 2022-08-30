# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
```
using System;
namespace helloworld
{
    public class prethivee
    {
        public static void Main(string[] args)
        {
            int num1, num2, num3;
            Console.WriteLine("enter the input a");
            num1 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("enter the input b");
            num2 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("enter the input c");
            num3 = Convert.ToInt32(Console.ReadLine());

            if (num1 > num2 && num1 >num3)
            {
                Console.WriteLine("\n largest number is:" + num1);
            }

            if (num2 > num1 && num2 > num3)
            {
                Console.WriteLine("\n Largest number is:" + num2);
            }

            if (num3 > num1 && num3 > num2)
            {
                Console.WriteLine("\n Largest number is:" + num3);
            }

            Console.ReadLine();

        }
    }
}
```

## Output:
![ouput](output%201%20(1).png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully
