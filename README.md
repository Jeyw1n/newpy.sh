
# NewPy - Project Creation Script
NewPy is a simple script that allows you to quickly create new projects with a predefined directory and file structure.
It can be useful for those who use tiling managers or those who work only with the terminal.
## Installation
1.  Download the `newpy` script and place it in a directory, for example, `~/scripts/`.
2.  Ensure the script has executable permissions:
```bash
chmod +x ~/scripts/newpy
```
## Usage
To create a new project, run the command:
```bash
newpy <project_name>
``` 
Where `<project_name>` is the name of your new project.
## Adding to bashrc
To be able to run the script from anywhere, add the script's path to your `~/.bashrc` file:

1.  Open the `~/.bashrc` file in a text editor:
    
```bash
nano ~/.bashrc
```
2. Add the following line at the end of the file:   
```bash
export  PATH="$PATH:~/scripts"
``` 
3. Save the changes and close the editor.
4. Apply the changes:
```bash
source ~/.bashrc
``` 
Now you can run the `newpy` script from anywhere in the terminal.

