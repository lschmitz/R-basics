# Executing R script

### Always use an editor (like the built-in R editor) for anything other than the simplest 1-line statements.

This saves your work for future use, and it doesn't choke when executing multiple lines. On a Mac, you can simply execute script from the R editor by highlighting code in the editor window and pressing “command + return”. If executing code line-by-line, command+enter will execute the line of code indicated by your cursor in the editor window. On a PC, Ctrl+R will do the same.

### Never, ever paste code from an editor window into R console!



# Operators

The "equals" sign in R is the arrow operator.


  `<-`

This must always go the same direction:

  `x <- 10`

and never

  `10 -> x`

The latter will work, but makes virtually unreadable code and you really do not want that. 

For more information on operators, please refer to this great [resource](https://www.statmethods.net/management/operators.html).



# R help is your friend

If you need more details on a function and its usage, you can always call the help file by typing 

  `?<name of function>`
  
For example, try 

  `?mean` or `?getwd`
  

# Always annotate your script, however easy and short it may be

Be nice to your future self and explain what you are doing. You may return to a script file in a year and, without comments, may find it hard to understand.

You can add annotations to your script file very easily: any text preced by `#` will be ignored by R.

`# The next line defines the value of x`

`x <- 12`



*Please let me know if you have additional items that should be added to this section.*
