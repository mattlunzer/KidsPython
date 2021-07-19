## Setup & Test Python

### Install Python
1. Go to https://www.manning.com/books/hello-world-third-edition/ to download and install the Windows installer, which includes Python 3.7.3.

### Test Python

2. Open IDLE (Python shell) & Type 

<pre lang="...">
print ("Hello World") 
</pre>

View the results. Try another phrase. What does the print command do? (Hint Print is a built-in function)

3.  Now try some math

<pre lang="...">
print (10 + 5)
</pre>

View the results. Try other mathmatical operations.

4. Try word combinations.

<pre lang="...">
print ("Daisy" + "Duke")
</pre>

View the results. Challenge, try a word times a number. What are the results?

5. On idle, click "File > New". Type the following;

<pre lang="...">
print ("I love pizza")
print ("pizza " * 10)
print ("yum " * 20)
</pre>

Save the file at c:\python\pizza.py

6. From Idle, click File --> Open the file

7. Click Run --> Run Module

View the results. Explain what happened. 

### Let's create a real program
    
8. On Idle, click File --> New. Type the following;

<pre lang="...">
import random 
secret = random.randint(1, 100) 
guess = 0 
tries = 0

print("AHOY! I'm the Dread Pirate Roberts, and I have a secret!") 
print("It is a number from 1 to 100. I'll give you 6 tries.") 

while guess != secret and tries < 6: 
 guess = int(input("What's yer guess? ")) 
 if guess < secret: 
    print("Too low, ye scurvy dog!") 
 elif guess > secret: 
    print("Too high, landlubber!") 
 tries = tries + 1 
if guess == secret: 
    print("Avast! Ye got it! Found my secret, ye did!") 
else: 
    print("No more guesses! Better luck next time, matey!") 
    print("The secret number was", secret) 
</pre>

Save the file at c:\python\NumGuess.py

9. From Idle, click File --> Open the file

10. Click Run --> Run Module

View the results. Explain what happened. 