# Reading 3: HTML Lists, Control Flow with JS, and the CSS Box Model

## Learn HTML

1. When should you use an unordered list in your HTML document?

> When you need to group a collection of items that do not have a numerical ordering, or if their numerical ordering isn't needed.

2. How do you change the bullet style of unordered list items?

> By using the CSS property "list-style". This allows you to change the style of the bullets.

3. When should you use an ordered list vs an unorder list in your HTML document?

> You should use an Ordered list when your collections of items needs to be displayed in a specific order, or in a certain series. An Unordered list can be used when the listed items don't need to be displayed in a specific order.

4. Describe two ways you can change the numbers on list items provided by an ordered list?

> The Start Attribute can be placed in the opening tag of the Ordered list which allows the list to start from a specific number. The style of the numbers can also be changed by using the "Type" Attribute in the opening tag of the Ordered list.

## Learn CSS

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
>The Margin is the outermost layer of the box, it wraps around all of the content within the box, while the padding exists as the white space in between the contents of the box and the border.

2. List and describe the four parts of an HTML elements box as referred to by the box model.
> Margin - The outermost layer of the box
> Border - Wraps around the box in between the padding and the content
> Padding - The innermost layer around the content, contained within the border
> Content - The space where the content of the box is displayed

## Learn JS

1. What data types can you store inside of an Array?
> We can store strings, numbers, objects, and other arrays.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
> Yes, the array is valid. To access a stored value simply place the number of the items index inside of a set of square brackets. To access an item from the inside of an array held within a second array, you will need to chain two sets of square brackets together. Place the index placement for the array in the first square bracket, and then the specific item index within the second square bracket. 

3. List five shorthand operators for assignment in javascript and describe what they do.
  1. Assignment Operators - Assigns a value to a variable
  2. Comparison Operators - Compares two operands 
  3. Arithmetic Operators - Performs a mathematical computation between two operands
  4. Conditional Operators - Takes three operands and returns a value dependent on which value is true
  5. String Operators - Concatenates two strings

4. Read the code below and evaluate the last expression and explain what the result would be and why.
> "10false'dog' would be the result because it would all be concatenated.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
> When checking if someones ID matches with their personal info

6. Give an example of when a Loop is useful in JavaScript.
> When a task has to be repeated several times, rather than running a script several times.
