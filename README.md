# 💻 C# Practice - Object-Oriented Programming Fundamentals

<div align="center">
  <strong>Master C# programming from basics to advanced OOP concepts</strong>
</div>

---

## 📋 Overview

**CSharp-Practice-Basic** is a comprehensive learning repository for C# programming language fundamentals. Perfect for beginners transitioning from other languages or aspiring .NET developers.

### 🎯 Learning Goals

✅ C# syntax and fundamentals  
✅ Object-Oriented Programming (OOP)  
✅ Data types and structures  
✅ LINQ and functional programming  
✅ Exception handling  
✅ File I/O operations  
✅ Collections and generics  
✅ Async/await patterns  

---

## 🛠️ Technology Stack

| Technology | Purpose |
|-----------|----------|
| **C#** | Primary language |
| **.NET Framework** | Runtime environment |
| **Visual Studio** | IDE (recommended) |
| **Console Apps** | Testing ground |

---

## 📁 Project Structure

```
CSharp-Practice-Basic/
├── 01-Fundamentals/
│   ├── Variables.cs
│   ├── Operators.cs
│   ├── ControlFlow.cs
│   └── Program.cs
├── 02-OOP/
│   ├── Classes.cs
│   ├── Inheritance.cs
│   ├── Polymorphism.cs
│   └── Encapsulation.cs
├── 03-Collections/
│   ├── Arrays.cs
│   ├── Lists.cs
│   ├── Dictionaries.cs
│   └── Generics.cs
└── 04-Advanced/
    ├── LINQ.cs
    ├── Async.cs
    ├── Exceptions.cs
    └── FileIO.cs
```

---

## 🚀 Getting Started

### Prerequisites
- .NET SDK installed
- C# IDE (Visual Studio or VS Code)
- Basic programming knowledge

### Installation

```bash
# Clone repository
git clone https://github.com/Muhammad-Tabish-123/CSharp-Practice-Basic.git
cd CSharp-Practice-Basic

# Run a console project
dotnet run

# Or compile and run
dotnet build
.\bin\Debug\net6.0\Program.exe
```

---

## 📚 Curriculum

### Level 1: Fundamentals
- **Variables** - Declaring variables, data types
- **Operators** - Arithmetic, comparison, logical
- **Control Flow** - If/else, loops, switch
- **Functions** - Method declaration, parameters, return
- **Strings** - String manipulation, formatting

### Level 2: Object-Oriented Programming
- **Classes & Objects** - Defining classes, instantiation
- **Properties** - Get/set, auto-properties
- **Methods** - Instance and static methods
- **Constructors** - Initialization, overloading
- **Inheritance** - Base classes, derived classes
- **Polymorphism** - Virtual methods, overriding
- **Interfaces** - Contract definition
- **Abstract Classes** - Abstract members

### Level 3: Collections & Generics
- **Arrays** - Single/multi-dimensional arrays
- **Lists** - Dynamic collections
- **Dictionaries** - Key-value pairs
- **Sets** - Unique elements
- **Queues & Stacks** - FIFO/LIFO structures
- **Generics** - Type-safe collections

### Level 4: Advanced Topics
- **LINQ** - Language Integrated Query
- **Delegates** - Function pointers
- **Events** - Publisher-subscriber pattern
- **Exception Handling** - Try/catch/finally
- **File I/O** - Reading/writing files
- **Async/Await** - Asynchronous programming
- **Reflection** - Type introspection

---

## 💡 Core Concepts

### OOP Principles

**Encapsulation**
```csharp
public class Person
{
    private string name;
    public string Name { get; set; }
}
```

**Inheritance**
```csharp
public class Animal { }
public class Dog : Animal { }
```

**Polymorphism**
```csharp
public virtual void Speak() { }
public override void Speak() { Console.WriteLine("Woof"); }
```

**Abstraction**
```csharp
public abstract class Shape
{
    public abstract void Draw();
}
```

### Collections Example
```csharp
// List
List<int> numbers = new List<int> { 1, 2, 3 };

// Dictionary
Dictionary<string, int> ages = new Dictionary<string, int>
{
    { "John", 30 },
    { "Jane", 25 }
};

// LINQ Query
var adults = ages.Where(x => x.Value >= 18).ToList();
```

---

## 🎓 Learning Path

```
1. Fundamentals (4-6 hours)
   ↓
2. OOP Concepts (6-8 hours)
   ↓
3. Collections (4-5 hours)
   ↓
4. Advanced Topics (8-10 hours)
   ↓
5. Build a Project (Practice all concepts)
```

---

## 🔨 Practical Exercises

**Beginner**
- Calculator application
- Student grade system
- To-do list manager

**Intermediate**
- Library management system
- Bank account simulator
- Employee payroll system

**Advanced**
- Game (console-based)
- Web API server
- Data analysis tool

---

## 📊 Project Statistics

- **Modules**: 4 major sections
- **Code Files**: 30+
- **Examples**: 50+
- **Exercises**: 40+
- **Estimated Time**: 30-40 hours

---

## 🎯 Skills You'll Gain

✅ C# programming proficiency  
✅ OOP design skills  
✅ Problem-solving abilities  
✅ Code organization  
✅ Debugging techniques  
✅ Best practices knowledge  
✅ .NET ecosystem understanding  
✅ Foundation for advanced .NET (ASP.NET, EF Core)  

---

## 📖 Common Mistakes to Avoid

- ❌ Not using proper naming conventions
- ❌ Ignoring exception handling
- ❌ Creating deep inheritance hierarchies
- ❌ Not using interfaces properly
- ❌ Memory leaks with unmanaged resources
- ❌ Ignoring async/await patterns

---

## 🚀 Next Steps

After mastering these fundamentals:
- Learn ASP.NET Core for web development
- Explore Entity Framework for databases
- Study design patterns
- Build real-world applications
- Contribute to open-source .NET projects

---

## 🐛 Debugging Tips

- Use Visual Studio debugger
- Set breakpoints
- Watch variables
- Use Debug.WriteLine() for logging
- Check Exception details
- Profile for performance issues

---

## 👤 Author

**Muhammad Tabish**  
GitHub: [@Muhammad-Tabish-123](https://github.com/Muhammad-Tabish-123)

---

## 📚 Related Repositories

- [SQL-Practice-Basic](https://github.com/Muhammad-Tabish-123/SQL-Practice-Basic) - Database fundamentals
- [Js-practice](https://github.com/Muhammad-Tabish-123/Js-practice) - JavaScript guide
- [NodeJS-Practice-Basic](https://github.com/Muhammad-Tabish-123/NodeJS-Practice-Basic) - Backend development

---

## 📖 Additional Resources

- [Microsoft C# Documentation](https://docs.microsoft.com/dotnet/csharp/)
- [C# Yellow Book](https://www.robmiles.com/c-yellow-book)
- [LeetCode C# Problems](https://leetcode.com/)
- [Microsoft Learn Path](https://learn.microsoft.com/)

---

*Last Updated: September 14, 2026*