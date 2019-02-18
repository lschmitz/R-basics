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

The latter will work, but makes virtually unreadable code. For more information on operators, please refer to this great [resource](https://www.statmethods.net/management/operators.html).
