# The Recipe Card
> Never forget another recipe!

Create an object to hold information on your favorite recipe. 

It should have properties for:
* `title` (a string)
* `servings` (a number)
* `ingredients` (an array of strings)

On separate lines (one statement for each), display the recipe information so it looks similar to:
* Mole
* Serves: 2
* Ingredients:
  * cinnamon
  * cumin
  * cocoa

---

# Famous Penguins
Watching this [video](https://www.youtube.com/watch?v=bNdFQc-AlEQ&list=PLG6ePePp5vvZrPZCp85dssGxQ7QLfujt7&index=13) first would be very helpful.  Pay attention to how he does Method.
Pick a penguin from Wikipedia's [List of Fictional Penguins](https://en.wikipedia.org/wiki/List_of_fictional_penguins) and:
* create an object named `myPenguin` with properties that represent the information listed in each column on that Wikipedia page (for example: the character's name, origin, and author).
* Use `console.log()` to print the penguin's name to the console as part of a welcome message, like "Hello, I'm a penguin and my name is [NAME HERE]!"
* Write another line of code that adds a new property to your penguin called `canFly` and set it to `false`.
  * Note: Don't modify your penguin-creation code that you wrote above! Do this step in a separate line of code.
* Add a method to your penguin called chirp that prints to the console: "CHIRP CHIRP! Is this what penguins sound like?" (Note: Again, don't modify your previous code! Do this step by writing a new line of code.)
* Add another method to your penguin called sayHello that prints to the console the same message from step 20 above. But this time, be sure to use the mystical, magical, all-powerful this keyword to access your penguin's name, so that way the sayHello method could potentially work for any penguin that has a name!
* Next, call your penguin's sayHello() method and make sure that it works!
  * Hint: if you need an example of what it looks like when you call a method of an object, look at console.log() -- that's how you call the log() method of the console object!
* Without modifying any of your previous code, change the penguin's name to "Penguin McPenguinFace" and then call your penguin's sayHello() function one more time to make sure it still works.
* Write another method called fly, and inside that method, use an if / else statement to print "I can fly!" to the console if your penguin's canFly property is true, or "No flying for me!" if its canFly property is false.
  * Hint: Remember to use the very handy this keyword to access the object that your new method is currently attached to!
* Call your penguin's fly() method and make sure it works!
* Change the canFly property to true -- again, without modifying any of your previous code!
* Now call your penguin's fly() method again and make sure it works as expected!
* Write a for ... in loop to print each key to the console.
  * Hint: See this page for an example of this special type of loop.
* Write another for ... in loop to print the value of each key to the console.
  * (Hint: You'll need to use bracket notation to access the values this way, instead of dot notation!
