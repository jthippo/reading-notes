# html-lists-js-control-flow-css-box-model

### HTML

#### When should you use an unordered list in your HTML document?

When you'd use bullet points, i.e. when the list order doesn't matter.

#### How do you change the bullet style of unordered list items? / Describe two ways you can change the numbers on list items provided by an ordered list?

Using the CSS _list-style-type_ property, not the depreciated HTML _type_ attribute.

### CSS

#### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Padding and Margin are in love, even when Padding gets _really_ big. Sadly, they will never meet - they are forever kept apart by that rascal and villain, Border.

#### List and describe the four parts of an HTML elements box as referred to by the box model.

- Content - what goes inside the box
- Padding - distance around the Content
- Border - wrapping around the Padding
- Margin - a buffer around the Border and other page elements

### JS

#### What data types can you store inside of an Array?

Any!

#### Is the people array below a valid JavaScript array? If so, how can I access the values stored? If not, why?

_const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];_

Yes, arrays and mixed data can go inside an array. To console log "accountant" here for example, you'd go with:

console.log(people[1][2]);

#### List five shorthand operators for assignment in JavaScript and describe what they do.

- Addition assignment (+=): assigns the variable to the original value plus a second value
- Subtraction assignment (-=): assigns the variable to the original value minus a second value
- Multiplication assignment (\*=): assigns the variable to the original value times a second value
- Division assignment (=): assigns the variable to the original value divided by a second value
- Remainder assignment (%=): assigns the variable to the remainder of the original value divided by a second value

#### Read the code below and evaluate the last expression and explain what the result would be and why.

_let a = 10;_
_let b = 'dog';_
_let c = false;_

_// evaluate this_
_(a + c) + b;_

(10 (number) + false (null)) + 'dog' (string) = '10dog'

#### Describe a real world example of when a conditional statement should be used in a JavaScript program.

Checking if a user is logged in, if a user has access to something, if an item or area has been unlocked in a video game.

#### Give an example of when a Loop is useful in JavaScript.

Loops are used to repeat a block of code, e.g. if you want to show a message 100 times, perhaps with slight variations each time.
