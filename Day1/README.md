## Use stuff of JS Mini to-do project

- Let Const Var
- Equality, Truthy/Falsy, Coercion == vs ===, 0, "", null, undefined, NaN.
- Functions and arrow-function function decl vs expr; arrow functions; returning values
- Array and object `push/splice (mutate) vs map/filter (new array);`
- Dom Selection and event example `js querySelector, .textContent, .value, addEventListener('click',…).`



## Three error I got

- wrong variable name I create deleteBtn and try to append it to li, but variable is newTask, not li.

- wrong index reference like using the wrong index to access the tasks array.

- double appendChild mistakes like appending the same element multiple times.


# Process I do to make this project
1. **Analysis** - create to do list app where user can add, edit, and delete tasks. user also want to tasks to stay visible until completed
2. **Planning** - feature add planning (add tasks, delete tasks and marks completed)
3. **Design** Plan the layout:
- **html** => input box + add button + list section
- **css** => colors, spacing, hover effects
- **javascript** => functions to add, remove and mark tasks done
4. **Implementation** - write the code
- `index.html` => contains input fields and tasks list
- `style.css` => makes the app visibility clean
- `script.js` => html elements, id, 
5. **Deployment** - host the project in local server sending GitHub
6. **Maintenance** - fix bug (e.g. tasks not saving), add features (like localstorage to remember tasks after refresh)