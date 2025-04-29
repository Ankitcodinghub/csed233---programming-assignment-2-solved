# csed233---programming-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CSED233 – Programming Assignment #2 Solved](https://www.ankitcodinghub.com/product/csed233-programming-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115678&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSED233 - Programming Assignment #2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Lecturer: Prof. Jaesik Park

Teaching Assistants: Hyeonjun Lee, Hyunsoo Ahn, Sangwoo Ryu

**** PLEASE READ THIS GRAY BOX CAREFULLY BEFORE STARTING THE ASSIGNMENT ****

Evaluation policy:

■ 100% penalty is applied for that submission

● Your code will be automatically tested using an evaluation program

○ Each problem has the maximum score

● We won’t accept any submission via email – it will be ignored

● Please do not use the containers in C++ standard template library (STL) ○ Such as:

■ #include &lt;queue&gt; ■ #include &lt;vector&gt;

■ #include &lt;stack&gt;

○ Any submission using the containers in STL will be disregarded

Any questions?

● Please use LMS – Q&amp;A board

0. Basic instruction

a. Please refer to the attached file named PA_instructions_updated.pdf

1. Quiz (2 pts)

1.1 Let T is a general tree, and T’ is a binary tree converted from T. Which of the following traversal visits the nodes in the same order as the inorder traversal of T’?

(1) Preorder traversal of T

(2) Inorder traversal of T

(3) Postorder traversal of T

(4) None of the aboves

1.2 What is the time complexity of rearranging min-heap into a max-heap?

(1) O(1)

(2) O(log n)

(3) O(n)

(4) O(2^n)

– Example execution

– If you choose “(1) Preorder traversal of T” for 1-1., print your answer as shown below

&gt;&gt; ./pa2.exe 1 1

[Task 1]

1

– If you choose “(1) O(1)” for 1-2., print your answer as shown below

&gt;&gt; ./pa2.exe 1 2

[Task 1]

1

pre-2. Construct Binary Tree

Note: pre-2 is not a problem that will be evaluated, but this is a short prerequisite to solve problems 2,3, and 4.

Don’t worry. We are providing utility functions to help you.

a. For problems 2, 3, and 4, you would need to implement member functions of BinaryTree class. To construct a BinaryTree class instance from an input, we use the string with bracket representation as input. The recursive definition of the bracket representation is as follows.

Tree = Root(LeftChild)(RightChild).

Below are some examples.

The left tree is represented as 1(2)(3), and the right tree is

1(2()(4))(3()(5))

b. To implement “a”, we provide a function to construct BinaryTree class from the bracket representation, which is BinaryTree::buildFromString function. It creates a pointer-based BinaryTree class instance from the given string. It would be helpful to read the implementation details of

BinaryTree::buildFromString

c. To sum up, you will need to use BinaryTree class for problems 2, 3 and 4. Please try to understand the code for BinaryTree class.

2. Traverse Binary Tree (2 pts)

a. Implement BinaryTree::preOrder, BinaryTree::postOrder and BinaryTree:inOrder function that can traverse a binary tree with given traverse mode

b. Input &amp; Output Input:

– String with bracket representation.

– String representing traverse mode. Either “preorder”, “postorder” or “inorder” Output:

– A sequence of node values acquired from the tree traversal. The value is separated with a white space

c. Example input &amp; output

Input Output

“1(2)(3)” “preorder” 1 2 3

“1(2()(4))(3()(5))” “postorder” 4 2 5 3 1

“4(2(3)(1))(6(5))” “preorder” 4 2 3 1 6 5

“4(2(3)(1))(6(5))” “inorder” 3 2 1 4 5 6

“4(2(3)(1))(6(5))” “postorder” 3 1 2 5 6 4

d. Example execution

&gt;&gt; ./pa2.exe 2 “4(2(3)(1))(6(5))” “inorder”

[Task 2] 3 2 1 4 5 6

3. Depth of Binary Tree (3 pts)

a. Implement BinaryTree::getDepth function that can calculate the depth of a specific node in a given binary tree.

b. Input &amp; Output

