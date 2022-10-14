
## Recursive Data Structure
- A recursive data structure is an object or class that contains an abstraction of itself.
- In mathematical terms, we say that the object is "isomorphic" to itself. The basic embodiment of a recursive data structure is the Composite Design pattern. Recursive data structures enable us to represent repetitive abstract patterns. In such, they enable us to generate or represent complexity from simplicity.

## Recursive Algorithm
- A recursive algorithm is a process that accomplishes its task, in part, by calling an abstraction of itself
- The similarity between recursive algorithms and recursive data structures is because in an OO system, the structure drives the algorithm. 
- A recursive processes or data structure is defined in terms of itself. A properly written recursive function must handle the base case, and convergence to the base case. Failure to properly handle the base case or converge to the base case (divergence) may result in infinite recursion.

## Recursive Method
- Recursion is a method in OOP which calls itself directly or indirectly until a suitable condition is met. 
- Recursion is the technique of making a function call itself. This technique provides a way to break complicated problems down into simple problems which are easier to solve.

_E.g. A Recursive Factorial Function_

```
public static int fac(int n) {
  if (n <= 1) {
  return 1;
  } else {
  return n * fac(n - 1);
  }
}

      ,
   \  :  /
`. __/ \__ .'
_ _\     /_ _
   /_   _\
 .'  \ /  `.
   /  :  \    
      '

```

