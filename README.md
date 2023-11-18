# Hi there 👋, my name is Klyse

```csharp

using System;
using System.Collections.Generic;

public class Program
{
  public static IEnumerable<string> Loves()
  {
    yield return "Fantasy 📚 / 🎥";
    yield return "Exploring the World 🗺️";
    yield return "PC Games 🕹️️";
    yield return "Improving my coding Skillz 💡";
    yield return ".net core 🥇";
  }

  public static IEnumerable<string> Hates()
  {
    yield return "We have always done it this way 🔙";
    yield return "Top down approach 🧑🏻‍💼";
  }

  public static void Main()
  {
    Console.WriteLine("Name: Klyse");
    Console.WriteLine("---");
    Console.WriteLine("Work: Innoactive");
    Console.WriteLine("Position: Backend Dev & DevOps 💻");
    Console.WriteLine("---");
    Console.WriteLine("In love with:");
    foreach (string klyseLoves in Loves()){
      Console.WriteLine(klyseLoves);
    }
    Console.WriteLine("---");
    Console.WriteLine("Hates:");
    foreach (string klyseHates in Hates()){
      Console.WriteLine(klyseHates);
    }
  }
}
```

```
Name: Klyse
---
Work: Innoactive
Position: Backend Dev & DevOps 💻
---
In love with:
Fantasy 📚 / 🎥
Exploring the World 🗺️
PC Games 🕹️️
Improving my coding Skillz 💡
.net core 🥇
---
Hates:
We have always done it this way 🔙
Top down approach 🧑🏻‍💼
```
