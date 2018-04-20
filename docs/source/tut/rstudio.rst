Self-contained projects in RStudio
==================================

R can be launched in two different ways, from the GUI or from the CLI. 

- When launched via the GUI app it creates a history file .Rapp.history and, if the session gets saved in the end, an .Rdata file in the user's home directory
- When launched from the CLI, these files are created in the user's current working directory.

This difference gives you possibility to achieve some separation between your projects when using R.


When RStudio is launched it creates an R session with the user's home directory as a *working directory*. This session's environment and the history of R commands are saved in the home directory (.Rdata and .Rhistory files). You can always change the *working directory* to a folder where you have some data and/or scripts.

