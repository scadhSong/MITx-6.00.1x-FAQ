# 6.00.1x Week 4 FAQ

**How to find answers to the midterm after submission ?**

In the short course everything had a deadline & we shared afterwards. Now it's self paced and last one year so we guess we'll put answers up then.
- - -

**I cannot access the Mid Term Exam**

Try different approaches to navigate to it. Also a different browser like Firefox. Persist.
- - -

**What the error Error 503 " Unable to deliver your submission to grader (Reason: failed to read from the server)" mean ?**

Wait a few hours before you try again. Maybe a fex submission instead.
- - -

**How to name a backup version of a file?**

Pick what works. one method is to add a z. It pushes things to the back of the directory list (2 backups = zz)

e.g. `MickeyMouse.py`, `zMickeyMouse.py`, `zzMickeyMouse.py`
- - -

**Why do we use those exception handlers if we can do all of this using simple `if` statements ?**

Its a language design choice.

Go returns all error messages as integers. So does C if it doesn't crash.

Python designers, operating at a higher level chose to use them and it does give some lovely code structure possibilities. Sometimes the exception version is faster than if else because 999 times out of 1000 there might be no exception. Sometimes it makes what you're doing clearer.
-- -

**What is the importance of closing file ?**

If you don't close a file, its data will stay in memory and that might be bad for performance.
- - -

**I'm confused on the difference between `raise` and `except`. Are they equivalent ?**

You can just type raise ZeroDivisionError in shell.

`raise` is generating an `exception`. `try`, `except` is a way of running code that might generate exception(s) and then handling those you have a plan for.
- - -

**What does "Exception as ex:" does ?**

An exception is an object like any other (so the thing `ex` is a name bound to an instance of that class) and the name of that instance is what is being passed.
- - -

**Why my marks are not getting updated ?**

If they were all ticked then it should update although, rarely, it can take an hour or so.

Check the detail in progress to see if they are ticked there too.
