# Create Increment Counter Using React

Should have Knowledge in <br />
1. ES6  <br />
2. React <br />


##Explaination

Set strikes initial value is 0. <br />
You can able to change initial state value from here <br />
``` Es6 React JavaScript 
 this.state = {	strikes: 0 };
```

Then Change strikes increment value by 100 <br />
``` Es6 React JavaScript 
timerTick() {
	this.setState((prevState) => {
		return {
			strikes: prevState.strikes + 100
		};
	});

	// OR 

	// this.setState({
	//     strikes: this.state.strikes + 100
	// });
}
```