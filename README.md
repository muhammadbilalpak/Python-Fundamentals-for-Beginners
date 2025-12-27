<h1> What is Progarming Language </h1>
<p> A Programming Language is a Special Language that we Use to tell the Computer What to do. </p>

<h1>What is Python </h1>
<p>Python is a popular and easy programming language. It was created by Guido van Rossum, and released in 1991. Python is case sensitive Programming language. In Python, indentation is very important</p>
<pre>
It is used for:
  1. web development (server-side),
  2. software development,
  3. mathematics,
  4. system scripting,
  5. AI/ML,
  6. Data science,
  7. automation,
  9. data analysis,
  10. game development,
  11. desktop applications,
  12. cyber security,
  13. network programming,
  14. IoT (Internet of Things),
  15. scientific computing,
  16  machine learning,
  17. deep learning,
</pre>
<h1>Escape Sequence Character in python</h1>
<p>Escape Characters are special characters in Python <a href="http://github.com/ceobilal/Basic-python-/blob/main/00_Escape%20Character%20in%20python.py"> &nbsp; &nbsp; Escape Sequence Character Example</a></p>
<pre>| Escape Character | Meaning          |
| ---------------- | ---------------- |
| \n             | New line         |
| \t             | Tab (space)      |
| \\             | Backslash itself |
| \'             | Single quote     |
| \"             | Double quote     |
</pre>
<h1>Python Comments</h1>
<p> They are used only to explain the code or leave notes for humans. Comments are not interpreted by Python. Meaining, Comments will not be executed.<br/>
There are Two Types Comments <br/> (1) single line Comments <br/> (2) Multiple line Comments <br/>
  Example in this link <a href="https://github.com/ceobilal/Basic-python-/blob/main/01%20Python%20Comments.py">Comments Example.</a>
</p>
<h1>What is Variables in Python</h1>
<p> Variables are containers for storing data values.<br/>
<h2>Rules for naming variables:</h2>
  1: A Variable name should start with a latter or undrscoure ( _ ). <br/>
  2: A Variable name Cannot Start With a number. <br/>
  3: A Variable name is Case sensitive. <br/>
  4: A variable name should only Contain Underscores ( _ ) and alpha-numeric Character. <br/>
  Variables Writing Methods <a href="https://github.com/ceobilal/Basic-python-/blob/main/02%20Python%20Variable.py"> Examples </a>
</p>
<h1>Python Data Types</h1>
<p> Variables can store data of different types. Python has some built-in data types, and they come in different categories<br/> In This is Example Check the data type <a href="https://github.com/ceobilal/Basic-python-/blob/main/03%20Python%20Check%20data%20Type.py">Example No 1</a> <br/> In This Example (str,int,float,complex) <a href="https://github.com/ceobilal/Basic-python-/blob/main/04%20Python%20Data%20Types.py">Example No 2</a> .</p>
<pre>
<h2>Python Built-in Data Types</h2>
Category           Data Types
-----------------  ----------------------------
Text Type          str ✅
Numeric Types      int ✅, float ✅, complex
Sequence Types     list ✅, tuple ✅, range
Mapping Type       dict✅
Set Types          set✅, frozenset
Boolean Type       bool✅
Binary Types       bytes, bytearray, memoryview
None Type          NoneType✅  
</pre>
<h1>Type Casting in Python</h1>
<pre>Type Casting is the process of converting one data type into another in Python.
integer to float 
flot to integer
string to integer
integer to float
etc.   <a href="https://github.com/ceobilal/Basic-python-/blob/main/05%20Python%20Type%20Casting.py">Example </a></pre>
<h1>Python Strings / Strings Methods</h1>
<p>
A String in Python is a sequence of characters, used to represent text data.<br/>
&nbsp; &nbsp;1: Strings can contain letters, numbers, symbols, and spaces.<br/>
&nbsp; &nbsp;2: In Python, strings are written inside single ' ' or double " " quotes.<br/>
&nbsp; &nbsp;3: Strings are immutable, which means once created, you cannot change them directly.<br/>
&nbsp; &nbsp;4: String Writing methods <a href="https://github.com/ceobilal/Basic-python-/blob/main/06%20Python%20Strings%20and%20Strings%20Methods.py">Example</a>
</p>

