React Docs - Lists and Keys
.map() returns an array.
Using the javascript map () function.
Each list item needs a unique string.
 the purpose of a key is to help React identify which items have changed, are added, or removed.
The Spread Operator 
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
Four things the spread operator can do is copy an array, using math functions, adding an item to a list, and combining objects.
const myArray = [`🤪`,`🐻`,`🎌`], const yourArray = [`🙂`,`🤗`,`🤩`], const ourArray = [...myArray,...yourArray], console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
const fewFruit = ['🍏','🍊','🍌'], const fewMoreFruit = ['🍉', '🍍', ...fewFruit], console.log(fewMoreFruit) // Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ], [..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ], const hello = {hello: "😋😛😜🤪😝"}, const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}, const helloWorld = {...hello,...world}, console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
How To Pass Function Into Components
The first step that the developer does to pass functions between component is to create a function
the increment function adds a count. 
To pass a method from a parent component into a child component you used this,props.name
Things I want to learn more about
How to practice more with combining than one array.
