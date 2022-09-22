# Challenge -15 min
1. Create 3 variables:
a. firstValue which will be assigned to the number 1
b. operator which will be assigned to the string “+”
c. secondValue which will be assigned to the number 2
2. Add three console.log to print the value of firstValue,
secondValue and operator in your browser console
3. Check in the browser that you can see the values
4. Now, replace the values using the prompt function to ask
the user to type it.
5. What are the prints of the three previous logs?

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>My website</h1>
    <script>
      let firstValue = prompt("Tell me your number");
      let operator = "+";
      let secondValue = prompt("Tell me your second value");;
      if (operator === "+") {
        
      }
    </script>
  </body>
</html>

------------------------------------------------------------------------------------------
Challenge - 10min number 1
1. Back to our calculator :
2. Remove the three console.log(...) from your code
3. Add a console.log of firstValue + secondValue: what is the
print?
4. Why?
5. Convert the values from string to number with the function
parseInt, eg: value = parseInt(value);
6. Now what is the print of the log?

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>My website</h1>
    <script>
      let firstValue = 1;
      let operator = "+";
      let secondValue = 2;
      console.log(firstValue + secondValue);

      if (operator === "+") {
      }
    </script>
  </body>
</html>







------------------------------------------------------------------------------------------

# Challenge -10 min number 2
1. Remove the previous console.log(...) from your code
2. Now you will add a condition on the value of the operator :
3. First you will test if the operator is equal to "+" If so, do a
console.log of firstValue + secondValue.
4. Then, in any other case, do a console.log of firstValue -
secondValue.


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>My website</h1>
    <script>
      let firstValue = 1;
      let operator = "-";
      let secondValue = 2;
      if (operator === "+") {
        console.log(firstValue + secondValue);
      } else {
        console.log(firstValue - secondValue);
      }
    </script>
  </body>
</html>
