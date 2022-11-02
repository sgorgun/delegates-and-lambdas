# Delegates and Lambdas (in progress!)

Intermediate level task for practicing delegates and lambdas. 

Estimated time to complete the task - 3h.  

The task requires .NET 6 SDK installed.   

## Task Description

The task has 5 sub-tasks. Each sub-task is a small coding exercise.

<details>
<summary>

**Sub-task #1**

</summary>
      
- Open the [FunctionExtensions.cs]() file, and navigate to the [GenerateProgression]() method.

- Implement a generator of the first `n` elements of a sequence which is created by recurrent formula:   

   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$
  
- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #2**

</summary>

- Open the [FunctionExtensions.cs]() file, and navigate to the [GenerateProgression]() method.

- Implement a generator of the elements of a sequence which is created by recurrent formula: 

   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

   The number of elements that were generated is defined by the condition.

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #3**

</summary>

- Open the [FunctionExtensions.cs]() file, and navigate to the [GenerateProgression]() method.

- Implement a generator of the `n`s element of a sequence which is created by recurrent formula: 
   
   $`x_1=a, x_{n+1}=f(x_n), n = 1, 2, ...`$

- [Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences.

</details>

<details>
<summary>

**Sub-task #4**

</summary>

</details>

<details>
<summary>

**Sub-task #5**

</summary>

- Open the [FunctionExtensions.cs]() file, and navigate to the [GenerateProgression]() method.

- Implement a generator of the first `n` elements of a sequence which is created by recurrent formula:   

   $`x_1 = a, x_2 = b, x_{n+1}=f(x_n, x_{n - 1}), n = 2, 3, ...`$
  
The following sequences are used as test sequences.

   $`x_1 = 1, x_2 = 1, x_{n + 1} = x_n +  x_{n - 1}, n = 2, 3, ... T`$ - integer type;     
   $`x_1 = 1, x_2 = 2, x_{n + 1} = 6 x_n - 8 x_{n - 1}, n = 2, 3, ... T`$ - integer type;    
   $`x_1 = 1, x_2 = 2, x_{n + 1} = x_n +  x_{n - 1} / x_{n}, n = 2, 3, ... T`$ - real type.

</details>
