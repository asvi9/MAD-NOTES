


## Javascript

 JavaScript is a lightweight, interpreted programming language.
 It is designed for creating network-centric applications.
 It is complimentary to and integrated with Java.
 JavaScript is very easy to implement because it is integrated with HTML.
 It is open and cross-platform.
Why to Learn Javascript
 Javascript  is  the  most  popular programming  language in  the  world
and that makes it a programmer’s great choice.
 Once  you  learnt Javascript,  it  helps  you  developing  great  front-end
as  well  as  back-end  softwares  using  different  Javascript  based
frameworks like jQuery, Node.JS etc.
 Javascript  is  everywhere,  it  comes  installed  on  every  modern  web
browser  and  so  to  learn  Javascript  you really  do  not  need  any
special environment setup.
 For example Chrome, Mozilla Firefox , Safari and every browser you
know as of today, supports Javascript.
 Javascript helps you create really beautiful and crazy fast websites.
 You  can  develop  your  website with  a console  like  look  and  feel  and
give your users the best Graphical User Experience.
 JavaScript  usage  has  now  extended  to  mobile  app  development,
desktop  app  development,  and  game  development.  This  opens
many opportunities for you as Javascript Programmer.
 Due  to  high  demand,  there  is  tons  of  job  growth  and  high  pay  for
those who know JavaScript.
 You  can  navigate  over  to  different  job  sites  to  see  what  having
JavaScript skills looks like in the job market.

 Great  thing  about  Javascript  is  that  you  will  find  tons  of  frameworks
and  Libraries  already  developed  which  can  be  used  directly  in  your
software development to reduce your time to market.
There could be 1000s of good reasons to learn Javascript Programming. But one thing
for  sure,  to  learn  any programming  language,  not  only  Javascript,  you  just  need  to
code, and code and finally code until you become expert.
Hello World using Javascript
Just  to  give  you  a  little  excitement  about Javascript  programming,  I'm
going  to  give  you  a  small  conventional  Javascript  Hello  World  program,
You can try it using Demo link
## Live Demo
## <html>
## <body>
<script language = "javascript" type =
## "text/javascript">
## <!--
document.write("Hello World!")
## //-->
## </script>
## </body>
## </html>
There are many useful Javascript frameworks and libraries available:
##  Angular
##  React
 jQuery
##  Vue.js
##  Ext.js
##  Ember.js
##  Meteor
##  Mithril
##  Node.js
##  Polymer

##  Aurelia
##  Backbone.js
Advantages of JavaScript
The merits of using JavaScript are −
 Less   server   interaction −  You  can  validate  user  input  before
sending  the  page  off  to  the  server.  This  saves  server  traffic,  which
means less load on your server.
 Immediate feedback to the visitors − They don't have to wait for a
page reload to see if they have forgotten to enter something.
 Increased interactivity − You can create interfaces that react when
the  user  hovers  over  them  with  a  mouse  or  activates  them  via  the
keyboard.
 Richer  interfaces − You can use JavaScript  to  include  such  items
as drag-and-drop components and sliders to give a Rich Interface to
your site visitors.
Limitations of JavaScript
We  cannot  treat  JavaScript  as  a  full-fledged  programming  language.  It
lacks the following important features −
 Client-side  JavaScript  does  not  allow  the  reading  or  writing  of  files.
This has been kept for security reason.
 JavaScript cannot be used for networking applications because there
is no such support available.
 JavaScript   doesn't   have   any   multi-threading   or   multiprocessor
capabilities.
Once again, JavaScript is a lightweight, interpreted programming language
that allows you to build interactivity into otherwise static HTML pages.
JavaScript Variables
Like   many   other   programming   languages,   JavaScript   has   variables.
Variables can be thought of as named containers. You can place data into

these  containers  and  then  refer  to  the  data  simply  by  naming  the
container.
Before  you  use  a  variable  in  a  JavaScript program,  you  must  declare  it.
Variables are declared with the var keyword as follows.
<script type = "text/javascript">
## <!--
var money;
var name;
## //-->
## </script>
You  can  also  declare  multiple  variables  with  the  same var keyword  as
follows −
<script type = "text/javascript">
## <!--
var money, name;
## //-->
## </script>
Storing  a  value  in  a  variable  is  called variable  initialization.  You  can  do
variable  initialization  at  the  time  of  variable  creation  or  at  a  later  point  in
time when you need that variable.
For  instance,  you  might  create  a  variable  named money and  assign  the
value  2000.50  to  it  later.  For  another  variable,  you  can  assign  a  value  at
the time of initialization as follows.
<script type = "text/javascript">
## <!--
var name = "Ali";
var money;
money = 2000.50;
## //-->
## </script>
JavaScript Variable Scope
The scope of a variable is the region of your program in which it is defined.
JavaScript variables have only two scopes.

 Global Variables − A global variable has global scope which means
it can be defined anywhere in your JavaScript code.
 Local  Variables −  A  local  variable  will  be  visible  only  within  a
