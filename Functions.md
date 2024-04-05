# Vocab / Terms

**Codomain:** All the possible values that the function could be mapped to.

**Range:** All of the values that the function does map to.

**One-to-one:** Where each input is mapped to a unique output. 

**Onto Function (surjection):** Every element in the codomain gets mapped to by an element in the domain.

**Well defined Functions:** a function thats x values have more than one y value

# One-to-One
How do the sizes of D, C, and R compare when the function is one-to-one.
D - domain
C - codomain
R  - range

$$|D| \le |C|$$
$$|D| = |R|$$

Does $|D| = |R|$ imply that a function is one to one? 
YES, if both $D$ and $C$ are finite. 

# Onto Function
How do the sizes of D, C, and R compare when the function is onto.
D - domain
C - codomain
R  - range

$|D|\geq |C|$
$|C| = |R|$

# Well Defined Functions
1) A function is not well defined when there a multiple outputs for the same inputs. (vertical line test)
2) When there is at least one input that is not mapped to anything / does not have an output
# Examples:

## In math

**Example 1:**
$$
f(x) = 2x \text{ on } \mathbb{Z}^+ \to \mathbb{Z}^+
$$
This example is one-to-one because no two elements map to the same however, this example is not onto because this function only maps even numbers.

**Example 2:**
$$
f(x) = x^2 \text{ on } \mathbb{Z} \to \mathbb{Z}
$$
This example is not one to one because $f(1) = f(-1)$ fails the horizontal line test.

**Example 3:**
$$
f(x) = 2x \text{ on } \mathbb{R} \to \mathbb{R}
$$
This function is one-to-one (injective) and onto (surjective), or a bijection. 
## In coding

**Example 1:**
```java
float square (float num){
	// statements
	
} return y;
```

Here the argument is the domain because it sets the data type 
The codomain is the return value or 'float'

**Example 2:**
here is an example of a poorly defined function in code

```java
float squareroot(float x){
	return squrt.x
}
```

Here the issue is that there are negative inputs are in the domain but aren't mapped to any output.

Here is a corrected version:
```java
float squareroot(float x){
	if (x < 0){
		return error
	} else {
	return math.squrt(x)
	}
}
```