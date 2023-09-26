# object-oriented-programming-html-tables

#### Explain why we need domain modeling.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

#### Why should tables not be used for page layouts?

1. Layout tables reduce accessibility for visually impaired users.
2. Table layouts generally involve more complex markup structures, resulting in code being harder to write, maintain, and debug.
3. Tables are sized according to their content by default (not 100% width of viewing device as with proper layout containers) so extra measures are needed to get table layout styling to effectively work across a variety of devices.

#### List and describe 3 different semantic HTML elements used in an HTML < table >.

- < thead > defines a set of rows defining the head of the columns of the table.
- < tbody > encapsulates a set of table rows (< tr > elements), indicating that they comprise the body of the table (< table >).
- < tfoot > defines a set of rows summarising the columns of the table.

#### What is a constructor and what are some advantages to using it?

A constructor is a function that will make an object. Calling a constructor will:

- create a new object
- bind "this" to the new object so you can refer to "this" in your constructor code
- run the code in the constructor
- return the new object

#### How does the term "this" differ when used in an object literal versus when used in a constructor?

An object literal binds "this" to the object the code is written inside; a constructor will bind "this" to the new object it makes.

#### Explain prototypes and inheritance via an analogy from your previous work experience. _NOTE: This is a very common front end developer interview question_

With a prototype (a method attached to a constructor) every object made will inherit the prototype so you only have to code it once.

When I was responsible training new hires for my department at Frontier Developments, I made a cheat sheet containing the 3 most important things to keep in mind. One was about a service that analysed crashes and pinpointed the root cause; it was overwhelming if you found out about it on your own time and scared hires away. By letting all new hires know the service existed, that it was simple and available at all times, I avoided having to train it out (i) individually, (ii) when it was too late, and (iii) after the new hire had encountered the anxiety of not being able to solve a problem.
