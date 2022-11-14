# Delegates and Lambdas

Intermediate level task for practice delegates and lambdas. 

Estimated time to complete the task - 2h.  

The task requires .NET 6 SDK installed.   

## Task Description

The task has 7 sub-tasks. Each sub-task is a small coding exercise.

<details>
<summary>

**Sub-task #1**

</summary>
      
- Open the [FunctionExtensions.cs](Delegates/FunctionExtensions.cs) file.

- Implement a generic `GenerateProgression` method that generates a sequence of the elements of type `T` using the following recurrent formula: 

   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

   The count of requested elements is defined by the given number.
  
- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #2**

</summary>

- Open the [FunctionExtensions.cs](Delegates/FunctionExtensions.cs) file.

- Implement a generic `GenerateProgression` method which generates a sequence of the elements of type `T` using the following recurrent formula: 

   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

   The count of requested elements is defined by the condition.

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #3**

</summary>

- Open the [FunctionExtensions.cs](Delegates/FunctionExtensions.cs) file.

- Implement a generic `GetElement` method which generates a `n`s element of the sequence using the following recurrent formula: 
   
   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #4**

</summary>

- Open the [FunctionExtensions.cs](Delegates/FunctionExtensions.cs) file.

- Implement a generic `Calculate` method which calculates a `value` as a composition of sequentially executed binary operation $`operation(x, y)`$ on the elements of the sequence by the rule:

   $`value = operation(x_1, x_2)`$, $`value = operation(value, x_3)`$,  ... , $`value = operation(value, x_n)`$

- The elements of the sequence are generated by recurrent formula: 
   
   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

   The count of requested elements for the calculation is defined by the given number.

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

- Multiplication and addition operations are used as test operations.

</details>

<details>
<summary>

**Sub-task #5**

</summary>

- Open the [FunctionExtensions.cs](Delegates/FunctionExtensions.cs) file.

- Implement a generic `GenerateSequence` method which generates a sequence of the elements of type `T` using the following recurrent formula: 

   $`x_1 = a, x_2 = b, x_{n+1}=f(x_n, x_{n - 1}), n = 2, 3, ...`$

   The count of requested elements is defined by the given number.
     
- The following sequences are used as test sequences.

   $`x_1 = 1, x_2 = 1, x_{n + 1} = x_n +  x_{n - 1}, n = 2, 3, ...`$, where `T` - integer type;     
   $`x_1 = 1, x_2 = 2, x_{n + 1} = 6 x_n - 8 x_{n - 1}, n = 2, 3, ...`$, where `T` - integer type;    
   $`x_1 = 1, x_2 = 2, x_{n + 1} = x_n +  x_{n - 1} / x_{n}, n = 2, 3, ...`$, where `T` - real type.

</details>

<details>
<summary>

**Sub-task #6**

</summary>

- Open the [FunctionExtensions.cs](Delegates/FunctionExtensions.cs) file.

- Implement the generic `FindMax` method which finds maximum from two elements of the type `T` according to comparer logic.

</details>

<details>
<summary>

**Sub-task #7**

</summary>

- Open the [FunctionExtensions.cs](Delegates/FunctionExtensions.cs) file.

- Implement the generic `CombinePredicates` method which allows to combine several predicate conditions using the logical AND operation (&&).

</details>

The detailed explanations of the task are provided in the XML-comments for the methods and in test cases of unit tests.

## Task Checklist

* Build a solution in [Visual Studio](https://docs.microsoft.com/en-us/visualstudio/ide/building-and-cleaning-projects-and-solutions-in-visual-studio?view=vs-2019). Make sure there are **no compiler errors and warnings**, fix these issues and rebuild the solution. 
* Run all unit tests with [Visual Studio](https://docs.microsoft.com/en-us/visualstudio/test/run-unit-tests-with-test-explorer?view=vs-2019) and make sure there are **no failed unit tests**. Fix your code to [make all tests GREEN](https://stackoverflow.com/questions/276813/what-is-red-green-testing). 
* Review all your changes in the codebase **before** [staging the changes and creating a commit](https://docs.microsoft.com/en-us/azure/devops/repos/git/commits?view=azure-devops&tabs=visual-studio). 
* [Stage your changes, create a commit](https://docs.microsoft.com/en-us/azure/devops/repos/git/commits?view=azure-devops&tabs=visual-studio), and publish your changes to the remote repository. 

## See also

- [Delegates (C# Programming Guide)](https://learn.microsoft.com/en-us/previous-versions/visualstudio/visual-studio-2010/ms173171(v=vs.100))
- [Using Delegates (C# Programming Guide)](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/delegates/using-delegates )
- [How to declare, instantiate, and use a Delegate (C# Programming Guide)](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/delegates/how-to-declare-instantiate-and-use-a-delegate)
- [Generic Delegates (C# Programming Guide)](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/generics/generic-delegates)
- [Strongly Typed Delegates](https://learn.microsoft.com/en-us/dotnet/csharp/delegates-strongly-typed)
- [Comparison<T> Delegate](https://learn.microsoft.com/en-us/dotnet/api/system.comparison-1?view=net-7.0)
- [Lambda expressions (C# reference)](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-expressions)
