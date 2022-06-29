TIC TAC TOE

step 1 : To make the tac tac toe game we have to make the grid dynamic to do that we can create an object with 9 keys and initiate each key with null. and then declare the object using useState in the parent component. so that instead of creating a seperate useState for each of the grid item we can utilise this single object to manipulate each grid item.

step 2 : Create a function in the parent component that will update the object on any change that happens

step 3 : pass the function to the child div, so that the child div can pass the key of that particular box that is been clicked, and the the function will get invoked it will then modify the object that have a record of each grid item

![ticTacToe](./WhatsApp%20Image%202022-06-29%20at%2011.30.44%20AM.jpeg)
