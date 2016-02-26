## Solutions 

# 1 How many lexical scopes you can see here:

				function printMessage(message) {
				  console.log(message);  
				}

				function getMessageLength(message) {
				  return message.length;
				}


There are 3 scopes. 

# 2 Fix ReferenceError: askForAddress error

				deliverProduct();

				function deliverProduct() {
				  var address = askForAddress();
				}

				function takeOrder() {
				  function askForAddress() {
				    var address = {
				      houseNumber: '20',
				      street: 'Bond Street',
				      city: 'London',
				      country: 'United Kingdom'
				    };

				    return address;
				  }
				}


http://jsbin.com/xekagehiho/edit?js,console

# 3 Convert this named function into annonymous function:

				function sum(a, b) {
				  return a + b;
				}


http://jsbin.com/gojotuvoqo/edit?js,console

# 4 Convert this function into Immediately Invoked Function Expression (IIFE):

				function getMessageLength(message) {
				  return message.length;
				}

http://jsbin.com/camirefewu/edit?js,console

# 5 Create a JavaScript object that has a property which you can access like this:

				message.explained.translated.comments;

http://jsbin.com/fezenozuhe/edit?js,console

# 6 Write a function that: 1. Takes an array as a parameter 2. Iterates over each value in that array 3. Checks if the value's type is number 4. If it is - calculate the sum of all numbers

http://jsbin.com/karejavico/edit?js,console

# 7 Write an algorithm in JavaScript that sorts and returns an array of 3 numbers. 

http://jsbin.com/bomitunaru/1/edit?js,console


