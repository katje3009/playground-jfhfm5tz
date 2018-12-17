# Welcome!

This C# template lets you get started quickly with a simple one-page playground.

```C# runnable
// { autofold
using System;

class Hello 
{
    static void Main() 
    {
// }

        Console.WriteLine("Hello World!");
        
        string value = string.Empty;
        Random rand = new Random();
            
        for(int i = 0; i < 100; i++)
        {
            int newValue = rand.Next(0,i);
            value += ";" + newValue.ToString();
        }
        
        Console.WriteLine(value);

// { autofold
    }
}
// }
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced C# template](https://tech.io/select-repo/386)
