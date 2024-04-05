# Floor Function:
a.k.a the greatest integer function
$f(x) = \lfloor x \rfloor$ if $x > 0$ truncate (drop) fractional part of the number.

$f(x) = \lfloor 10.5 \rfloor = 10$  On a number line the first integer at or to the left of x

# Ceiling Function:
a.k.a least integer function

$g(x) = \lceil x \rceil$ smallest int $\geq$ x

$g(x) = \lceil 2.75 \rceil = 3$ if x > 0 round up

## Example:

$\lceil \lfloor 0.5 \rfloor - 0.66 \rceil = 0$ 

Note: both functions are graphed with a slightly varied step function. 

## Example Application of F & C Functions

A process that outputs 83bits and stores it in memory. If we want to know haw many bytes to reserve (1 byte = 8 bits) so $\lceil 83 / 8 \rceil = 11$ which is how may bytes you will reserve. 

# Inverse of a Function

$f: x \to y$ is one to one and onto (bijection) if it has in inverse.

**Example:** Does the following have an inverse?

$f(x) = 5x-4$  $f: \mathbb{R} \to \mathbb{R}$

yes it does! the inverse is: 

$x = {y + 4) \over 5}$ 
