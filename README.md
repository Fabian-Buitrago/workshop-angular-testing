# Your First Unit Test in Angular

Congrats!! 🎉🎉🎉 hope you did it well, if you didn't, do not worry, do it better next time. `app.component.spec.ts` file should look like this so far: 

```js
// 1. Create a basic testing structure using what you think it's necesary
describe('AppComponent', () => {

	// 2. declare a boolean variable called truly 
	let truly = true;
  
	// 3. Evaluate truly variable, be sure its value is true
	it('should evaluate truly variable to return true', () => {
		expect(truly).toBe(true);
    // or expect(truly).toBeTruthy();
	});
})
```

You already have tools to solve challenge #2, but before starting it's appropriate let you know that in Angular everything is a class (`Components`, `Services`, `Pipes`, etc), therefore you can make instaces of it. Remember import the respective class before instantiate it.

## Challenge #2

Time to test something real in our app. Use the same spec you created before:

- Import `AppComponent` into the spec.
- Create a new instance of it.
- Create a `spec` (`it`) to ensure `AppComponent` title varible is equal to `'Chuck Norris Jokes'`.

**You already know how to verify if everything it's ok in your code, if the 2 `specs` are successful then you're ready to take challenge #3**

### [Take next challenge >>](https://github.com/jevvilla/Workshop-ATesting/tree/3#your-first-unit-test-in-angular)
