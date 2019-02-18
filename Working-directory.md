
R needs to know where to look for files or where to save files so we need to specify that information.

```
#get the current working diretory
getwd()
```

While I write this, my R working directory is set to:
```
> getwd()
[1] "C:/Users/lschmitz/Documents"
```

If I want to set the working directory to a different folder, I need to specify a new file path.
```
#set working directory
setwd("C:/Users/lschmitz/Documents/R-Code")
```
