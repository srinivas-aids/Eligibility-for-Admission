# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course.

## Algorithm:
Step 1:

Get the three subject marks from the user.

Step 2:

Check the following conditions mentioned in the question using if-else statement.

Step 3:

Print the appropriate output by statisfying the conditions.

Step 4:

End the program.

## Program:
Developed By : SRINIVAS.U

Reg no : 212221230108
```C#
using System;
namespace hi
{
    public class Program
    {
        public static void Main()
        {
            int maths_marks, physics_marks, chemistry_marks, total;
            Console.Write("Enter the maths mark: ");
            maths_marks = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter the physics mark: ");
            physics_marks = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter the chemistry mark: ");
            chemistry_marks = Convert.ToInt32(Console.ReadLine());
            if (maths_marks >= 65 && physics_marks >= 55 && chemistry_marks >= 50)
            {
                total = maths_marks + physics_marks + chemistry_marks;
                if (total >= 180 || (maths_marks + physics_marks) >= 140)
                {
                    Console.WriteLine("The student is eligible for engineering");
                }
                else
                {
                    Console.WriteLine("The student is not eligible for engineering");
                }
            }
            else
            {
                Console.WriteLine("The student is not eligible for engineering");
            }
        }
    }
}

```



## Output:
![image](https://github.com/Jayamani25/Eligibility-for-Admission/assets/85949888/0bb2fc9b-93df-4fc1-98ab-a83f9cc0afb2)

## Result:
The above C# code is executed and the output is obtained.
