# comp5421-assignment-3-adt-and-operator-overload-solved
**TO GET THIS SOLUTION VISIT:** [COMP5421 Assignment 3-ADT and Operator Overload Solved](https://www.ankitcodinghub.com/product/comp5421-assignment-3-adt-and-operator-overload-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99982&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5421 Assignment 3-ADT and Operator Overload Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Objectives

􏰀 To experience creating an abstract data type (ADT)

􏰀 To implement an ADT in C++, using the operator overloading facility of the C++ language 􏰀 To learn how to turn objects of a class into “function objects”

􏰀 To learn how to convert objects of a class to objects of unrelated types (e.g., Foo to bool)

2 Background

A data type represents a set of data values sharing common properties. An abstract data type (ADT) specifies a set of operations on a data type, independent of how the data values are actually represented or how the operations are implemented.

Classic ADTs representing mathematical entities such as rational number and complex number ADTs support many arithmetic, relational and other operations, making them ideal data types for operator overloading.

Since there is no shortage of code for C++ classes representing rational and complex numbers, assignments designed to provide practice with operator overloading tend to get a bit creative with their choice of data types; ideally, a data type that is not as ubiquitous as rational and complex number ADTs, but one that lends itself to operator overloading just as good.

3 Mat2x2 ADT

</div>
</div>
<div class="layoutArea">
<div class="column">
Mat2x2 is an ADT that encapsulates a “2 × 2 matrix”, a simple mathematical entity of the form 􏰃a b􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
c d , where the numbers a, b, c, and d represent the “value” of a 2 × 2 matrix data type.

</div>
</div>
<div class="layoutArea">
<div class="column">
For example, the numbers 4, 8, 7, and 3 together can represent the value of the 2 × 2 matrix 􏰃4 8􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
73.

3.1 Notation

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰃a b􏰄 􏰃1 0􏰄 􏰃x 0􏰄

A= c d ,I= 0 1 ,xI= 0 x =Ix,xarealnumber,amultiplicativescalar

􏰃a′b′􏰄 􏰃11􏰄 􏰃xx􏰄

B= c′ d′ ,J= 1 1 ,xJ= x x =Jx,xarealnumber,anadditivescalar

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3.2 Operations

Scalar Multiplication Ax = xA = xIA = cx dx

</div>
</div>
<div class="layoutArea">
<div class="column">
Scalar Addition Scalar Subtraction

addition

subtraction

multiplication

determinant

inverse

division Norm

Relational Equality

Relational Inequality

</div>
<div class="column">
x+A=xJ+A= x+c x+d , A+x=x+A 􏰃x − a x − b􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰃ax bx􏰄 􏰃x+a x+b􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
x−A=xJ−A= x−c x−d , A−x=−(x−A) 􏰃a b􏰄 􏰃a′ b′􏰄 􏰃a+a′ b+b′􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
A+B= c d + c′ d′ = c+c′ d+d′ 􏰃a b􏰄 􏰃a′ b′􏰄 􏰃a−a′ b−b′􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
A−B= c d − c′ d′ = c−c′ d−d′ 􏰃a b􏰄 􏰃a′ b′􏰄 􏰃aa′ +bc′ ab′ +bd′􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
AB= c d ∗ c′ d′ = a′c+c′d b′c+dd′ 􏰃a b􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
det(A) = det c d = ad − bc

−1 􏰃ab􏰄 1􏰃d−b􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
A =inv(A)=inv c d =det(A) −c a , det(A)̸=0 A/B = AB−1, det B ̸= 0

</div>
</div>
<div class="layoutArea">
<div class="column">
||A||=norm(A)=􏰅a2 +b2 +c2 +d2 A = B iff ||A − B|| ≤ ε.

The symbol ε denotes a tolerance, a small positive amount the value ||A − B|| can change and still be acceptable that A is equal to B.

A &lt; B if ¬(A = B) and ||A|| &lt; ||B||

where ¬ denotes the negation operator.

Recall that the definitions of the operators &lt; and = on objects X and Y are sufficient for deriving the definitions of the other four relational operators &gt;, ≥, ̸=, and ≤:

􏰀 X&gt;Y ≡Y &lt;X 􏰀 X̸=Y ≡¬(X=Y)

􏰀 X≥Y ≡¬(X&lt;Y) 􏰀 X≤Y ≡X&lt;Y orX=Y

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 2 of 15

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
4 Your Task

Implement the Mat2x2 ADT above using a C++ class, called Mat2x2, that uses one of the representations listed in section 5 to store the underlying data as private member(s).

The public interface of your Mat2x2 class must include the following member functions:

<ol>
<li>Constructors:
<pre>     explicit Mat2x2(double = 0, double = 0, double = 0, double = 0);
</pre>
<pre>     Mat2x2(const array&lt;double, 4&gt; &amp;);          // using std::array;
</pre>
<pre>     Mat2x2(const array&lt;array&lt;double, 2&gt;, 2&gt;&amp;); // using std::array;
</pre>
<pre>     Mat2x2(const initializer_list&lt;double&gt;);    // using std::initializer_list;
</pre>
</li>
<li>Defaulted copy/move constructors, copy/move assignment operators, and destructor.</li>
<li>norm(), returns the norm of the calling object</li>
<li>inverse(), returns the inverse of the calling object</li>
<li>det(), returns the determinant of the calling object</li>
</ol>
4.1 Member Operator Overload Functions

<ol start="6">
<li>Compound assignment operator overloads. Mat2x2opMat2x2 x+=y,x-=y,x*=y,x/=y Mat2x2opdouble x+=k,x-=k,x*=k,x/=k</li>
<li>Unary operators ++x, x++, +x, –x, x–, -x, where x is a Mat2x2 object.</li>
<li>An overloaded XOR operator^ such that x^k returns the Mat2x2 object resulting from
raising x to the power k (an integer). It does not modify x.
</li>
<li>Subscript operators [ ], both const and non-const overloads. If subscript is invalid, must
throw: invalid argument(“index out of bounds”)

These operator overloads provide direct access to the underlying data members, effectively

eliminating the need for friend functions.
</li>
<li>operator bool() const Returns whether or not the invoking object has inverse. For example, if x is a Mat2x2 object, it returns true if |x.det()| &gt; ε, and returns false otherwise.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 3 of 15

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
4.2 Function objects

Overloading the function call operator, these overloads effectively turn Mat2x2 objects into functions; hence the name “function object.”

<ol start="11">
<li>double operator()()const Returns the norm of the invoking Mat2x2 object. For ex- ample, if x is a Mat2x2 object, then x() returns x.norm().</li>
<li>double&amp; operator()(size t r, size t c)

Returns an lvalue reference to the entry at row r and column c.

Since it would be more intuitive for humans to start row and column indexing at 1, this function must ensure that the values of r and c are 1-based.

x12 􏰄

x , then x(i, j) should return a reference

22
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
For example, if x stores the matrix x 21

to xij , i = 1, 2, j = 1, 2.

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰃x11

</div>
</div>
<div class="layoutArea">
<div class="column">
If r or c is invalid, then this function must throw an exception as shown below: 1

2

1 2 3

<ol>
<li>Overloaded extraction operator &gt;&gt; for reading Mat2x2 values</li>
<li>Overloaded insertion operator &lt;&lt; for writing Mat2x2 values</li>
<li>Basic arithmetic operators. None modifies it operands. Not all can be implemented as members (which ones?). For consistency, all are typically implemented as free functions.
Mat2x2opMat2x2 x+y,x-y,x*y,x/y Mat2x2opdouble x+k,x-k,x*k,x/k doubleopMat2x2 k+y,k-y,k*y,k/y
</li>
<li>Relational operators. None modifies it operands. For consistency, all are typically imple- mented as free functions.
Mat2x2opMat2x2 x&lt;y,x&lt;=y,x&gt;y,x&gt;=y,x==y,x!=y

Assignment 3, Summer 2021, page 4 of 15
</li>
</ol>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>if (r &lt; 1 || r &gt; 2) throw invalid_argument("row index out of bounds");
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>if (c &lt; 1 || c &gt; 2) throw invalid_argument("column index out of bounds");
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
4.3 static Members

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>static double tolerance; // initial value = 1.0E-6
static void setTolerance(double tol);
static double getTolerance();
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
See Relational Equality in section 3.2 where “tolerance” is defined.

4.4 Non-Member Operator Overload Functions

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
5 Alternative Representations for a 2 × 2 Matrix

Applying the OOP’s principle of information hiding, an implementation of an ADT can optimize both representation of the data type and implementation of the operations without affecting the client code.

However, since an ADT does not depend on the representation of the data type it specifies, the first order of business for any implementation of an ADT is to define concrete representation of the data type so that the operations on the type can be implemented.

􏰃a b􏰄 The examples below show three common representations of a 2 × 2 matrix c d :

</div>
</div>
<div class="layoutArea">
<div class="column">
Eaxmple 1:

</div>
<div class="column">
Viewing the 2 × 2 matrix as four individual elements a, b, c, and d:

For the benefit of human readers of the code, such representation must explicitly document the correspondence between the matrix elements and the variable a, b, c, and d.

Viewing the 2 × 2 matrix as a sequence (y0, y1, y2, y3)

For storing and managing any sequence of const size, modern C++ provides a

smart array class template in the &lt;array&gt; header file:

1 std::array &lt;double, 4&gt; y; // an array of 4 doubles

std::array provides a rich set of useful methods as well as supporting the familiar array notation y[0], y[1], y[2], and y[3].

This representation too must document the correspondence between the matrix elements and the variable y[0], y[1], y[2], and y[3].

􏰃􏰁x00 x01􏰂􏰄 􏰁􏰁 􏰂 􏰁 􏰂􏰂 Viewing the 2×2 matrix as 􏰁x10 x11􏰂 , or as x00 x01 x10 x11 , as an

array of two rows, each in turn an array of two elements.

1 2 3

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>double a; // top-left
double b; // top-right
double c; // bottom-left
double d; // bottom-right
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Eaxmple 2:

</div>
</div>
<div class="layoutArea">
<div class="column">
1 2 3 4

</div>
</div>
<div class="layoutArea">
<div class="column">
Eaxmple 3:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>std::array&lt; std::array &lt;double, 2&gt;, 2&gt; x;
// x is an array of size 2;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// each element of x is an array of 2 doubles;
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Note that x is a std::array of std::arrays, representing a two-dimensional table or matrix of doubles.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 5 of 15

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Overloading the subscript operator [], std::array provides the familiar array notation. Specifically, the two elements (the rows) x[0] and x[1] of the 2D-array x are each of type std::array&lt;double, 2&gt;, and as such, x[0]’s two elements on the first row are x[0][0], and x[0][1], and x[1]’s two elements on the second row are x[1][0], and x[1][1].

5.1 What About Multi-Dimensional Raw Arrays?

C++ does not provide a special multi-dimensional raw array type. Instead, C++ provides only one-dimensional array type, but it allows the array elements themselves to be “one-dimensional arrays”.

For example, denoting a two-dimensional 5 × 3 array of 5 rows and 3 columns, the declaration double A[5][3] means that A is a one-dimensional array of 5 elements, each of which, in turn, is an array of 3 doubles. Specifically,

A[0] points to an array of 3 elements A[0][0], A[0][1], A[0][2] on row 1,

A[1] points to an array of 3 elements A[1][0], A[1][1], A[1][2] on row 2, and in general, A[r] points to an array of 3 elements A[r][0], A[r][1], A[r][2] on row r+1.

Similarly, the declaration double B[3][4][5] declares B as an array of size 3 whose elements are each arrays of size 4 whose elements are each arrays of 5 doubles.

Question 1

Write a declaration for a function named process2D that is to receive and process a raw array of 7 raw arrays, each of 5 doubles.

Question 2

Write a declaration for a function named process3D that is to receive and process a three-dimensional 5 × 3 × 7 array of integers.

5.2 Prefer std::arrays to Raw Arrays

Given std::array&lt;T,n&gt; container, a smart class template modeling an array of fixed size n and

elements of type T, there is really no good reason to use raw arrays in C++. The justification for this is that a std::array&lt;T,n&gt; object

􏰀 stores and can tell the size of the array,

􏰀 provides bounds checking facilities,

􏰀 can be passed as an argument to a function without decaying to a pointer, 􏰀 can be used by any algorithm designed to work with C++ container classes, 􏰀 provides the familiar raw array notation (by overloading the [] operator),

􏰀 and more.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 6 of 15

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
6 Deliverables

1. Header files: Mat2x2.h

2. Implementation files: Mat2x2.cpp, Mat2x2 test driver.cpp 3. A README.txt text file (as described in the course outline).

7 Grading scheme

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Functionality

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
􏰀 Correctness of execution of your program,

􏰀 Proper implementation of all specified requirements, 􏰀 Efficiency

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
60%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
OOP style

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>􏰀 &nbsp;Encapsulating only the necessary data inside your objects,</li>
<li>􏰀 &nbsp;Information hiding,</li>
<li>􏰀 &nbsp;Proper use of C++ constructs and facilities.</li>
<li>􏰀 &nbsp;No global variables</li>
<li>􏰀 &nbsp;No use of the operator delete.</li>
<li>􏰀 &nbsp;No C-style memory functions such as malloc, alloc, realloc,
free, etc.
</li>
</ul>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
20%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Documentation

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
􏰀 Description of purpose of program,

􏰀 Javadoc comment style for all methods and fields, 􏰀 Comments for non-trivial code segments

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
10%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Presentation

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
􏰀 Format, clarity, completeness of output, 􏰀 User friendly interface

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
5%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Code readability

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Meaningful identifiers, indentation, spacing

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
5%

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 7 of 15

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
8

</div>
<div class="column">
Sample Test Driver

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#include &lt;iostream&gt;
#include &lt;iomanip&gt;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#include &lt;string&gt;
#include &lt;cassert&gt;
#include "Mat2x2.h"
using std::cout;
using std::cin;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>using std::endl;
</pre>
<pre>/*
Tests class Mat2x2 . Specifically, tests constructors, compound assignment
operator overloads, basic arithmetic operator overloads, unary +, unary -,
pre/post-increment/decrement, subscripts, function objects,
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>input/output operators, and relational operators.
@return 0 to indicate success.
*/
</pre>
int main()

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>{
   const Mat2x2  ZERO;
   // must not compile, because zero is const
   //ZERO[1] = 0;
   //ZERO[2] = 0;
   //ZERO[3] = 0;
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36 37 38 39 40 41 42 43 44

</div>
<div class="column">
<pre>//ZERO[4] = 0;
</pre>
<pre>const Mat2x2  IDENTITY(1, 0, 0, 1);
// ctor that takes an std::initializer_list&lt;double&gt;
</pre>
<pre>Mat2x2 a = { 11, 22, 33, 44, 55, 66.5 }; // notice intentional too many initializers
</pre>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>cout &lt;&lt; "a = " &lt;&lt; a &lt;&lt; endl;
assert(a == Mat2x2(11, 22, 33, 44));
</pre>
<pre>Mat2x2 b{ 111,222.7,333 };
cout &lt;&lt; "b = " &lt;&lt; b &lt;&lt; endl;
assert(b == Mat2x2(111, 222.7, 333, 0));
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2 c{ 1234 };
cout &lt;&lt; "c = " &lt;&lt; c &lt;&lt; endl;
assert(c == Mat2x2(1234, 0, 0, 0));
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// a conversion constructor
Mat2x2 d(1234);       // int -&gt; Mat2x2 // [1234, 0, 0, 0]
cout &lt;&lt; "d = " &lt;&lt; d &lt;&lt; endl;
assert(d == Mat2x2(1234, 0, 0, 0));
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 8 of 15

</div>
</div>
</div>
<div class="page" title="Page 9">
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2  e;
cout &lt;&lt; "e = " &lt;&lt; e &lt;&lt; endl;
assert(e == ZERO);
</pre>
<pre>Mat2x2  f(2);
cout &lt;&lt; "f = " &lt;&lt; f &lt;&lt; endl;
</pre>
</div>
<div class="column">
<pre>// default ctor
// cout &lt;&lt; Mat2x2
// Mat2x2  == Mat2x2
</pre>
<pre>// normal ctor with 1 arg
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(f == Mat2x2(2, 0, 0, 0));
</pre>
<pre>Mat2x2  g(2, 3);                     // normal ctor with 2 args
cout &lt;&lt; "g = " &lt;&lt; g &lt;&lt; endl;
assert(g == Mat2x2(2, 3, 0, 0));
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2  h(2, 3, 8);                  // normal ctor with 3 args
cout &lt;&lt; "h = " &lt;&lt; h &lt;&lt; endl;
assert(h == Mat2x2(2, 3, 8, 0));
</pre>
<pre>Mat2x2  m1(2.5, 3.6, 8.7, 5.8);                // normal ctor with 4 args
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2   m1_inverse = m1.inverse();            // inverse, copy ctor
</pre>
<pre>Mat2x2  m1_inverse_times_m1 = m1_inverse * m1; // Mat2x2  * Mat2x2
assert(m1_inverse_times_m1 == IDENTITY);       // invariant, must hold
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2  m1_times_m1_inverse = m1 * m1_inverse;
assert(m1_times_m1_inverse == IDENTITY);
</pre>
<pre>assert(+m1 == -(-m1));
Mat2x2  t1 = m1;
++m1;
</pre>
</div>
<div class="column">
<pre>// invariant, must hold
// +Mat2x2 , -Mat2x2
// ++Mat2x2
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(m1 == t1 + 1);
--m1;                                          // --Mat2x2
assert(m1 == t1);
</pre>
<pre>Mat2x2  m1_post_inc = m1++;                    // Mat2x2 ++
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(m1_post_inc == t1);
assert(m1 == t1 + 1);
</pre>
<pre>Mat2x2  m1_post_dec = m1--;                    // Mat2x2 --
assert(m1_post_dec == t1 + 1);
assert(m1 == t1);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>cout &lt;&lt; "\n";
h += Mat2x2(0, 0, 0, 5);               // Mat2x2  += Mat2x2
Mat2x2  m2 = h + 1.0;                  // Mat2x2  = Mat2x2 + int
assert(m2 == Mat2x2(3, 4, 9, 6));
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>cout &lt;&lt; "m2 = " &lt;&lt; m2 &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
45 46 47 48 49 50 51 52 53 54 55 56 57 58 59 60 61 62 63 64 65 66 67 68 69 70 71 72 73 74 75 76 77 78 79 80 81 82 83 84 85 86 87 88 89 90

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 9 of 15

</div>
</div>
</div>
<div class="page" title="Page 10">
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>m2 = 1 + h;                            // Mat2x2  = double + Mat2x2;
assert(m2 == Mat2x2(3, 4, 9, 6));
</pre>
<pre>Mat2x2  m3 = m2 - 1.0;                 // Mat2x2  = Mat2x2 - double
assert(m3 == h);
cout &lt;&lt; "m3 = " &lt;&lt; m3 &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2  m4 = 1.0 - m3;                 // Mat2x2  = double - Mat2x2
cout &lt;&lt; "m4 = " &lt;&lt; m4 &lt;&lt; endl;
assert(m4 == Mat2x2(-1, -2, -7, -4));
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2  m5 = m4 * 2.0;                 // Mat2x2  = Mat2x2 * double
cout &lt;&lt; "m5 = " &lt;&lt; m5 &lt;&lt; endl;
assert(m5 == Mat2x2(-2, -4, -14, -8));
</pre>
<pre>Mat2x2  m6 = -1 * m5;                  // Mat2x2  = double * Mat2x2
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>cout &lt;&lt; "m6 = " &lt;&lt; m6 &lt;&lt; endl;
assert(m6 == Mat2x2(2, 4, 14, 8));
assert(m6 / -1.0 == m5);
assert(1 / m6 == 1 * m6.inverse());
assert(-1.0 * m4 * 2.0 == m6);
</pre>
</div>
<div class="column">
<pre>// Mat2x2  = Mat2x2 / double
// double / Mat2x2, inverse
// double * Mat2x2 * double
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2  m7 = m1++;                     //Mat2x2 ++
cout &lt;&lt; "m1 = " &lt;&lt; m1 &lt;&lt; endl;
cout &lt;&lt; "m7 = " &lt;&lt; m7 &lt;&lt; endl;
assert(m7 == m1 - Mat2x2(1, 1, 1, 1)); // Mat2x2  - Mat2x2
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2  m8 = --m1;                     // --Mat2x2
cout &lt;&lt; "m1 = " &lt;&lt; m1 &lt;&lt; endl;
cout &lt;&lt; "m8 = " &lt;&lt; m8 &lt;&lt; endl;
assert(m8 == m1);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>m8--;
cout &lt;&lt; "m8 = " &lt;&lt; m8 &lt;&lt; endl;
assert(m1 == 1 + m8);
assert(m1 - 1 == m8);
assert(-m1 + 1 == -m8);
assert(2 * m1 == m8 + m1 + 1);
</pre>
</div>
<div class="column">
<pre>// Mat2x2--
// double + Mat2x2
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(m1 * m1 == m1 * (1 + m8));
</pre>
<pre>Mat2x2  m9(123, 6, 6, 4567.89);
cout &lt;&lt; "m9 = " &lt;&lt; m9 &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
91 92 93 94 95 96 97 98 99

100 101 102 103 104 105 106 107 108 109 110 111 112 113 114 115 116 117 118 119 120 121 122 123 124 125 126 127 128 129 130 131 132 133 134

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 10 of 15

</div>
</div>
</div>
<div class="page" title="Page 11">
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// subscripts (non-const)
</pre>
<pre>m9[0] = 3;
m9[1] = 1;
m9[2] = 7;
m9[3] = 4;
cout &lt;&lt; "m9 = " &lt;&lt; m9 &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(m9 == Mat2x2(3, 1, 7, 4));
</pre>
<pre>// relational operators
</pre>
<pre>double smallTol = Mat2x2::getTolerance() / 10.0;
Mat2x2  m9Neighbor(3 - smallTol, 1 + smallTol, 7 - smallTol, 4 + smallTol);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(m9 == m9Neighbor);
</pre>
<pre>double tol = Mat2x2::getTolerance();
assert(m9 == m9);
assert(m9 == (m9 + 0.1 * tol));
assert(m9 == (m9 + 0.2 * tol));
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(m9 == (m9 + 0.3 * tol));
assert(m9 == (m9 + 0.4 * tol));
assert(m9 == (m9 + 0.5 * tol));
assert(m9 != (m9 + 0.6 * tol));
assert(m9 != (m9 + tol));
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(m9 &lt; (m9 + 0.001));
assert(m9 &lt;= (m9 + 0.001));
assert((m9 + 0.001) &lt;= (m9 + 0.001));
</pre>
<pre>assert((m9 + 0.001) &gt; m9);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert((m9 + 0.001) &gt;= m9);
assert((m9 + 0.001) &gt;= (m9 + 0.001));
</pre>
<pre>// compound operators
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>m9 += m9;
cout &lt;&lt; "m9 = " &lt;&lt; m9 &lt;&lt; endl;
assert(m9 == 2 * Mat2x2(3, 1, 7, 4));
</pre>
<pre>Mat2x2  m10;
m10 += (m9 / 2);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>cout &lt;&lt; "m10 = " &lt;&lt; m10 &lt;&lt; endl;
assert(m10 == Mat2x2(3, 1, 7, 4));
</pre>
<pre>m10 *= 2;
cout &lt;&lt; "m10 = " &lt;&lt; m10 &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(m10 == m9);
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
135 136 137 138 139 140 141 142 143 144 145 146 147 148 149 150 151 152 153 154 155 156 157 158 159 160 161 162 163 164 165 166 167 168 169 170 171 172 173 174 175 176 177 178 179 180

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 11 of 15

</div>
</div>
</div>
<div class="page" title="Page 12">
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>m10 /= 2;
cout &lt;&lt; "m10 = " &lt;&lt; m10 &lt;&lt; endl;
assert(m10 == m9 / 2);
</pre>
<pre>m10 += 10;
cout &lt;&lt; "m10 = " &lt;&lt; m10 &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(m10 == (m9 + 20) / 2);
</pre>
<pre>m10 -= 10;
cout &lt;&lt; "m10 = " &lt;&lt; m10 &lt;&lt; endl;
assert(m10 == 0.5 * m9);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// ctor that takes a std::array&lt;double, 4&gt;
</pre>
<pre>std::array&lt;double, 4&gt; arr = { 2, 0, 0, 2 };
Mat2x2 m11{ arr };
cout &lt;&lt; "m11 = " &lt;&lt; m11 &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// ctor that takes a std::array&lt; std::array &lt;double, 2&gt;, 2&gt;
</pre>
<pre>std::array &lt;double, 2&gt; row1{ 2, 0 };
std::array &lt;double, 2&gt; row2{ 0, 2 };
std::array&lt; std::array &lt;double, 2&gt;, 2&gt; mat{ row1, row2 };
Mat2x2 m12{ mat };
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>cout &lt;&lt; "m12 = " &lt;&lt; m12 &lt;&lt; endl;
assert(m12 == arr);
</pre>
<pre>// multiplications
</pre>
<pre>Mat2x2 i{ 1,2,3,4 };
Mat2x2 j{ 2,0,1,2 };
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert((i * j) == Mat2x2(4, 4, 10, 8));
assert((j * i) == Mat2x2(2, 4, 7, 10));
</pre>
<pre>// inverse operation
</pre>
<pre>Mat2x2 k{ 4,7,2,6 };
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>if (k) // this is how if(cin) works!
{
</pre>
<pre>   cout &lt;&lt; "k is invertible\n";
   Mat2x2 m4aInv1 = k.inverse();
   Mat2x2 m4aInv2 = k ^ (-1); // operator ^ overload
   assert(m4aInv1 == m4aInv2);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
}

else

<pre>{
   cout &lt;&lt; "k is NOT invertible\n";
</pre>
}

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
181 182 183 184 185 186 187 188 189 190 191 192 193 194 195 196 197 198 199 200 201 202 203 204 205 206 207 208 209 210 211 212 213 214 215 216 217 218 219 220 221 222 223 224 225

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 12 of 15

</div>
</div>
</div>
<div class="page" title="Page 13">
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2 p{ k * k * k * k * k };
Mat2x2 q{ k ^ (5) };
assert(p == q);
</pre>
<pre>Mat2x2 x = Mat2x2{ 4,7,2,6 }.inverse();
Mat2x2 y{ x * x * x * x * x };
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2 z{ q ^ (-1) };
assert(y == z);
</pre>
<pre>// test function objects (that is, function call operators)
</pre>
<pre>assert(k() == k.norm());
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>cout &lt;&lt; "k = " &lt;&lt; k &lt;&lt; endl;
k(1, 1) = 10;
k(1, 2) = 20;
k(2, 1) = 30;
</pre>
k(2, 2) = 40;

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>cout &lt;&lt; "k = " &lt;&lt; k &lt;&lt; endl;
</pre>
try

{

k(3, 1) = 40;

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>}
catch (std::invalid_argument&amp; ia)
{
</pre>
<pre>   cout &lt;&lt; "Problem:\n" &lt;&lt; ia.what() &lt;&lt; endl;
}
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
try

{

k(1, 3) = 40;

<pre>}
catch (std::invalid_argument&amp; ia)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>{
   cout &lt;&lt; "Problem: " &lt;&lt; ia.what() &lt;&lt; endl;
</pre>
}

<pre>//testing operator&gt;&gt;
</pre>
<pre>cout &lt;&lt; "Please enter the numbers 1, 2, 3, 4.5, in that order\n\n";
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2  input;
cin &gt;&gt; input;
cout &lt;&lt; "input = " &lt;&lt; input &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
226 227 228 229 230 231 232 233 234 235 236 237 238 239 240 241 242 243 244 245 246 247 248 249 250 251 252 253 254 255 256 257 258 259 260 261 262 263 264 265 266 267 268

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 13 of 15

</div>
</div>
</div>
<div class="page" title="Page 14">
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Mat2x2  diff = input - Mat2x2(1, 2, 3, 4.5);
assert(diff.norm() &lt;= tol);    // absolute value
assert(diff() &lt;= tol);             // function object
</pre>
<pre>cout &lt;&lt; "Test completed successfully!" &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return 0; }

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
269 270 271 272 273 274 275 276 277

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33

</div>
<div class="column">
8.1 Output

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>a = [11.00, 22.00, 33.00, 44.00]
b = [111.00, 222.70, 333.00, 0.00]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>c = [1234.00, 0.00, 0.00, 0.00]
d = [1234.00, 0.00, 0.00, 0.00]
e = [0.00, 0.00, 0.00, 0.00]
f = [2.00, 0.00, 0.00, 0.00]
</pre>
<pre>g = [2.00, 3.00, 0.00, 0.00]
h = [2.00, 3.00, 8.00, 0.00]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>m2 = [3.00, 4.00, 9.00, 6.00]
m3 = [2.00, 3.00, 8.00, 5.00]
m4 = [-1.00, -2.00, -7.00, -4.00]
m5 = [-2.00, -4.00, -14.00, -8.00]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>m6 = [2.00, 4.00, 14.00, 8.00]
m1 = [3.50, 4.60, 9.70, 6.80]
m7 = [2.50, 3.60, 8.70, 5.80]
m1 = [2.50, 3.60, 8.70, 5.80]
m8 = [2.50, 3.60, 8.70, 5.80]
m8 = [1.50, 2.60, 7.70, 4.80]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>m9 = [123.00, 6.00, 6.00, 4567.89]
m9 = [3.00, 1.00, 7.00, 4.00]
m9 = [6.00, 2.00, 14.00, 8.00]
m10 = [3.00, 1.00, 7.00, 4.00]
</pre>
<pre>m10 = [6.00, 2.00, 14.00, 8.00]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>m10 = [3.00, 1.00, 7.00, 4.00]
m10 = [13.00, 11.00, 17.00, 14.00]
m10 = [3.00, 1.00, 7.00, 4.00]
m11 = [2.00, 0.00, 0.00, 2.00]
</pre>
<pre>m12 = [2.00, 0.00, 0.00, 2.00]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>k is NOT invertible
k = [4.00, 7.00, 2.00, 6.00]
k = [10.00, 20.00, 30.00, 40.00]
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 14 of 15

</div>
</div>
</div>
<div class="page" title="Page 15">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Problem: row index out of bounds
Problem: column index out of bounds
Please enter the numbers 1, 2, 3, 4.5, in that order
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>1 2 3 4.5
input = [1.00, 2.00, 3.00, 4.50]
Test completed successfully!
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
34 35 36 37 38 39 40

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 3, Summer 2021, page 15 of 15

</div>
</div>
</div>
