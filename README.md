# Experiment-7
# Aim: Study of While loop in Python
# Theory:
- The while loop is used to execute statements repeatedly as long as a condition is true.  
- input() is used to take input from the user and int() converts it into integer form.  
- if–else statements are used for decision making.  
- Arithmetic operators and increment/decrement operators are used for calculations and loop control.
- break terminates the loop and continue skips the current iteration.
- % and // operators are used for digit extraction, reversal of numbers, and palindrome checking.  
- else with while executes only when the loop completes normally without using break.
## Algorithm 1: To print i as long as i is less than 6
1.Start.  
2.Initialize variable i with a value.  
3.While i < 6, print the value of i using print().  
4.Increment i using i += 1.  
5.Repeat until the condition becomes false.  
6.Stop.  
## Algorithm 2: Print Numbers from 1 to N
1.Start.  
2.Accept the value of N using input() and convert it into integer using int().  
3.Initialize variable i = 1.  
4.While i ≤ N, print the value of i using print().  
5.Increment i using i += 1.  
6.Stop.  
## Algorithm 3: To print the factorial of a given number
1.Start.  
2.Read integer n using input().  
3.Initialize fact = 1.  
4.Repeat while n > 0.  
5.Update fact = fact * n.  
6.Decrement n = n − 1.  
7.Display factorial using print().  
## Algorithm 4: To print the fibonnaci series
1.Start.  
2.Take number of terms using input() and convert using int().  
3.Initialize a = 0, b = 1, and counter i = 1.  
4.Print initial terms using print().  
5.While i ≤ n, find next term using c = a + b.  
6.Print term and update values using assignment.  
7.Increment counter using i += 1.  
8.Stop.  
## Algorithm 5:To print the fibonacci series with a given limit
1.Start.  
2.Read limit using input() and convert with int().  
3.Initialize a = 0, b = 1.  
4.While a ≤ limit, repeat.  
5.Print a using print(end=" ").  
6.Update a, b = b, a + b.  
7.Stop.  
## Algorithm 6: Reverse a Number using while Loop
1.Start.  
2.Take an integer using input() and convert it using int().  
3.Initialize rev = 0.  
4.While number is greater than 0.  
5.Extract digit using % and update rev using * and +.  
6.Remove digit using //.  
7.Print the reversed number.  
8.Stop.  
## Algorithm 5:To check if a given number is a plaindrome
1.Start.  
2.Read a number using input() and convert it using int().   
3.Store the number in num and copy it to temp.  
4.Initialize rev = 0.  
5.While temp > 0, reverse the number using %, *, +, and //.  
6.Compare num and rev using if–else.  
7.Display result using print().  
8.Stop.  
## Algorithm 6: To check if the word madam  is a palindrome or not.
1.Start
2.Assign the string s = "madam"
3.Initialize i = 0 and j = len(s) − 1
4.Set is_palindrome = True
5.While i < j, repeat.
6.If s[i] ≠ s[j], set is_palindrome = False and break.  
7.Increment i by 1 & Decrement j by 1.  
8.If is_palindrome is True, print “The word is a palindrome”.  
9.Else, print “The word is not a palindrome”.  
10.Stop.  
## Algorithm 7: Palindrome String using While loop
1.Start.  
2.Accept a string using input() and store it in variable s.  
3.Initialize two index variables i = 0 and j = len(s) - 1.  
4.Use a while i < j loop to compare characters.  
5.If s[i] != s[j], print not palindrome and stop.  
6.Increment i and decrement j.  
7.If loop completes, print palindrome using print().  
8.Stop.  
## Algorithm 8: To count the number of digits in a given number
1.Start.  
2.Read a number using input() and convert it into integer using int().  
3.Initialize count = 0.  
4.Use while num > 0 to repeat the process.  
5.Increment count using count += 1.  
6.Remove last digit using num = num // 10.  
7.Display the result using print().  
8.Stop.  
## Algorithm 9: Search an elment in a list
1.Start.  
2.Read list elements and search element using input().  
3.Initialize index i = 0.  
4.While i < len(list), compare element using if.  
5.If found, print position and exit using break.  
6.Increment index using i += 1.  
7.If loop ends, execute else to print not found.  
8.Stop.  
## Algorithm 10: To print all the odd numbers between 1 to 10
1.Start.  
2.Initialize variable i = 1.  
3.Use while i ≤ 10 to repeat the steps.  
4.Check if the number is odd using if i % 2 != 0.  
5.Print the value of i using print().  
6.Increment i using i += 1.  
7.Stop.  
