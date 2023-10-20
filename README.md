Assignment: Asynchronous Programming in Javascript

Part 1: Callbacks

1. Create a simple HTML file with a button and a div element.
2. When a button is clicked, use a callback function to simulate a delay of 2 seconds and then update the text in the div element to display “Callback executed after 2 seconds”.

Part2: Promises

1.Create a new HTML file with a button and another div element.
2.When the button is clicked, create a Promise that simulates a successful asynchronous operation that resolves after 3 seconds. During this time, display "Loading..." in the div.
3.Once the Promise is resolved, update the text in the div to display "Promise resolved after 3 seconds."

Part 3: Promises with Error Handling (25 points)

1.Modify the previous HTML file to handle errors using Promises.
2.If the Promise takes longer than 5 seconds to resolve, reject it with a message like "Operation timed out."
3.Display the error message in the div if the Promise is rejected.

Part 4: Async/Await (25 points)

1.Create a new HTML file with a button and a div element.
2.When the button is clicked, create an asynchronous function that simulates a network request using setTimeout. This function should pause for 4 seconds and then return a message like "Data received successfully."
3.Use the await keyword within an async function to call this asynchronous function and update the text in the div with the message once the operation is complete.
