# Lab-11-js
This code creates three variables shoppingList, input, and addButton to hold references to the <ul>, <input>, and <button> elements, respectively. It then creates a function addItem that runs in response to the button being clicked.

Inside the function body, it stores the current value of the input element in a variable inputValue, and then empties the input element by setting its value to an empty string.

It creates a new <li> element listItem, a <span> element span, and a <button> element deleteButton, and stores them in variables. It sets the text content of the span to the input element value, and the text content of the button to "Delete". It appends the span and the button as children of the list item, and then appends the list item as a child of the shopping list.

It attaches an event handler to the delete button so that, when clicked, it will delete the entire list item. Finally, it uses the focus() method to focus the input element ready for entering the next shopping list item.

The script also attaches the addItem function as an event listener to the add button using the addEventListener() method.
