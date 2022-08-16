# Python-Working-with-classes
Create the Parity class and its initialization method.

From the PyCharm menu, select Tools→Python or Debug Console.

In the Windows Defender dialog box, select the Allow Access button.
In the console, type class Parity: and press Enter.

Parity is the concept of numbers being odd or even. Your test class will determine if the number you provide is either odd or even.

Verify that the next prompt begins indented. Type def __init__(self, num): and press Enter.

Note: If you use the type feature in the lab to type the code above, verify that "self" appears only once within the parentheses.

Your initialization method takes self because it is an instance variable. This variable will be applied to all instances of the class. The other argument, num, is the number that you'll provide when you construct an instance of the class in order to check its parity.

Type self.num = num and press Enter.

This assigns the instance variable self.num to the number you're passing in. Now, in other methods that could go in this same class, you can use self.num to refer to each instance's num argument.

Create the check_parity() method to check if the number is odd or even.

Press Shift+Tab to go back one level of indentation.

The insertion point should now be on the same level as the def above.

Type def check_parity(self): and press Enter.

Note: If you use the type feature in the lab to type the code above, verify that "self" appears only once within the parentheses.

This method takes the instance variable self as its only argument. You'll only need to use an instance variable in this method, so this is the only argument it needs.

Type if self.num % 2 == 0: and press Enter.

This checks if the instance's number is evenly divisible by two.

Type print("{} is even.".format(self.num)) and press Enter.

Press Shift+Tab to go back one level of indentation.

Type else: and press Enter.

Type print("{} is odd.".format(self.num)) and press Enter.

Construct an instance of the Parity class.

Press Shift +Tab three times so that you're back at the highest level of indentation and no longer inside the class.

Type x = Parity(12345) and press Enter.

You're constructing an instance of class Parity as x and passing in 12345 as the num argument.

Observe the variable list.

An object named x has been created.

Select the arrow to the left of the x variable to expand the list.

When you created an instance of the object named x, you initialized the object with a num value of 12345.

In the Python console, type x.check_parity() and press Enter.

Verify that the console tells you the number contained within the object is odd.

Adjust your instance's number value dynamically.

At the prompt, type x.num = 42 and press Enter.

Type x.check_parity() and press Enter.

Verify that the num value changed and that the result is now even.
