# JavaScript Functions

## Getting Started

You will be doing the function exercises in the JavaScript section of your code editor. Don't forget to invoke/call your functions. There are two parts of this assignment. In Part I of this assignment you will just be console logging. In Part II of the assignment you will be returning values. Only move on to Part II if you covered the return value in class. Otherwise, wait for instructions from your instructor to move on to Part II.

Example:

```
// Add Then Subtract
var addTwoNums = 5 + 3;

function addThenSubtract(sum, num) {
    console.log(sum - num);
};

addThenSubtract(addTwoNums, 2);
```

## Exercises

### Part I

When invoking your functions you will have to either pass in the variable you created with each exercise and a number of your choice or pass in your own arguments. Console log inside of your functions.

**Multiply**

1.  Create a function called `multiply`
2.  This function takes two parameters `num1` and `num2`
3.  Multiply `num1` by `num2` in the function
4.  Invoke your function and pass in the appropriate arguments

**Subtract From Sum**

1.  Declare a variable called `sumOfNums` and store the sum of two numbers of your choice.
2.  Create a function called `subtractFromSum`
3.  This function takes two parameters `sum` and `num`
4.  Subtract `num` from `sum`
5.  Invoke your function with the appropriate arguments

**Subtract Then Multiply**

1.  Declare a variable called `diffOfNums` and store the difference of two numbers of your choice.
2.  Create a function called `subtractThenMultiply`
3.  This function takes two parameters `diff` and `num`
4.  Multiply `num` by `diff`
5.  Invoke your function with the appropriate arguments

**Add To Quotient**

1.  Declare a variable called `quotientOfNums` and store the quotient of two numbers of your choice.
2.  Create a function called `addToQuotient`
3.  This function takes two parameters `quotient` and `num`
4.  Add `num` to `quotient`
5.  Invoke your function with the appropriate arguments

**Multiply Then Divide**

1.  Declare a variable called `productOfNums` that will store the product of two numbers of your choice.
2.  Create a function called `multipyThenDivide`
3.  This function takes two parameters `product` and `num`
4.  Divide `product` by `num`
5.  Invoke your function with the appropriate arguments

**Get Remainder**

1.  Create a function called `getRemainder`
2.  This function takes two parameters `num1` and `num2`.
3.  Your function should get the remainder of `num1` and `num3`
    * Hint: You can use the modulus ( % ) operator.
4.  Invoke your function with the appropriate arguments

**Add To Difference**

1.  Declare a variable called `getDiffOfNums` that will store the difference of two numbers of your choice
2.  Create a function called `addToDiff`
3.  This function takes two parameters `diff` and `num`
4.  Add `num` to `diff`
5.  Invoke your function with the appropriate arguments

**Math Champion**

1.  Create a function called `mathChamp`
2.  This function takes two parameters `name` (String value) and `num`
3.  Create the following sentence:
    `-name- has won -num- math decathlons.`
4.  Invoke your function with the appropriate arguments

**Winner**

1.  Create a function called `winner`
2.  This function takes three parameters `num1`, `num2`, and `sport` (String value)
3.  Create the following sentence:
    `My school has won -num1- + -num2- -sport- games this season.`
4.  Invoke your function with the appropriate arguments

**Lottery**

1.  Create a function called `lottery`
2.  This function takes in two parameters `location` and `name` with String values
3.  Create the following sentence: `The winner of the million dollar lotto is -name-. Please redeem your prize at -location-.`
4.  Invoke your function with the appropriate arguments

---

### Part II

In this section you will be using the `return` keyword to produce a value.

Use the following bank object to do the exercises below:

```
var bank = {
    clientDeposits: {
        dali: [421.50, 309.78, 120.90, 732.84, 812.34],
        picasso: [680, 333.65, 901.54, 592.75],
        magritte: [2345.13, 890.32, 458.23, 124.95]
    }
}
```

**Access Each Client's Account**

1.  Create 3 variables `daliAcct`, `picassoAcct`, and `magritteAcct`
2.  Access the `bank` object and store the Array of each client to the corresponding variable.
3.  You will be using these variables for the exercises below

**Greet The Client**

1.  Create a function called `greeting`
2.  This function takes in one parameter `string`
3.  Return a greeting of your choice
4.  Create a variable for each client
5.  Invoke your function with the appropriate arguments and store it in the corresponding variable
6.  Console log each variable to greet each client
    * Example: `"-stringValue- Mel"`

**Get All Client Accounts**

1.  Create a function called `getAllAccounts`
2.  This function takes in one parameter `accounts` (Object)
3.  Return all client accounts
4.  Invoke your function with the appropriate argument and store it in a variable
5.  Console log your variable and produce the following example sentence:
    * Example: `"Active Bank Accounts: -objectValue-`

**Get An Individual Client Account**

1.  Create a function called `getClientAccount`
2.  This function takes in one parameter `account` (Array)
3.  Return the client's account
4.  Create a variable for each client
5.  Invoke your function with the appropriate argument and store it in the corresponding variable
6.  Console log each variable and produce the following sentence:
    * Example: `"Mel's deposits: -arrayValue-"`

**Get A Client's First Deposit**

1.  Create a function called `getFirstDeposit`
2.  This function takes in one parameter called `deposits` (Array)
3.  Return the first item in deposits
4.  Create a variable for each client
5.  Invoke your function with the appropriate argument and store it in the corresponding variable
6.  Console log each variable and produce the following sentence:
    * Example: `"Mel's latest deposit: $-numberValue-"`

**Get A Client's Last Deposit**

1.  Create a function called `getLastDeposit`
2.  This function takes in one parameter called `deposits` (Array)
3.  Return the last item in deposits
    * Hint: To dynamically get the last item in an Array you can do `array[array.length - 1]`
4.  Create a variable for each client
5.  Invoke your function with the appropriate argument and store it in the corresponding variable
6.  Console log each variable and produce the following sentence:
    * Example: `"Mel's latest deposit: $-numberValue-"`

**Get A Client's Total Count Of Deposits**

1.  Create a function called `clientDepositCount`
2.  This function takes one parameter `deposits` (Array)
3.  Return a client's total count of deposits
4.  Create a variable for each client
5.  Invoke your function with the appropriate argument and store it in the corresponding variable
6.  Console log each variable and produce the following sentence:
    * Example: `"Mel has made -numberValue- deposits`"

**Get Total Count Of Bank Deposit Transactions**

1.  Create a function called `totalBankDeposits`
2.  This function takes in three parameters `client1, client2, client3` (Numbers)
3.  Return the total deposit transactions made at the bank
4.  Pass the variables you created from the previous exercise as your arguments
5.  Invoke your function with the variables you created in the previous exercise as your arguments and store it in a variable
6.  Console log the variable and produce the following sentence:
    * Example: `"Total Bank Deposit Transactions: -numberValue-"`