Input:

– A given binary tree represented by string with bracket representation – All node values in the tree are unique.

– A specific node represented by integer value.

Output:

– height of the specific node in a given binary tree

– if the specific node doesn’t exist in the binary tree, return -1

c. Example input &amp; output

Input Output

“1(2)(3)” 2 1

“1(2(3(4)))(5)” 4 3

“1(2(3(4)))(5)” 6 -1

d. Example execution

&gt;&gt; ./pa2.exe 3 “1(2(3(4)))(5)” 4

[Task 3]

3

4. Properness of Binary Tree (3 pts)

a. Implement BinaryTree::isProper function that can check whether if the given binary tree is a proper binary tree or not

b. Input &amp; Output

Input: string with bracket representation

Output: string “True” if the given binary tree is proper binary tree, “False” otherwise

c. Example input &amp; output

Input Output

1(2)(3) True

1(2(4)(5))(3) True

1(2(4)(5(6)(7))(3) True

1(2(4)(5))(3(6)) False

d. Example execution

&gt;&gt; ./pa2.exe 4 “1(2(4)(5(6)(7))(3)”

[Task 4] True

5. Max-heap Insertion (2 pts)

Note: For solving problems 5 and 6, the similar utility functions provided in0 PA1 will be used to parse an input string. Therefore, you won’t need to try implementing a string parser. Please read pa2.cpp, and find the lines where your code would be located.

a. Implement a function that inserts a new element to a binary max-heap. Your heap should maintain the max-heap property even after the insertion. Each test case will insert less than 100 values

b. Input &amp; Output

Input: A sequence of commands

– (‘insert’,integer): insert integer into the current max heap Output:

– Values in a heap in a node number order, in a string separated with the white space (automatically printed with built-in function)

– Do not consider the exceptional cases such as overflow, underflow or empty heap. We will not use the test cases for those scenarios.

c. Example Input &amp; Output

Input Output

[(‘insert’,5),(‘insert’,-3),(‘insert’,2)] 5 -3 2

[(‘insert’,4),(‘insert’,-2),(‘insert’,9),

(‘insert’,10),(‘insert’,15),(‘insert’,-25)] 15 10 4 -2 9

-25

[(‘insert’,28),(‘insert’,9),(‘insert’,27),

(‘insert’,10),(‘insert’,3),(‘insert’,45)] 45 10 28 9 3

27

d. Example execution

&gt;&gt; ./pa2.exe 5 “[(‘insert’,2),(‘insert’,3),(‘insert’,5)]”

[Task 5]

5 2 3

6. Max-heap Deletion (3 pts)

a. Implement a function that deletes the maximum value from the binary maxheap. Your heap should maintain the max heap property even after the deletion.

b. Input &amp; Output

Input: A sequence of commands, which is one of the following

– (‘insert’,integer): insert integer into the current max heap

– (‘delMax’,NULL): delete maximum value from current binary max heap and rearrange heap to maintain the max heap property.

Output:

– Values in a heap in a node number order, in a string separated with the white space (automatically printed with built-in function)

– Do not consider the exceptional cases such as overflow, underflow or empty heap. We will not use the test cases for those scenarios.

c. Example Input &amp; Output

Input Output

[(‘insert’,5),(‘insert’,-3),(‘insert’,22),

(‘delMax’,NULL)] 5 -3

[(‘insert’,28),(‘insert’,9),(‘insert’,27),

(‘insert’,10),(‘insert’,3),(‘insert’,45), (‘delMax’,NULL)] 28 10 27 9 3

[(‘insert’,28),(‘insert’,9),(‘insert’,27),

(‘insert’,10),(‘insert’,3),(‘insert’,45),

(‘delMax’,NULL),(‘insert’,22)] 28 10 27 9 3

22

d. Example execution

&gt;&gt; ./pa2.exe 6 “[(‘insert’,4),(‘insert’,-2),(‘insert’,9),

(‘insert’,10),(‘insert’,15),(‘insert’,-25),(‘delMax’,NULL)]”

[Task 6]

10 -2 4 -25 9
