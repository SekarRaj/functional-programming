# Category Theory

Category is in Mathematics what Generics is in programming. Branch of mathematics that can be grouped into based on their behaviour is considered as category.

It is much easier to explain Category theory in terms of Set theory. Category and Set are used interchangiblty in this context. 


## Primary properties of Categories
Composition
Identity

Types(reffered in context as Set) and Functions are categories in programming.

## Pure/Total Functions
Pure or Total Functions - Defined for all possible arguments. Pure functions can be memoised. Serves as the basic abstractions from which complex functions are created.

Relation between set can be one to one, one to many or many to many. On the other hand for a function many to one or many to many should not be possible. Also for a function there must be mapping for every argument in a domain there must be related mapping in the codomain, the vice verse is not necessary i.e. inverse of a function. 

f::a -> b = Means functions goes from set `a` to set `b`.

if there exist a function g::b -> a, then this is considered as the invere of the function. `g*f` and `f*g` will be identity of the category.
Functions that are invertible (unique mapping between the categories) is called **Isomorphism**

> Fibration : Subtopic in Category Theory. Multiple elements of Sat mapping to single element in another set is called fibres.

Function that does not collapse is called *injective function* or *injections*. One to one mapping between categories.
Function that covers the whole of co-domain is called *surjective function*.
Funtion that is *surjective* and *injective* then it is a *isomorphic* function.


In terms of Category Theory,
*Surjective* category of functions is called *epimorphism* or *epic morphism*.
*Injective* category of functions is called *monomorphism* or *monic morphism*. 

