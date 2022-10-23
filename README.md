

<img src="https://github.com/sirin-koca/Java-Basics/blob/master/img/recursion.jpeg" width="800">
<sub>Photo by Taras Chernus on Unsplash</sub>


## Recursive Data Structure
- A recursive data structure is an object or class that contains an abstraction of itself.
- In mathematical terms, we say that the object is "isomorphic" to itself. The basics of a recursive data structure is the Composite Design pattern. Recursive data structures enable us to represent repetitive abstract patterns. In such, they enable us to generate or represent complexity from simplicity.

## Recursive Algorithm
- A recursive algorithm is a process that accomplishes its task, in part, by calling an abstraction of itself
- The similarity between recursive algorithms and recursive data structures is because in an OO system, the structure drives the algorithm. 
- A recursive processes or data structure is defined in terms of itself. A properly written recursive function must handle the base case, and convergence to the base case. Failure to properly handle the base case or converge to the base case (divergence) may result in infinite recursion.

## Recursive Method
- Recursion is a method in OOP which calls itself directly or indirectly until a suitable condition is met. 
- Recursion is the technique of making a function call itself. This technique provides a way to break complicated problems down into simple problems which are easier to solve.
- To prevent infinite recursion, you need at least one branch (i.e. of an if/else statement) that does not make a recursive call. Branches without recursive calls are called base cases; branches with recursive calls are called recursive cases.


_E.g. A Recursive Factorial Function_

```
public static int fac(int n) {
  if (n <= 1) {
  return 1;
  } else {
  return n * fac(n - 1);
  }
}


// Et annet eksempel på rekursiv metode:
// Euklids algoritme for det største felles divisor

  public static int euklid(int a, int b)
  {
    if (b == 0) return a;
    int r = a % b;            // r er resten
    return euklid(b,r);       // rekursivt kall
  }
     
      
   \  :  /
`. __/ \__ .'
_ _\     /_ _
   /_   _\
 .'  \ /  `.
   /  :  \    
      

```

