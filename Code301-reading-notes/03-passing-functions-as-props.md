# passing-functions-as-props

#### What does .map() return?

An array with the results of a function applied to every element of an existing array.

#### If I want to loop through an array and display each value in JSX, how do I do that in React?

const array = [1,2,3,4,5];
const loopThru = array.map((array) => <li>(array)</li>);

#### Each list item needs a unique \_\_\_\_.

Key!

#### What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed.

#### What is the spread operator?

The spread operator (...) allows us to quickly copy all or part of an existing array or object into another array or object.

#### List 4 things that the spread operator can do.

- Copy an array
- Concatenate an array
- Conditionally adding values to an array
- Copying and merging objects

#### Give an example of using the spread operator to combine two arrays.

let arr1 = [0, 1, 2];
const arr2 = [3, 4, 5];

arr1 = [...arr1, ...arr2];

#### Give an example of using the spread operator to add a new item to an array.

const parts = ["shoulders", "knees"];
const lyrics = ["head", ...parts, "and", "toes"];

#### Give an example of using the spread operator to combine two objects into one.

const obj1 = { foo: "bar", x: 42 };
const obj2 = { bar: "baz", y: 13 };

const mergedObj = { ...obj1, ...obj2 };
