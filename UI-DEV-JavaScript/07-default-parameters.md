# Default parameters:
Default parameters in JavaScript allows your to set default values for arguments that are being passed in your function like the name suggests. Default parameters are great for undefined type parameters in your functions. 

For example in an e-commerce website you can set the value of the discount parameter to 0 or to 10% if you're having a sale so that whenever a customer checkouts from your site the 10% discount will be applied to his bill.

In ES5 we use the double pipe symbol **||** also called the **OR** symbol to define default parameters for arguments. We can also use a ternary operator or an If-else block.
When using the syntax of ES6 we don't need to use the OR operator or any If-else block. We just define the default value after the parameters which makes or code easier to understand.

```jsx
//Default parameters in ES6.
function calculatePayment(total, discount = 10, salesTax = 0.47);


//Default parameters in ES5
function calculatePayment(total,discount,salesTax){
	 salesTax = typeOf salesTax === 'undefined' ? 0.47 : salesTax
}

```

