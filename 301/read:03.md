# Read: Class 03 Passing Functions as Props

### React Docs - lists and keys

- What does .map() return?
	- it returns a list item element for each item

- If I want to loop through an array and display each value in JSX, how do I do that in React?
	- using .map

- Each list item needs a unique ____.
	- key

- What is the purpose of a key?

	- keys help react identify which items have changed, are added, or are removed
		from (https://reactjs.org/docs/lists-and-keys.html)


### The Spread Operator

- What is the spread operator?
	- to expand an iterable object into the list of arguments.
		from (https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- List 4 things that the spread operator can do.
	1. adding items to arrays
	2. combining arrays or objects
	3. spreading an array out into a functionβs arguments.
	4. Adding to state in React

- Give an example of using the spread operator to combine two arrays.
	- const myArray = [`π€ͺ`,`π»`,`π`]
		const yourArray = [`π`,`π€`,`π€©`]
		const ourArray = [...myArray,...yourArray]
			from (https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- Give an example of using the spread operator to add a new item to an array.
	- const fewFruit = ['π','π','π']
		const fewMoreFruit = ['π', 'π', ...fewFruit]
			from (https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- Give an example of using the spread operator to combine two objects into one.
	- const objectOne = {hello: "π€ͺ"}
		const objectTwo = {world: "π»"}
		const objectThree = {...objectOne, ...objectTwo, laugh: "π"}
		console.log(objectThree) // Object { hello: "π€ͺ", world: "π»", laugh: "π" }
		const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("π".repeat(5))}}
		objectFour.laugh() 
			from (https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)


### How to Pass Functions Between Components 

- In the video, what is the first step that the developer does to pass functions between components?
	- create a function where the state is that he is going to change

- In your own words, what does the increment function do?
	- it loops through the "people" array using map method to find out which one of the names had its button
	 	--that is below it-- clicked, and then adds a +1 to that counter which is initialized as 0. then returns the updated array


- How can you pass a method from a parent component into a child component?
	- maybe by passing it as a prop

- How does the child component invoke a method that was passed to it from a parent component?
	- by calling it and passing a name

