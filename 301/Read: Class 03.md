React Docs - Lists and Keys
.map() returns an array.
Using the javascript map () function.
Each list item needs a unique string.
 the purpose of a key is to help React identify which items have changed, are added, or removed.
The Spread Operator 
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a functionβs arguments.
Four things the spread operator can do is copy an array, using math functions, adding an item to a list, and combining objects.
const myArray = [`π€ͺ`,`π»`,`π`], const yourArray = [`π`,`π€`,`π€©`], const ourArray = [...myArray,...yourArray], console.log(...ourArray) // π€ͺ π» π π π€ π€©
const fewFruit = ['π','π','π'], const fewMoreFruit = ['π', 'π', ...fewFruit], console.log(fewMoreFruit) // Array(5) [ "π", "π", "π", "π", "π" ]
[...["ππππ€ͺπ"]] // Array [ "ππππ€ͺπ" ], [..."ππππππ₯°ππ€©!"] // Array(9) [ "π", "π", "π", "π", "π", "π₯°", "π", "π€©", "!" ], const hello = {hello: "ππππ€ͺπ"}, const world = {world: "ππππππ₯°ππ€©!"}, const helloWorld = {...hello,...world}, console.log(helloWorld) // Object { hello: "ππππ€ͺπ", world: "ππππππ₯°ππ€©!" }
How To Pass Function Into Components
The first step that the developer does to pass functions between component is to create a function
the increment function adds a count. 
To pass a method from a parent component into a child component you used this,props.name
Things I want to learn more about
How to practice more with combining than one array.
