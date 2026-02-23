# Experiment-7
# Aim: To study while loops in python.
# Theory:
- A while loop is a control structure in Python that allows a set of statements to be executed repeatedly based on a condition.
- It is mainly used when the number of iterations is not known in advance and depends on a condition being true.  
- A while loop repeatedly executes a block of code as long as the given condition evaluates to True.
- The condition is checked before every iteration.If the condition is True, the loop body executes.
- The while loop is used to execute statements repeatedly as long as a condition is true.
- Arithmetic operators and increment/decrement operators are used for calculations and loop control.
- break terminates the loop and continue skips the current iteration.
- % and // operators are used for digit extraction, reversal of numbers, and palindrome checking.
- else with while executes only when the loop completes normally without using break.
## Palindrome:  
A palindrome is a word, number, or sequence that reads the same forward and backward.  
Examples:121 → palindrome, madam → palindrome and 123 → not a palindrome.  
# Algorithm 1: To print i as long as i is less than 6
1. Start.
2. Initialise a variable with 1.
3. To check condition i<=5  using while statement.
4. If condition true then it prints i.
5. To increase i by by 1 using i+=1.
6. To repeat steps 3-5 until the condition becomes false.
7. End.
# Algorithm 2: Print Numbers from 1 to N
1. Start.
2. To take the input(n) from the user.
3. To initialise the variable with 1.
4. To check condition i<=n using while statement.
5. If condition true it prints i.
6. To increase i by 1 using i+=1.
7. To repeat steps 3-5 until the condition becomes false.
8. End
# Algorithm 3: To print the factorial of a given number
1. Start.
2. To take input from the user.
3. To initialise fact by 1.
4. To check condition if n>0 using while statement, if true multiply fact=fact*n.
5. To decrease the value of n in each term by 1 using n=n-1.
6. To repeat steps from 4-6 until n becomes 0.
7. To display the result(factorial).
8. End.
# Algorithm 4: To print the fibonnaci series.
1. Start.
2. To take the input of the number of terms(n) from the user.
3. To initialise a=0, b=1 and i=1.
4. To check condition i<=n using while statement, if true print a.
5. To calculate the next term using the formula c=a+b.
6. To update the values from a=b and b=c.
7. To increase the number of i by 1.
8. To repeat steps 4-8 until condition becomes false.
9. End.
# Algorithm 5: To print the fibonacci series with a given limit.
1. Start.
2. To take the input of the limit from the user till which number the user wants.
3. To initialise a=0 and b=1.
4. To check the condition a<=limit using while statement, if true prints a.
5. To calculate the next terms using a, b=b and a+b.
6. To repeat the steps from 4-6 until a becomes greater than the limit.
7. End.
# Algorithm 6: Reverse a Number using while Loop.
1. Start.
2. To take the input num from the user.
3. To initialise rev=0.
4. To check the condition if num>0, if true to find the last digit using digit=num%10.
5. To update the reversed number using rev=rev*10+digit.
6. To remove the last digit from the oringinal number using num=num//10.
7. To repeat from steps 4-7 until num becomes 0.
8. To display the result(reversed number).
9. End.
# Algorithm 7a: To check if a given number is a palindrome.
1. Start.
2. To take input(num) from the user.
3. To store it in another variable temp.
4. To intialise rev = 0.
5. To repeat while num > 0 using while statement.
6. To find last digit if digit = num % 10.
7. To add it to reverse it using rev = rev * 10 + digit.
8. To remove last digit using num = num // 10.
9. To compare temp and rev,if equal then prints Palindrome.
10. Else it prints Not Palindrome.
11. End.
# Algorithm 7b: To check if the word madam is a palindrome or not.
1. Start.
2. Assign the string s = "madam".
3. To set two variables:i = 0 (start index) and j = len(s) - 1 (end index)
4. To set is_palindrome = True
5. To repeat using while statement,if s[i] != s[j]
6. To set is_palindrome = False using break loop.
7. To increment i and decrement j by value of 1.
8. If is_palindrome == True print Yes using if statement.
9. Else print No using else statement.
10. End.
# Algorithm 7c: To check Palindrome String using While loop.
1. Start.
2. To input a string and store it in variable st.
3. To reverse the string and create a new variable rev such that rev = reverse of st.
4. To compare both strings and if st == rev then it print "Palindrome" uisng if statement.
5. Else it prints "Not a Palindrome" using else statement.
6. End.
# Algorithm 8: To count the number of digits in a given number.
1. Start.
2. To take input from the user and store it in variable num.
3. To initialize a variable count with 0.
4. To repeat while num > 0 using while statement.
5. To increase count by 1 using count = count + 1.
6. To remove the last digit of the number using num = num // 10.
7. To display the result(number of digits).
8. End.
# Algorithm 9: To Search an elment in a list.
1. Start.
2. To initialize the list.
3. To take input of the element to search and store it in key.
4. To initialize index variable i = 0 and to repeat while i < length of nums using while statement.
5. If nums[i] == key then it prints "Element found in index" by i+1 and to exit loop using break.
6. Else it increments i by 1,if loop ends without break (element not found) and prints "Element not found".
7. End.
# Algorithm 10: To print all the odd numbers between 1 to 10.
1. Start.
2. To initialize variable i = 0 and repeat while i < 10 using while statement.
3. To increment i by 1 using i = i + 1.
4. To check if i is even and if i % 2 == 0 using if statement under while.
5. To skip the remaining steps use continue otherwise it prints the value of i using continue.
6. End.
# Conclusion
Thus, the use of the while loop along with conditional and arithmetic operators in Python was successfully studied to generate the required output.