<h1>String Array in Python ?</h1>
<p>Each character can be accessed by its index <a href="https://github.com/ceobilal/Basic-python-/blob/main/07%20Python%20Strings%20are%20Arrays.py"> Example </a></p>
<h1>Input our Output in Python </h1>
<P>Input = User gives something <br/>
Output = Program shows something &nbsp; &nbsp;  <a href="https://github.com/ceobilal/Basic-python-/blob/main/08%20Python%20input%20and%20output.py"> Example </a></P>
<h1>Python List </h1>
<p>
<h2>What is a Python List? </h2> 
In Python, a list is an ordered container — meaning the items inside it are stored in a specific sequence.<br/>
In Python, lists allow us to store multiple items in a single variable.<br/>
For example, if you need to store the ages of all the students in a class, you can easily do this using a list.<br/>
<h2>How to Create List</h2>
To create a list, we use square brackets [ ].<br/>
All the items you want to store are written inside these brackets,<br/>
and each item is separated by a comma ( , ).<br/>
<pre>fruits = ["apple", "banana", "mango"]</pre>
<h2>List Items of Different Types</h2>
Python lists are very flexible.<br/>
We can store items of different data types in a single list.<br/>
For example:
You can keep numbers, words (strings), and True or False (boolean values) all together in one list.<br/> <br/>
Lists are somewhat similar to arrays in other programming languages,
but the difference is that Python lists are dynamic arrays — meaning they can hold items of different data types (such as numbers, strings, or booleans) together.
<h2>Access List Elements</h2>
When we create a list, each item inside it is automatically given a number,<br/>
called an index.
<h2>What is an Index?</h2>
An index is a number that tells us the position of an item in the list.<br/><br/>

1. The first item in a list is always at index 0.<br/>
2. The second item is at index 1.<br/>
3. The third item is at index 2, and so on.<br/>Example.
<pre>fruits = ["apple", "banana", "mango", "grapes"]</pre>
<pre>| Item     | Index |
| -------- | ----- |
| "apple"  | 0     |
| "banana" | 1     |
| "mango"  | 2     |
| "grapes" | 3     |
</pre>
<h2>Negative Indexing (Accessing items from the end of a list)</h2>

In Python, you can access items from the end of a list using negative numbers.
•	The last item has index -1
•	The second last item has index -2
•	The third last item has index -3,
and so on.
  <pre>fruits = ["apple", "banana", "mango", "grapes"]</pre>
  <pre>
    | Item   | Positive Index | Negative Index |
| ------ | -------------- | -------------- |
| apple  | 0              | -4             |
| banana | 1              | -3             |
| mango  | 2              | -2             |
| grapes | 3              | -1             |
  </pre>
<h2>What is a Nested List?</h2>
A Nested List is a list that contains other lists inside it.<br/>
The outer list is called the parent list, and the inner lists are called child lists.
<pre>
  Example:
         matrix = [
                     [1, 2, 3],
                     [4, 5, 6],
                     [7, 8, 9]
                                ]
</pre>
<h2>🔹 What is List Slicing? \ Range of Indexes?</h2>
If we want to get a portion of a list, instead of the whole list,<br/>
we can use the slicing operator : in Python.<br/><br/> 
Using slicing, we can specify the start and end indexes of the list to get only that part.
<h3> Range of Index</h3> By using a colon (:) we can access a range of items at once.<br/> Simply separate two indexes useing the colon.<br/> The first index is the start of the range while the second index is the end of the range  <br/>

<pre>         
     Example:
               numbers = [10, 20, 30, 40, 50]
                     print(numbers[1:4]) Output: [20, 30, 40]
                     numbers[:3]  # 0 سے 2 index تک  Output: [10, 20, 30]
</pre>
<h2>Negative slicing</h2> 
<pre>                     
        Example:
                        numbers = [10, 20, 30, 40, 50]
                            print(numbers[-4:-1])   Output:  [20, 30, 40]
                            print (number[:-4]) Output: [10] 
</pre>

<pre>
|    Method Name                      | What it Does / Working                                                       
| ----------------------------------- | ---------------------------------------------------------------------------- 
| append(item)✅                      Adds a single item at the end of the list                                    
| insert(index, item)✅               Adds a single item at a specific position                                  
| extend(iterable)✅                  Adds all items from another list or iterable                                 
| remove(item)✅                      Removes the first occurrence of a specified item                           
| pop(index=-1)✅                     Removes and returns item at the given index (default last item)            
| clear() ✅                          Removes all items from the list                                            
| len(list))                           Returns the number of items in the list                                     
| count(item)✅                       Returns the number of times a specified item appears in the list          
| sort()✅                            Sorts the list (ascending by default, descending if `reverse=True`)         
| reverse()✅                         Reverses the order of items in the list                                    
| copy()✅                            Returns a shallow copy of the list                                        
| len(list)                           Returns the number of items in the list *(function, not method)*           
| del list[index]                     Deletes item at a specific index *(statement, not method)*                   
| *list comprehension*                Creates a new list based on existing lists *(not a method, but widely used)* 
|index()                              Returns the index of the first mathched item   

</pre>
</p>







