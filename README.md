# Delegates and Lambdas (in progress!)

Intermediate level task for practicing delegates and lambdas. 

Estimated time to complete the task - 3h.  

The task requires .NET 6 SDK installed.   

## Task Description

The task has ? sub-tasks. Each sub-task is a small coding exercise.

<details>
<summary>

**Sub-task #1**

</summary>
      
- Open the [FunctionExtensions.cs]() file.

- Implement a [GenerateProgression]() method that generates a sequence of the elements of type T according to the following recursive formula: 

   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$
  
- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #2**

</summary>

- Open the [FunctionExtensions.cs]() file.

- Implement a [GenerateProgression]() method that generates a sequence of the elements of type T according to the following recursive formula: 

   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

   The number of elements that were generated is defined by the condition.

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #3**

</summary>

- Open the [FunctionExtensions.cs]() file.

- Implement a [GetElement]() method that generates a `n`s element of the sequence of the elements of type T according to the following recursive formula: 
   
   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #4**

</summary>

- Open the [FunctionExtensions.cs]() file.

-Implement a method that applies a binary operation  $`operation(x, y)$ pairwise over the elements of a sequence 

- Sequence is created by recurrent formula: 
   
   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

- Operations of multiplication and addition are used as test.

</details>

<details>
<summary>

**Sub-task #5**

</summary>

- Open the [FunctionExtensions.cs]() file, and navigate to the [GenerateProgression]() method.

- Implement a generator of the first `n` elements of a sequence which is created by recurrent formula:   

   $`x_1 = a, x_2 = b, x_{n+1}=f(x_n, x_{n - 1}), n = 2, 3, ...`$
  
- The following sequences are used as test sequences.

   $`x_1 = 1, x_2 = 1, x_{n + 1} = x_n +  x_{n - 1}, n = 2, 3, ... T`$ - integer type;     
   $`x_1 = 1, x_2 = 2, x_{n + 1} = 6 x_n - 8 x_{n - 1}, n = 2, 3, ... T`$ - integer type;    
   $`x_1 = 1, x_2 = 2, x_{n + 1} = x_n +  x_{n - 1} / x_{n}, n = 2, 3, ... T`$ - real type.

</details>

<details>
<summary>

**Sub-task #6**

</summary>

- Open the [FunctionExtensions.cs]() file, and navigate to the [CombinePredicates]() method.

- Implement the `CombinePredicates` method for the generic delegate `Predicate<T>`, which allows you to combine several predicate conditions using the logical AND operation (&&).

</details>
