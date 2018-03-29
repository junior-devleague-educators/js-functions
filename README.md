# JavaScript Functions

## Getting Started

You will be doing the function exercises in the JavaScript section of your code editor. There are two parts of this assignment:

* Part I of this assignment you will only use console.log()
* Part II of the assignment you will return values
  * Only move on to Part II if you covered `return` in class. Otherwise, wait for your instructor to move on to Part II

## Exercises

### Part I

Don't forget to invoke and pass in the appropriate arguments. Console log in the body of the function.

Example:

```
// Brew Coffee
function brewCoffee(ingredient1, ingredient2) {
    console.log(ingredient1 + " and " + ingredient2 = " make a cup of coffee.")
};

brewCoffee('water', 'coffee grounds'); // produces "water and coffee grounds make a cup of coffee
```

**Multiply**

1.  Create a function called `multiply`
2.  This function takes two parameters `num1` and `num2`
3.  Console log `num1` times `num2` in the body of the function
4.  Invoke your function and pass in the appropriate arguments

**Subtract Then Multiply**

1.  Create a function called `subtractThenMultiply`
2.  This function takes two parameters `num1` and `num2`
3.  In the body of your function create a variable called `difference` and store the difference of `num1` minus `num2`
4.  Then, console log `difference` times `num1`
5.  Invoke your function with the appropriate arguments

**Divide Then Add**

1.  Create a function called `divideThenAdd`
2.  This function takes two parameters `num1` and `num2`
3.  In the body of your function create a variable called `quotient` and store the quotient of `num2` divided by `num1`
4.  Then, console log `quotient` plus `num1`
5.  Invoke your function with the appropriate arguments

**Multiply Then Divide**

1.  Create a function called `multipyThenDivide`
2.  This function takes three parameters `num1`, `num2`, and `num3`
3.  In the body of your function create a variable called `product` and store the product of `num1` times `num3`
4.  Then, console log `product` divided by `num2`
5.  Invoke your function with the appropriate arguments

**Add Then Subtract**

1.  Create a function called `addThenSubtract`
2.  This function takes three parameters `num1`, `num2`, and `num3`
3.  In the body of your function create a variable called `sum` and store the sum of `num1` plus `num2`
4.  Then, console log `sum` minus `num3`
5.  Invoke your function with the appropriate arguments

**Get Remainder**

1.  Create a function called `getRemainder`
2.  This function takes two parameters `num1` and `num2`.
3.  In the body of your function console log to get the remainder of `num1` and `num3`
    * Hint: You can use the modulus ( % ) operator.
4.  Invoke your function with the appropriate arguments

**Math Champion**

1.  Create a function called `mathChamp`
2.  This function takes two parameters `name` (String value) and `num`
3.  In the body of the function, console log to produce the following sentence: `-name- has won -num- math decathlons.`
4.  Invoke your function with the appropriate arguments

**Winner**

1.  Create a function called `winner`
2.  This function takes three parameters `num1`, `num2`, and `sport` (String value)
3.  In the body of the function, console log to produce the following sentence: `My school has won -num1- + -num2- -sport- games this season.`
4.  Invoke your function with the appropriate arguments

**Lottery**

1.  Create a function called `lottery`
2.  This function takes in two parameters `location` and `name` with String values
3.  In the body of the function, console log to produce the following sentence: `The winner of the million dollar lotto is -name-. Please redeem your prize at -location-.`
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
2.  This function takes in one parameter `string` (String)
3.  Return the `string` parameter
4.  Create a variable for each client
5.  Invoke your function with a greeting of your choice as the argument and store it in a variable, repeat this for each variable you created.
6.  Console log each variable to greet each client
    * Example: `"Hello Mel"`

**Get All Client Accounts**

1.  Create a function called `getAllAccounts`
2.  This function takes in one parameter `accounts` (Object)
3.  Return all client accounts
4.  Invoke your function with the appropriate argument and store it in a variable
5.  Console log your variable and produce the following example sentence:
    * Example: `"Active Bank Accounts: {...}`

**Get An Individual Client Account**

1.  Create a function called `getClientAccount`
2.  This function takes in one parameter `account` (Array)
3.  Return the client's account
4.  Create a variable for each client
5.  Invoke your function with the appropriate argument and store it in the corresponding variable
6.  Console log each variable and produce the following sentence:
    * Example: `"Mel's deposits: [...]"`

**Get A Client's First Deposit**

1.  Create a function called `getFirstDeposit`
2.  This function takes in one parameter called `deposits` (Array)
3.  Return the first item in deposits
4.  Create a variable for each client
5.  Invoke your function with the appropriate argument and store it in the corresponding variable
6.  Console log each variable and produce the following sentence:
    * Example: `"Mel's latest deposit: $99.00"`

**Get A Client's Last Deposit**

1.  Create a function called `getLastDeposit`
2.  This function takes in one parameter called `deposits` (Array)
3.  Return the last item in deposits
    * Hint: To dynamically get the last item in an Array you can do `array[array.length - 1]`
4.  Create a variable for each client
5.  Invoke your function with the appropriate argument and store it in the corresponding variable
6.  Console log each variable and produce the following sentence:
    * Example: `"Mel's latest deposit: $99.00"`

**Get A Client's Total Count Of Deposits**

1.  Create a function called `clientDepositCount`
2.  This function takes one parameter `deposits` (Array)
3.  Return a client's total count of deposits
4.  Create a variable for each client
5.  Invoke your function with the appropriate argument and store it in the corresponding variable
6.  Console log each variable and produce the following sentence:
    * Example: `"Mel has made 5 deposits`"

**Get Total Count Of Bank Deposit Transactions**

1.  Create a function called `totalBankDeposits`
2.  This function takes in three parameters `client1, client2, client3` (Numbers)
3.  Return the total deposit transactions made at the bank
4.  Pass the variables you created from the previous exercise as your arguments
5.  Invoke your function with the variables you created in the previous exercise as your arguments and store it in a variable
6.  Console log the variable and produce the following sentence:
    * Example: `"Total Bank Deposit Transactions: 5"`
