# PyMadLibs
A (dynamic) Python implementation of the classic and fun Mad Libs game.

## Creating Custom Stories
The dynamic nature of this application allows the user to create their own stories. If you wish to add your own story, a key,value pair must be added to the dictionary in the code and the text file must exist in the 'stories' directory.

In the content of the file, I use what I call 'cues' to trigger the application's behavior of prompting the user for parts of speech. All cues are encased in a set of curly brackets {}. (Spaces are **NOT** supported!)

### Examples
> The cat jumped over the {big noun}.
(The above example wouldn't prompt the user to enter anything and would print back the exact string from the text file.)

> The cat jumped over the {noun}.
(The above example would prompt the user to enter a noun.)