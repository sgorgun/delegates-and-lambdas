# Delegates and Lambdas (in progress!)

Intermediate level task for practicing delegates and lambdas.  
Estimated time to complete the task - 3h.  
The task requires .NET 6 SDK installed.   

## Task Description

The task has ? sub-tasks. Each sub-task is a small coding exercise.

#### Sub-task 1

Open the []() file, and navigate to the [GenerateProgression]() method.

Implement a generator of the `n`-first members of a sequence of the elements of the type `T` according to the following recurrence formula:   

$`x_{n+1}=f(x_n), n = 1, 2, ...`$

  
[Arithmetic](https://www.wikiwand.com/en/Arithmetic_progression) and [geometric](https://www.wikiwand.com/en/Geometric_progression) progressions are used as test sequences in the test project.

#### Sub-task 2

Open the []() file, and navigate to the []() method.

Implement a generic generator of the `n`-first members of a sequence of the elements of the type `T` according to the following recurrence formula:

   $`x_1 = a, x_2 = b, x_{n+1}=f(x_n, x_{n - 1}), n = 2, 3, ...`$
  
Check the generator work by using the following sequences:

   $`x_1 = 1, x_2 = 1, x_{n + 1} = x_n +  x_{n - 1}, n = 2, 3, ... T`$ - integer type;     
   $`x_1 = 1, x_2 = 2, x_{n + 1} = 6 x_n - 8 x_{n - 1}, n = 2, 3, ... T`$ - integer type;    
   $`x_1 = 1, x_2 = 2, x_{n + 1} = x_n +  x_{n - 1} / x_{n}, n = 2, 3, ... T`$ - real type.