function where it is defined. Function parameters are always local to
that function.
Within  the  body of  a  function,  a  local  variable  takes  precedence  over  a
global  variable  with  the  same  name.  If  you  declare  a  local  variable  or
function   parameter   with   the   same   name   as   a   global   variable,   you
effectively hide the global variable. Take a look into the following example.
## Live Demo
## <html>
<body onload = checkscope();>
<script type = "text/javascript">
## <!--
var myVar = "global";      // Declare a
global variable
function checkscope( ) {
var myVar = "local";    // Declare a
local variable
document.write(myVar);
## }
## //-->
## </script>
## </body>
## </html>
This produces the following result −
local

What is an Operator?
Let  us  take  a  simple  expression 4  +  5  is  equal  to  9.  Here  4  and  5  are
called operands and  ‘+’  is  called  the operator.  JavaScript  supports  the
following types of operators.
##  Arithmetic Operators
##  Comparison Operators

##  Logical (or Relational) Operators
##  Assignment Operators
 Conditional (or ternary) Operators
Lets have a look on all operators one by one.
## Arithmetic Operators
JavaScript supports the following arithmetic operators −
Assume variable A holds 10 and variable B holds 20, then −
Sr.No. Operator & Description
## 1
+ (Addition)
Adds two operands
Ex: A + B will give 30
## 2
- (Subtraction)
Subtracts the second operand from the first
Ex: A - B will give -10
## 3
- (Multiplication)
Multiply both operands
Ex: A * B will give 200
## 4
/ (Division)
Divide the numerator by the denominator
Ex: B / A will give 2
## 5
% (Modulus)
Outputs the remainder of an integer division
Ex: B % A will give 0

## 6
++ (Increment)
Increases an integer value by one
Ex: A++ will give 11
## 7
-- (Decrement)
Decreases an integer value by one
Ex: A-- will give 9
Note − Addition operator (+) works for Numeric as well as Strings. e.g. "a"
+ 10 will give "a10".
## Comparison Operators
JavaScript supports the following comparison operators −
Assume variable A holds 10 and variable B holds 20, then −
Sr.No. Operator & Description
## 1
= = (Equal)
Checks if the value of two operands are equal or not, if yes, then the
condition becomes true.
Ex: (A == B) is not true.
## 2
!= (Not Equal)
Checks  if  the  value  of  two  operands  are equal  or  not,  if  the  values
are not equal, then the condition becomes true.
Ex: (A != B) is true.
## 3
> (Greater than)
Checks  if  the  value  of  the  left  operand  is  greater  than  the  value  of
the right operand, if yes, then the condition becomes true.
Ex: (A > B) is not true.

## 4
< (Less than)
Checks  if  the  value  of  the  left  operand  is  less  than  the  value  of  the
right operand, if yes, then the condition becomes true.
Ex: (A < B) is true.
## 5
>= (Greater than or Equal to)
Checks if the value of the left operand is greater than or equal to the
value of the right operand, if yes, then the condition becomes true.
Ex: (A >= B) is not true.
## 6
<= (Less than or Equal to)
Checks  if  the  value  of  the  left  operand  is  less  than  or  equal  to  the
value of the right operand, if yes, then the condition becomes true.
Ex: (A <= B) is true.
## Logical Operators
JavaScript supports the following logical operators −
Assume variable A holds 10 and variable B holds 20, then −
Sr.No. Operator & Description
## 1
&& (Logical AND)
If both the operands are non-zero, then the condition becomes true.
Ex: (A && B) is true.
## 2
|| (Logical OR)
If any of the two operands are non-zero, then the condition becomes
true.
Ex: (A || B) is true.

## 3
! (Logical NOT)
Reverses the  logical state  of  its  operand. If  a condition  is  true, then
the Logical NOT operator will make it false.
Ex: ! (A && B) is false.
## Bitwise Operators
JavaScript supports the following bitwise operators −
Assume variable A holds 2 and variable B holds 3, then −
Sr.No. Operator & Description
## 1
& (Bitwise AND)
It  performs  a  Boolean  AND  operation  on  each  bit  of  its  integer
arguments.
Ex: (A & B) is 2.
## 2
| (BitWise OR)
It  performs  a  Boolean  OR  operation  on  each  bit  of  its  integer
arguments.
Ex: (A | B) is 3.
## 3
^ (Bitwise XOR)
It performs  a  Boolean  exclusive  OR  operation  on  each  bit  of  its
integer  arguments.  Exclusive  OR  means  that  either  operand  one  is
true or operand two is true, but not both.
Ex: (A ^ B) is 1.
## 4
~ (Bitwise Not)
It  is  a  unary  operator  and  operates  by  reversing all  the  bits  in  the
operand.

Ex: (~B) is -4.
## 5
<< (Left Shift)
It  moves  all  the  bits  in  its  first  operand  to  the  left  by  the  number  of
places  specified  in  the  second  operand.  New  bits  are  filled  with
zeros. Shifting a value left by one position is equivalent to multiplying
it by 2, shifting two positions is equivalent to multiplying by 4, and so
on.
Ex: (A << 1) is 4.
## 6
>> (Right Shift)
Binary Right Shift Operator. The left operand’s value is moved right
by the number of bits specified by the right operand.
Ex: (A >> 1) is 1.
## 7
>>> (Right shift with Zero)
This operator is just like the >> operator, except that the bits shifted
in on the left are always zero.
Ex: (A >>> 1) is 1.
## Assignment Operators
JavaScript supports the following assignment operators −
Sr.No. Operator & Description
## 1
= (Simple Assignment )
Assigns values from the right side operand to the left side operand
Ex: C = A + B will assign the value of A + B into C
## 2
+= (Add and Assignment)
It adds the right operand to the left operand and assigns the result to

the left operand.
Ex: C += A is equivalent to C = C + A
## 3
−= (Subtract and Assignment)
It subtracts the  right  operand  from  the  left  operand  and assigns  the
result to the left operand.
Ex: C -= A is equivalent to C = C - A
## 4
*= (Multiply and Assignment)
It  multiplies  the  right  operand  with  the  left  operand  and  assigns  the
result to the left operand.
Ex: C *= A is equivalent to C = C * A
## 5
/= (Divide and Assignment)
It  divides  the  left operand  with  the  right  operand  and  assigns  the
result to the left operand.
Ex: C /= A is equivalent to C = C / A
## 6
%= (Modules and Assignment)
It  takes  modulus  using  two  operands  and  assigns  the  result  to  the
left operand.
Ex: C %= A is equivalent to C = C % A
## Conditional Operator (? :)
The  conditional  operator  first  evaluates  an  expression  for  a  true  or  false
value and then executes one of the two given statements depending upon
the result of the evaluation.
Sr.No. Operator and Description
## 1
? : (Conditional )
If   Condition   is   true?   Then   value   X   :

Otherwise value Y

JavaScript - if...else Statement
While writing a program, there may be a situation when you need to adopt
one out of a given set of paths. In such cases, you need to use conditional
statements that allow your program to make correct decisions and perform
right actions.
JavaScript  supports  conditional  statements  which  are  used  to  perform
different  actions  based  on  different  conditions.  Here  we  will  explain
the if..else statement.
Flow Chart of if-else
The following flow chart shows how the if-else statement works.

JavaScript supports the following forms of if..else statement −
 if statement
 if...else statement
 if...else if... statement.
if statement

The if statement   is   the   fundamental control   statement   that   allows
JavaScript to make decisions and execute statements conditionally.
## Syntax
The syntax for a basic if statement is as follows −
if (expression) {
Statement(s) to be executed if expression is true
## }
Here  a  JavaScript  expression  is  evaluated.  If  the  resulting  value  is  true,
the  given  statement(s)  are  executed.  If  the  expression  is  false,  then  no
statement  would  be  not  executed.  Most  of  the  times,  you  will  use
comparison operators while making decisions.
## Example
Try the following example to understand how the if statement works.
## Live Demo
## <html>
## <body>
<script type = "text/javascript">
## <!--
var age = 20;

if( age > 18 ) {
document.write("<b>Qualifies for
driving</b>");
## }
## //-->
## </script>
<p>Set the variable to different value and then
try...</p>
## </body>
## </html>
## Output
Qualifies for driving
Set the variable to different value and then try...
if...else statement

The 'if...else' statement  is  the  next  form  of  control  statement  that  allows
JavaScript to execute statements in a more controlled way.
## Syntax
if (expression) {
Statement(s) to be executed if expression is true
} else {
Statement(s) to be executed if expression is false
## }
Here JavaScript expression is evaluated. If the resulting value is true, the
given statement(s) in the ‘if’ block, are executed. If the expression is false,
then the given statement(s) in the else block are executed.
## Example
Try  the  following  code  to  learn  how  to  implement  an  if-else  statement  in
JavaScript.
## Live Demo
## <html>
## <body>
<script type = "text/javascript">
## <!--
var age = 15;

if( age > 18 ) {
document.write("<b>Qualifies for
driving</b>");
} else {
document.write("<b>Does not qualify for
driving</b>");
## }
## //-->
## </script>
<p>Set the variable to different value and then
try...</p>
## </body>
## </html>

## Output
Does not qualify for driving
Set the variable to different value and then try...
if...else if... statement
The if...else  if... statement  is  an advanced  form  of if...else that  allows
JavaScript to make a correct decision out of several conditions.
## Syntax
The syntax of an if-else-if statement is as follows −
if (expression 1) {
Statement(s) to be executed if expression 1 is true
} else if (expression 2) {
Statement(s) to be executed if expression 2 is true
} else if (expression 3) {
Statement(s) to be executed if expression 3 is true
} else {
Statement(s) to be executed if no expression is true
## }
There is nothing special about this code. It is just a series of if statements,
where  each if is  a  part  of  the else clause  of  the  previous  statement.
Statement(s)  are  executed  based  on  the  true  condition,  if  none  of  the
conditions is true, then the else block is executed.
## Example
Try the following code to learn how to implement an if-else-if statement in
JavaScript.
## <html>
## <body>
<script type = "text/javascript">
## <!--
var book = "maths";
if( book == "history" ) {
document.write("<b>History Book</b>");
} else if( book == "maths" ) {
document.write("<b>Maths Book</b>");
} else if( book == "economics" ) {
document.write("<b>Economics Book</b>");

} else {
document.write("<b>Unknown Book</b>");
## }
## //-->
## </script>
<p>Set the variable to different value and then
try...</p>
## </body>
## <html>
## Output
## Maths Book
Set the variable to different value and then try...

JavaScript - Switch Case
You  can  use  multiple if...else...if statements,  as  in  the  previous  chapter,
to  perform  a  multiway  branch.  However,  this  is  not  always  the  best
solution,  especially  when  all  of  the  branches  depend  on  the  value  of  a
single variable.
Starting  with  JavaScript  1.2,  you  can  use  a switch statement  which
handles   exactly   this   situation,   and   it   does   so   more   efficiently   than
repeated if...else if statements.
## Flow Chart
The following flow chart explains a switch-case statement works.


## Syntax
The  objective  of  a switch statement  is  to  give  an  expression  to  evaluate
and  several  different  statements  to  execute  based  on  the  value  of  the
expression.  The  interpreter  checks  each case against  the  value  of  the
expression  until  a  match  is  found.  If  nothing  matches,  a default condition
will be used.
switch (expression) {
case condition 1: statement(s)
break;

case condition 2: statement(s)
break;
## ...

case condition n: statement(s)
break;

default: statement(s)
## }

The break statements  indicate the  end  of  a  particular  case.  If  they  were
omitted,  the  interpreter  would  continue  executing  each  statement  in  each
of the following cases.
We will explain break statement in Loop Control chapter.
## Example
Try the following example to implement switch-case statement.
## Live Demo
## <html>
## <body>
<script type = "text/javascript">
## <!--
var grade = 'A';
document.write("Entering switch block<br
## />");
switch (grade) {
case 'A': document.write("Good job<br
## />");
break;

case 'B': document.write("Pretty good<br
## />");
break;

case 'C': document.write("Passed<br
## />");
break;

case 'D': document.write("Not so good<br
## />");
break;

case 'F': document.write("Failed<br
## />");
break;

default:  document.write("Unknown
grade<br />")

## }
document.write("Exiting switch block");
## //-->
## </script>
<p>Set the variable to different value and then
try...</p>
## </body>
## </html>
## Output
Entering switch block
Good job
Exiting switch block
Set the variable to different value and then try...
Break  statements  play  a  major  role  in  switch-case  statements.  Try  the
following   code   that   uses   switch-case   statement   without   any   break
statement.
## Live Demo
## <html>
## <body>
<script type = "text/javascript">
## <!--
var grade = 'A';
document.write("Entering switch block<br
## />");
switch (grade) {
case 'A': document.write("Good job<br
## />");
case 'B': document.write("Pretty good<br
## />");
case 'C': document.write("Passed<br
## />");
case 'D': document.write("Not so good<br
## />");
case 'F': document.write("Failed<br
## />");
default: document.write("Unknown
grade<br />")

## }
document.write("Exiting switch block");
## //-->
## </script>
<p>Set the variable to different value and then
try...</p>
## </body>
## </html>

JavaScript - While Loops
 While  writing  a  program,  you  may  encounter  a  situation  where  you
need to perform an action over and over again.
 In  such  situations,  you  would  need  to  write  loop  statements  to
reduce the number of lines.
 JavaScript  supports  all  the  necessary  loops  to  ease  down  the
pressure of programming.
The while Loop
## Flow Chart
The flow chart of while loop looks as follows −


## Syntax
The syntax of while loop in JavaScript is as follows −
while (expression) {
Statement(s) to be executed if expression is
true
## }
## Example
Try the following example to implement while loop.
## Live Demo
## <html>
## <body>

<script type = "text/javascript">
## <!--
var count = 0;
document.write("Starting Loop ");


while (count < 10) {
document.write("Current Count : " +
count + "<br />");
count++;
## }

document.write("Loop stopped!");
## //-->
## </script>

<p>Set the variable to different value and then
try...</p>
## </body>
## </html>
## Output
## Starting Loop
## Current Count : 0
## Current Count : 1
## Current Count : 2
## Current Count : 3
## Current Count : 4
## Current Count : 5
## Current Count : 6
## Current Count : 7
## Current Count : 8
## Current Count : 9
Loop stopped!
Set the variable to different value and then try...
The do...while Loop
The do...while loop  is  similar  to  the while loop  except  that  the  condition
check happens at the end of the loop. This means that the loop will always
be executed at least once, even if the condition is false.
## Flow Chart
The flow chart of a do-while loop would be as follows −


## Syntax
The syntax for do-while loop in JavaScript is as follows −
do {
Statement(s) to be executed;
} while (expression);
Note − Don’t miss the semicolon used at the end of the do...while loop.
## Example
Try  the  following  example  to  learn  how  to  implement  a do-while loop  in
JavaScript.
## <html>
## <body>
<script type = "text/javascript">
## <!--
var count = 0;

document.write("Starting Loop" + "<br />");
do {
document.write("Current Count : " +
count + "<br />");
count++;
## }


while (count < 5);
document.write ("Loop stopped!");
## //-->
## </script>
<p>Set the variable to different value and then
try...</p>
## </body>
## </html>
## Output
## Starting Loop
## Current Count : 0
## Current Count : 1
## Current Count : 2
## Current Count : 3
## Current Count : 4
## Loop Stopped!
Set the variable to different value and then try...

JavaScript - For Loop
The 'for' loop is the most compact form of looping. It includes the following
three important parts −
 The loop  initialization where  we  initialize  our  counter  to  a  starting
value.   The   initialization   statement   is   executed   before   the   loop
begins.
 The test statement which will test if a given condition is true or not. If
the  condition  is  true,  then  the  code  given  inside  the  loop  will  be
executed, otherwise the control will come out of the loop.
 The iteration  statement where  you  can  increase  or  decrease  your
counter.
You can put all the three parts in a single line separated by semicolons.
## Flow Chart
The flow chart of a for loop in JavaScript would be as follows −


## Syntax
The syntax of for loop is JavaScript is as follows −
for (initialization;test condition;iteration statement)
## {
Statement(s) to be executed if test condition is
true
## }
## Example
Try the following example to learn how a for loop works in JavaScript.
## Live Demo
## <html>
## <body>
<script type = "text/javascript">
## <!--
var count;
document.write("Starting Loop" + "<br />");

for(count = 0; count < 10; count++) {
document.write("Current Count : " +
count );
document.write("<br />");
## }

document.write("Loop stopped!");
## //-->
## </script>
<p>Set the variable to different value and then
try...</p>
## </body>
## </html>
## Output
## Starting Loop
## Current Count : 0
## Current Count : 1
## Current Count : 2
## Current Count : 3
## Current Count : 4
## Current Count : 5
## Current Count : 6
## Current Count : 7
## Current Count : 8
## Current Count : 9
Loop stopped!
Set the variable to different value and then try...

JavaScript for...in loop
The for...in loop is used to loop through an object's properties. As we have
not discussed Objects yet, you may not feel comfortable with this loop. But
once  you  understand  how  objects  behave  in  JavaScript,  you  will  find  this
loop very useful.
## Syntax
The syntax of ‘for..in’ loop is −
for (variablename in object) {
statement or block to execute
## }
In each iteration, one property from object is assigned
to variablename and  this  loop continues  till  all the  properties  of  the  object
are exhausted.

## Example
Try  the  following  example  to  implement  ‘for-in’ loop.  It  prints  the  web
browser’s Navigator object.
## Live Demo
## <html>
## <body>
<script type = "text/javascript">
## <!--
var aProperty;
document.write("Navigator Object
## Properties<br /> ");
for (aProperty in navigator) {
document.write(aProperty);
document.write("<br />");
## }
document.write ("Exiting from the loop!");
## //-->
## </script>
<p>Set the variable to different object and then
try...</p>
## </body>
## </html>
## Output
## Navigator Object Properties
serviceWorker
webkitPersistentStorage
webkitTemporaryStorage
geolocation
doNotTrack
Set the variable to different object and then try...

JavaScript - Functions
 A function is a group of reusable code which can be called anywhere
in your program.
 This eliminates the need of writing the same code again and again.

 It helps programmers in writing modular codes.
 Functions allow a programmer to divide a big program into a number
of small and manageable functions.
 Like  any  other  advanced  programming  language,  JavaScript  also
supports  all  the  features  necessary  to  write  modular  code  using
functions.
 We  were  using these functions  again and  again,  but they  had  been
written in core JavaScript only once.
 JavaScript allows us to write our own functions as well. This section
explains how to write your own functions in JavaScript.
## Function Definition
Before we use a function, we need to define it. The most common way to
define a function in JavaScript is by using the function keyword, followed
by a unique function name, a list of parameters (that might be empty), and
a statement block surrounded by curly braces.
## Syntax
The basic syntax is shown here.
<script type = "text/javascript">
## <!--
function functionname(parameter-list) {
statements
## }
## //-->
## </script>
## Example
Try  the following  example.  It  defines a function called  sayHello that takes
no parameters −
<script type = "text/javascript">
## <!--
function sayHello() {
alert("Hello there");
## }
## //-->

## </script>
Calling a Function
To invoke a function somewhere later in the script, you would simply need
to write the name of that function as shown in the following code.
## Live Demo
## <html>
## <head>
<script type = "text/javascript">
function sayHello() {
document.write ("Hello there!");
## }
## </script>

## </head>

## <body>
<p>Click the following button to call the
function</p>
## <form>
<input type = "button" onclick = "sayHello()"
value = "Say Hello">
## </form>
<p>Use different text in write method and then
try...</p>
## </body>
## </html>
## Function Parameters
Till now, we have seen functions without parameters. But there is a facility
to  pass  different  parameters  while  calling  a  function.  These  passed
parameters can be captured inside the function and any manipulation can
be  done  over  those  parameters.  A  function  can  take  multiple  parameters
separated by comma.

## Example
Try  the  following  example.  We  have  modified  our sayHello function  here.
Now it takes two parameters.
## <html>
## <head>
<script type = "text/javascript">
function sayHello(name, age) {
document.write (name + " is " + age + "
years old.");
## }
## </script>
## </head>

## <body>
<p>Click the following button to call the
function</p>
## <form>
<input type = "button" onclick =
"sayHello('Zara', 7)" value = "Say Hello">
## </form>
<p>Use different parameters inside the function
and then try...</p>
## </body>
## </html>
The return Statement
A  JavaScript  function  can  have  an  optional return statement.  This  is
required  if  you  want  to  return  a  value  from  a  function.  This  statement
should be the last statement in a function.
For  example,  you  can  pass  two  numbers  in  a  function  and then  you  can
expect the function to return their multiplication in your calling program.
## Example
Try the following example. It defines a function that takes two parameters
and  concatenates  them  before  returning  the  resultant  in  the  calling
program.
## <html>

## <head>
<script type = "text/javascript">
function concatenate(first, last) {
var full;
full = first + last;
return full;
## }
function secondFunction() {
var result;
result = concatenate('Zara', 'Ali');
document.write (result );
## }
## </script>
## </head>

## <body>
<p>Click the following button to call the
function</p>
## <form>
<input type = "button" onclick =
"secondFunction()" value = "Call Function">
## </form>
<p>Use different parameters inside the function
and then try...</p>
## </body>
## </html>

JavaScript - Events
What is an Event ?
 JavaScript's  interaction  with  HTML  is  handled through  events  that  occur  when
the user or the browser manipulates a page.
 When the page loads, it is called an event. When the user clicks a button, that
click too is an event.
 Other examples include events like pressing any key, closing a window, resizing
a window, etc.
 Developers  can  use  these  events  to  execute  JavaScript  coded  responses,
which cause buttons to close windows, messages to be displayed to users, data
to be validated, and virtually any other type of response imaginable.

 Events  are  a  part  of  the  Document  Object  Model  (DOM)  Level  3  and  every
HTML element contains a set of events which can trigger JavaScript Code.
 Please  go  through  this  small  tutorial  for  a  better  understanding HTML  Event
Reference.  Here  we  will  see  a few  examples  to  understand  a  relation  between
Event and JavaScript −
onclick Event Type
This  is  the  most  frequently  used  event  type  which  occurs  when  a  user  clicks  the  left
button of his mouse. You can put your validation, warning etc., against this event type.
## Example
Try the following example.
## Live Demo
## <html>
## <head>
<script type = "text/javascript">
## <!--
function sayHello() {
alert("Hello World")
## }
## //-->
## </script>
## </head>

## <body>
<p>Click the following button and see result</p>
## <form>
<input type = "button" onclick = "sayHello()" value = "Say
## Hello" />
## </form>
## </body>
## </html>
onsubmit Event Type
onsubmit is an event that occurs when you try to submit a form. You can put your form
validation against this event type.
## Example
The   following   example   shows   how   to   use   onsubmit.   Here   we are   calling
a validate() function     before     submitting     a     form     data     to     the     webserver.
If validate() function returns true, the form will be submitted, otherwise it will not submit
the data.

Try the following example.
## <html>
## <head>
<script type = "text/javascript">
## <!--
function validation() {
all validation goes here
## .........
return either true or false
## }
## //-->
## </script>
## </head>

## <body>
<form method = "POST" action = "t.cgi" onsubmit = "return
validate()">
## .......
<input type = "submit" value = "Submit" />
## </form>
## </body>
## </html>
onmouseover and onmouseout
These two event types will help you create nice effects with images or even with text as
well.  The onmouseover event  triggers  when  you  bring  your  mouse  over  any  element
and the onmouseout triggers when you move your mouse out from that element. Try
the following example.
## Live Demo
## <html>
## <head>
<script type = "text/javascript">
## <!--
function over() {
document.write ("Mouse Over");
## }
function out() {
document.write ("Mouse Out");
## }
## //-->
## </script>
## </head>

## <body>

<p>Bring your mouse inside the division to see the
result:</p>
<div onmouseover = "over()" onmouseout = "out()">
<h2> This is inside the division </h2>
## </div>
## </body>
## </html>
HTML 5 Standard Events
The  standard  HTML  5  events  are  listed  here  for  your  reference.  Here
script indicates a Javascript function to be executed against that event.
## Attribute Value Description
Offline script Triggers when the document goes offline
onchange script Triggers when an element changes
onclick script Triggers on a mouse click
onkeydown script Triggers when a key is pressed
onkeypress script Triggers when a key is pressed and released
onkeyup script Triggers when a key is released
onload script Triggers when the document loads
onmousedown script Triggers when a mouse button is pressed
onmousemove script Triggers when the mouse pointer moves
onmouseout script
Triggers when the mouse pointer moves out
of an element
onmouseover script
Triggers when the mouse pointer moves over
an element

onmouseup script Triggers when a mouse button is released
onmousewheel script Triggers when the mouse wheel is being
rotated
JavaScript - The Strings Object
The String object  lets  you  work  with  a  series  of  characters;  it  wraps
Javascript's string primitive data type with a number of helper methods.
As JavaScript automatically  converts between  string  primitives  and  String
objects,  you  can  call  any  of  the  helper  methods  of  the  String  object  on  a
string primitive.
## Syntax
Use the following syntax to create a String object −
## String Methods
Here  is  a  list  of  the methods  available  in  String  object  along  with  their
description.
## Method & Description
charAt()
Returns the character at the specified index.
concat()
Combines the text of two strings and returns a new string.
indexOf()
Returns  the  index  within  the  calling  String  object  of  the  first
occurrence of the specified value, or -1 if not found.
lastIndexOf()
Returns  the  index  within  the  calling  String  object  of  the  last

occurrence of the specified value, or -1 if not found.
search()
Executes  the  search  for  a  match  between  a  regular  expression
and a specified string.
slice()
Extracts a section of a string and returns a new string.

JavaScript - The Date Object
The  Date  object  is  a  datatype  built  into  the  JavaScript  language.  Date
objects are created with the new Date( ) as shown below.
Once a Date object is created, a number of methods allow you to operate
on it. Most methods simply allow you to get and set the year, month, day,
hour,  minute,  second,  and  millisecond  fields  of  the  object,  using  either
local time or UTC (universal, or GMT) time.
The ECMAScript standard requires the Date object to be able to represent
any date and time, to millisecond precision, within 100 million days before
or  after  1/1/1970.  This  is  a  range  of  plus  or  minus  273,785 years,  so
JavaScript can represent date and time till the year 275755.
## Syntax
You  can  use  any  of  the  following  syntaxes  to  create  a  Date  object  using
Date() constructor.
new Date( )
new Date(milliseconds)
new Date(datestring)
new Date(year,month,date[,hour,minute,second,millisecond ])
## Date Methods
Here is a list of the methods used with Date and their description.
Sr.No. Method & Description

## 1 Date()
Returns today's date and time
2 getDate()
Returns  the  day  of  the  month  for  the  specified  date  according  to
local time.
3 getDay()
Returns  the  day  of  the  week  for  the  specified  date  according  to
local time.
4 getFullYear()
Returns the year of the specified date according to local time.
5 getHours()
Returns the hour in the specified date according to local time.
6 getMilliseconds()
Returns  the milliseconds  in  the  specified  date  according  to  local
time.
7 getMinutes()
Returns the minutes in the specified date according to local time.
8 getMonth()
Returns the month in the specified date according to local time.
9 getSeconds()
Returns the seconds in the specified date according to local time.
10 getTime()
Returns the numeric value of the specified date as the number of
milliseconds since January 1, 1970, 00:00:00 UTC.


JavaScript - The Math Object
The math object  provides  you  properties  and  methods  for  mathematical
constants   and   functions.   Unlike   other   global   objects, Math is   not   a
constructor. All the properties and methods of Math are static and can be
called by using Math as an object without creating it.
Thus, you refer to the constant pi as Math.PI and you call the sine function
as Math.sin(x), where x is the method's argument.
## Syntax
The syntax to call the properties and methods of Math are as follows
var pi_val = Math.PI;
var sine_val = Math.sin(30);

## Math Methods
Here  is  a  list  of  the  methods  associated  with  Math  object  and  their
description
## Method & Description
abs()
Returns the absolute value of a number.
ceil()
Returns the smallest integer greater than or equal to a number.
cos()
Returns the cosine of a number.
floor()
Returns the largest integer less than or equal to a number.
log()

Returns the natural logarithm (base E) of a number.
max()
Returns the largest of zero or more numbers.
min()
Returns the smallest of zero or more numbers.
pow()
Returns base to the exponent power, that is, base exponent.
random()
Returns a pseudo-random number between 0 and 1.
sin()
Returns the sine of a number.
sqrt()
Returns the square root of a number.
tan()
Returns the tangent of a number.
What is different between XML and HTML?
Parameter XML HTML
Type of language XML is a framework for specifying
markup languages.
HTML is predefined markup language.
Language type Case sensitive Case insensitive
Structural details It is provided It is not provided.

Purpose Transfer of data Presentation of the data
Coding Errors No coding errors are allowed. Small errors are ignored.
Whitespace You can use whitespaces in your code. You can't use white spaces in your code.
Nesting Should be done appropriately. Does not have any effect on the code.
Driven by XML is content driven HTML is format driven
End of tags The closing tag is essential in a well-
formed XML document.
The closing tag is not always required.
<HTML> tag needs an equivalent </HTML> tag
but <br> tag does not require </br> tag
Quotes Quotes required around XML attribute
values.
Quotes are not required for the values of
attributes.
Object support Objects have to be expressed by
conventions. Mostly using attributes
and elements.
Offers native object supp
Learning curve Very hard as you need to learn
technologies like XPath, XML Schema,
DOM, etc.
HTML is a simple technology stack that is
familiar to developers.
Example of XML
<?xml version="1.0>
## <address>
## <name> Krishna Rungta</name>
## <contact>9898613050</contact>
## <email>krishnaguru99@gmail.com
## </email>
## <birthdate>1985-09-27</birthdate>
## </address>
Example of HTML

<!DOCTYPE html>
## <html>
## <head>
<title> Page title </title> </head>
## <body>
<hl> First Heading</hl> <p> First paragraph.</p> </body>
## </html>
Advantages of using XML
Here, are significant advantages of using XML:
 Makes documents transportable across systems and applications. With the
help of XML, you can exchange data quickly between different platforms.
 XML separates the data from HTML
 XML simplifies platform change process
Advantages of using HTML
Following are advantages of using HTML language:
 HTML document browser interfaces are simple to build
 It works across a system which is otherwise unrelated.
 HTML is easy to understand because it has a very simple syntax
 You can use many tags to make a webpage.
 Allows you to use various colors, objects, and layouts
Disadvantages of using XML
Here, are few drawbacks of using XML:
 XML requires a processing application
 The XML syntax is very similar to other alternative 'text-based' data
transmission formats which is sometimes confusing
 No intrinsic data type support
 The XML syntax is redundant
 Does not allow the user to create his tags.
Disadvantages of using HTML
Here, are few drawbacks of using HTML:

 HTML lacks syntax checking and structure
 HTML is not suitable for data interchange
 HTML is not context aware
 HTML doesn't allow us to describe the information content or the semantics of
the document
 HTML is not object-oriented, so it, not an extensible and very unstable
language
 Data storage and interchange of data are not possible using HTML.
What is AJAX?
 AJAX is a web development technique for creating interactive web
applications.
 If you know JavaScript, HTML, CSS, and XML, then you need to
spend just one hour to start with AJAX.
AJAX is a developer's dream, because you can:
 Update a web page without reloading the page
 Request data from a server - after the page has
loaded
 Receive data from a server - after the page has loaded
 Send data to a server - in the background
AJAX is Based on Open Standards
AJAX is based on the following open standards −
 Browser-based presentation using HTML and Cascading Style
Sheets (CSS).
 Data is stored in XML format and fetched from the server.
 Behind-the-scenes data fetches using XMLHttpRequest objects in the
browser.
 JavaScript to make everything happen.
Why to Learn Ajax?

AJAX  stands  for Asynchronous JavaScript   and XML.   AJAX   is   a   new
technique for creating better, faster, and more interactive web applications
with the help of XML, HTML, CSS, and Java Script.
 Ajax  uses  XHTML  for  content,  CSS  for  presentation,  along  with
Document Object Model and JavaScript for dynamic content display.
 Conventional  web  applications  transmit  information  to  and  from  the
sever using synchronous requests.
 It  means  you  fill  out  a  form,  hit  submit,  and  get  directed  to  a  new
page with new information from the server.
 With  AJAX,  when  you  hit  submit,  JavaScript will  make  a  request  to
the server, interpret the results, and update the current screen.
 XML  is  commonly  used  as  the  format  for  receiving  server  data,
although any format, including plain text, can be used.
 AJAX  is  a  web  browser  technology  independent  of  web  server
software.
 A  user  can  continue  to  use  the  application  while  the  client  program
requests information from the server in the background.
 Intuitive and natural user interaction. Clicking is not required, mouse
movement is a sufficient event trigger.
 Data-driven as opposed to page-driven.
## Example
## <html>
## <body>
<button type="button" onclick="loadDoc()">Change Content</button>
## <script>
function loadDoc() {
var xhttp = new XMLHttpRequest();
xhttp.onreadystatechange = function() {

if (this.readyState == 4 && this.status == 200) {
document.getElementById("demo").innerHTML = this.responseText;
## }
## };
xhttp.open("GET", "ajax_info.txt", true);
xhttp.send();
## }
## </script>
## </body>
## </html>
XMLHttpRequest Methods
 The XMLHttpRequest object is the key to AJAX.
 It has been available ever since Internet Explorer 5.5 was released in
July  2000,  but  was  not  fully  discovered  until  AJAX  and  Web  2.0  in
2005 became popular.
 XMLHttpRequest  (XHR)  is  an  API  that  can  be  used  by  JavaScript,
JScript,  VBScript,  and  other  web  browser  scripting  languages  to
transfer  and  manipulate  XML  data  to  and  from  a  webserver  using
HTTP,  establishing  an  independent  connection  channel  between  a
webpage's Client-Side and Server-Side.
 The data returned from XMLHttpRequest calls will often be provided
by back-end databases.
 Besides  XML,  XMLHttpRequest  can  be  used  to  fetch  data  in  other
formats, e.g. JSON or even plain text.
XMLHttpRequest Methods
 abort()

Cancels the current request.
 getAllResponseHeaders()
Returns the complete set of HTTP headers as a string.
 getResponseHeader( headerName )
Returns the value of the specified HTTP header.
 open( method, URL )
 open( method, URL, async )
 open( method, URL, async, userName )
 open( method, URL, async, userName, password )
 send( content )
Sends the request.
 setRequestHeader( label, value )
Adds a label/value pair to the HTTP header to be sent.
XMLHttpRequest Properties
 onreadystatechange
An event handler for an event that fires at every state change.
 readyState
The    readyState property    defines    the    current    state    of    the
XMLHttpRequest object.

