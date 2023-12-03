
# Guided Assignment - Introduction to Loops in C#

## Tutorials

### Starting Code
```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Learning Loops");
    }
}
```

**Understanding the Code:** This initial code is our setup to explore loops in C#. We'll modify it to understand how loops work.

**Write this code**  
- Add a comment above the `Main` method for better understanding.

```csharp
    // Entry point of our C# program
    static void Main(string[] args)
    {
        Console.WriteLine("Learning Loops");
    }
```

---

### **Step 1: Using a For Loop**

**Objective:** Learn to use a for loop for repeated actions.

Implement a for loop to print numbers from 1 to 5.

```csharp
static void Main(string[] args)
{
    for (int i = 1; i <= 5; i++)
    {
        Console.WriteLine(i);
    }
}
```

**Run your code**  
You should see numbers 1 through 5 printed one after another.

**Understanding For Loops:** For loops are used for repeating actions a specific number of times.

---

### **Step 2: Exploring While Loops**

**Objective:** Understand how to use a while loop.

Use a while loop to perform a repeated action until a condition is no longer true.

```csharp
    int number = 1;

    while (number <= 5)
    {
        Console.WriteLine(number);
        number++;
    }
```

**Run your code**  
The numbers 1 to 5 will be printed, similar to the for loop.

**Understanding While Loops:** While loops continue executing as long as the condition remains true.

---

### **Step 3: Working with Do-While Loops**

**Objective:** Learn to use a do-while loop.

Implement a do-while loop which is similar to a while loop but checks the condition at the end.

```csharp
    number = 1;

    do
    {
        Console.WriteLine(number);
        number++;
    } while (number <= 5);
```

**Run your code**  
Again, numbers 1 to 5 will be printed.

**Understanding Do-While Loops:** Do-while loops guarantee that the loop body is executed at least once.

---

### **Step 4: Breaking Out of a Loop**

**Objective:** Learn to exit a loop prematurely using `break`.

Use a for loop and exit it using `break`.

```csharp
    for (int i = 1; i <= 5; i++)
    {
        if (i == 3)
        {
            break;
        }
        Console.WriteLine(i);
    }
```

**Run The Code**

The loop will break when the number reaches 3.

**Understanding Break:** The `break` statement immediately exits the loop, regardless of the loop's condition.

---

### **Step 5: Skipping Iterations with Continue**

**Objective:** Understand how to skip loop iterations using `continue`.

Use a for loop and skip an iteration using `continue`.

```csharp
    for (int i = 1; i <= 5; i++)
    {
        if (i == 3)
        {
            continue;
        }
        Console.WriteLine(i);
    }
```

**Run your code**

Number 3 will be skipped in the output.

**Understanding Continue:** The `continue` statement skips the current loop iteration and proceeds with the next one.

---

### Additional Tips and Resources

- **Debugging:** Ensure loop conditions are set correctly to avoid infinite loops.
- **Challenge:** Try nesting loops within each other and observe the output.
- **Further Learning:** Explore more complex loop structures and their practical applications.
- **Syntax Highlighting:** Pay attention to how syntax highlighting helps distinguish loop structures in the code.

---
