# Delegates and Lambdas (in progress!)

## 


Implement a generic generator of the `n`-first members of a sequence of the elements of the type `T` according to the following recurrence formula:

   $`x_1 = a, x_2 = b, x_{n+1}=f(x_n, x_{n - 1}), n = 2, 3, ...`$
  
Check the generator work by using the following sequences:

   $`x_1 = 1, x_2 = 1, x_{n + 1} = x_n +  x_{n - 1}, n = 2, 3, ... T`$ - integer type;     
   $`x_1 = 1, x_2 = 2, x_{n + 1} = 6 x_n - 8 x_{n - 1}, n = 2, 3, ... T`$ - integer type;    
   $`x_1 = 1, x_2 = 2, x_{n + 1} = x_n +  x_{n - 1} / x_{n}, n = 2, 3, ... T`$ - real type.
