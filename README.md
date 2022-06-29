# javascript-building-blocks-loops

Read through the lesson at https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code and then complete the tasks at https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code#test_your_skills by editing the files in this repository.

## Notes

### Task 1

The code at https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code#active_learning_launch_countdown should help you to see how to add text to an `li` element and also how to append `li` elements to a `ul` element.

### Task 2

To access the name field of the first object in the phonebook array, you would use the code `phonebook[0].name`.  To access the phone number for this first object, you would use the code `phonebook[0].number`. Once you have access to a name or phone number of an object, you can treat it like any other variable.  For instance, the code 
``` 
phonebook[1].name = 'Alex'
```
assigns the string `Alex` as the name field value for the second object in the phonebook array.

Notice that this task says to use a type of loop that you did not use in the first task. Assuming that you used a for-loop for the first task, this means to use a `while` or `do while` for this task. Note that it is easy to produce an "infinite loop" when you are writing something other than a for-loop. If you don't see any output when you try to run your program, you might be in an infinite loop. If so, you might need to close the brower tab and try again. If you were testing in your Codespace, after closing the browser tab you will want to return to the Codespace you were in rather than creating a new Codespace.

### Task 3

By "some kind of separator" they mean one or more spaces, or a comma and a space, or something like that. Notice that you need to use the third type of loop!
