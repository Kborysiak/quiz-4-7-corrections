# Quiz 4-7 Corrections
## Quiz 5
### Question 1)
For Question 1, I answered choice B, however, the correct answer was choice C. Choice C is the correct answer, as in order for the function to display which is the smallest choice of the three, an && statement is required so that both conditions will be met, and a will be true. The second line is also correct, as you need an || to make sure that c is not the smallest of the three, as if it is greater than one of the variables, it cannot be the smallest.
### Question 2)
For Question 2, I mistook the logical operators for the relational operators. The correct answers are all correct, as all of them are valid logical operators, whilst the answers that I chose were wrong as they were not valid logical operators.
### Question 4)
For Question 4, I mistook the relational operators for the logical operators. The correct answers are correct, as they are also valid relational operators, along with the other relational operators I entered.
### Question 6)
Along with the correct choice that I entered for this multiple select question, the fourth choice is also correct. This is because the first curly bracket does not have to be on the same line as the if statement is. It can look like this:
```
if(a<b)
{
  //do something
}
```
### Question 8)
In this multiple choice question, the second answer was correct as it is the simplest way to achieve the goal of assigning a letter grade to a student. The code I chose did extensive tests in order to verify if the grade should be an A,B,C ... However, the correct code achieves the same task, however, it does it in a way more efficient manner, as if one if statement is not met, the function will move onto the next else if.

### Question 9)
Along with the one correct answer I chose, the otehr two available choices for this question were also correct. This is because the two other ternary operators still effectively replace the if-else statement. The ternary operator does not have to all be on one line, and can be found on seperate lines, making the other two choices correct.

### Question 15)
Along with the correct answer I chose, the other multiple select answer was also correct as the do...while loop will still terminate, even if the do loop is performing x++.

## Quiz 6)
### Question 1)
Along with the one correct multiple select question I answered, the two other options alert and console.log() also accept built in parameters. My choice Math.Random was not correct, as Math.Random does not accept parameters, and it chooses a random number from the given parameter.

### Question 5)
For this question, I chose that the proper parameters were x,y. These two parameters are really vague, and would not do a good job and allowing the function to perform its implementation. The correct parameters base, and exponent make sense in this case as they give a hint to as what the function is doing.

### Question 6)
Along with the two correct multiple select choices, the third option is also a viable choice to perform multiplication. This is because, even though the two other correct choices are simpler the third choice also reaches the same goal, it just is more extensive and indepth.

### Question 7)
For Question 7, I chose the wrong answer. The answer I chose was wrong as the answer is the same answer as the premodified code. This code also does not accept parameters that are inputted from an outside source. 

### Question 12) 
For Question 12, I chose that 4 would be printed to the console. However, this is wrong, as either 4 or undefined can be printed to the console. This is because, if a does not equal 1, and or b does not equal 2, and or c does not equal 3, variable d will be undefined, meaning that the console.log would show undefined.

## Quiz 7)
### Question 1)
For Question 1, I put True, however, this is not correct as if one was to input all the aforementioned digits in the question, the correct response from the code would be False. This is because there is 4444 in the numbers array, meaning that it is not a three Digit number, making the output False.

### Question 14)
For Question 14, I answered that in order for the code to tell the user if the car exists in the array, the if statement should include 
```
cars[i]===car
```
However, this is not correct as there is no iteration over the variable I, and I isn't even defined as a variable. The correct answers: 
```
cars.includes(car)
cars.lastIndexOf(car) !== -1
cars.indexOf(car) !== -1
```
are all correct as they will let the user know if their input is in the cars array.
