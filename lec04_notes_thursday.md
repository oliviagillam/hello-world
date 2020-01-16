# Announcements <h>
	
* Attend optional “Ninja Hours”
* Play around with Homework questions. Exam questions might be variations of Homework questions.

# General Questions <h>
* Q: Do we always have 2 hws in one week?
  * A: Sometimes, not always. Sometimes chapters are more complicated, so there may be only one for that week.

* Q: Will we have any practice exams that will be uploaded to the class website?
  * A: I will consider this

# Review...<h>
## iClicker Questions: <h>
  
  * Q1: Correct term for >>>print("Hello!")?
    * Correct Answer: C) This is a function call
    * Explanation: “the >>> signify that the next thing will be a function call"
    

  * Q2: Which version of squared was used in the call?
	  * Correct Answer: C) Can’t tell
    * Prof K: How could you tell which one was used?
      * Student Answer 1: set squared(8) equal to a variable and then print the variable. <br/> It will either output “None” or 	“64”
      * Student Answer 2: Use the "type" function
      * Student Answer 3: Add one to the function. If there is an error, it used the print function. If it outputs 65, it used the return function.
  * Q3: Which version of squared was used in the call?
    * Correct Answer: A) Version with return
    * Explanation: If it had been version with print, an error would have occurred since <br/> we can’t multiply type None by 2.

# New Material <h>
## User Input <h>
* User input gets stored as a string!
* Q: is there a way to limit inputs to only numbers?
	* A: For now, we will assume they input a number and we will force it to be a number.

```python
num = input("What is your favorite number?")
print("you said ", num)
num = int(num)        # this forces their input to be type int rather than str
print("mine is ", num + 1)
```
* If the user were to input a type other than just an integer, for example, a string like "eight" or a float like 8.0, there would be an error
	* > ValueError: invalid literal for int() with base 10: '8.0'
  
##   Escape Key <h>
  
```python
>>> 'O\'Brian said "Pay attention!" '
'O\'Brian said "Pay attention!" '
```
The print function removes the escape characters:
```python
>>> print('O\'Brian said "Pay attention!" ')
O'Brian said "Pay attention!"
```

* Note: When typing, you can use the tab key to complete a variable name
