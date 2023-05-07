Download Link: https://assignmentchef.com/product/solved-listiterator
<br>
Given two nonempty sorted lists, L1 and L2.

(a) a following method in Java that prints true if L2 ⊆ L1, and false otherwise. In

your implementation you can use only the basic list operators (next(), hasNext(), and

compareTo()).

Remember that L2 ⊆ L1 if for all x ∈ L2, x ∈ L1.

public static &lt;AnyType extends Comparable&lt;? super AnyType&gt;&gt;

boolean subset(List&lt;AnyType&gt; L1, List&lt;AnyType&gt; L2)

{

ListIterator&lt;AnyType&gt; iterL1 = L1.listIterator();

ListIterator&lt;AnyType&gt; iterL2 = L2.listIterator();

// get first item in each list

if ( iterL1.hasNext() &amp;&amp; iterL2.hasNext() )

{

itemL1 = iterL1.next();

itemL2 = iterL2.next();

}

// YOUR CODE GOES HERE

}

(b) What is the running time complexity of your method?