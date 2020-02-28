# working-with-decimal-number

as with the string object the properties and method of the number object can be used with with any value that is a number
in this example a number is stored in a variable called originalNumber and it is then roundedup or down using two different techniques
in both cases you need to indicate how many digits you want to round to this is provided as a parameter in the parentheses for that method
originalNumber.toFixed(3)will round the number stored in the variable originalNumber to three decimal places (the number of decimal places is specified in the parentheses) it will return the number as a string it return a string because fractions cannot always be accurately represented using floating point numbers
toPrecision(3) uses the number in parentheses to indicate the total number of digits the number should have it will also return the number as a string it may return a scientifc notation if there are more digits than the specified number of positions.
