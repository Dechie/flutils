# FLUTILS: A COMMAND LINE TOOL FOR FLUTTER UTILITIES

*Developed by: Logos*
        
## COMMANDS:

new - 
	creates a new project, with basic folder structure, and also adds 'assets/images' folder by default
makemodel e.g.: `cre.sh makemodel <model_name>`
                        creates a new model class, using specified file name. file name shall be specified in snake case, and the model's identifier name will be inferred from that. i.e., it will be a pascal-case version of the former
makewidget e.g.: `cre.sh makewidget <widget_name>`
                        creates a basic StatefulWidget. again the name will be inferred from file name provided in snake case
packs `e.g.: cre.sh packs "package1" "package2"`
                        expects a list of package names surrounded by " " separated by spaces, it will add each of the packages to the project.
                        `

## Installation:
  
Copy the file 'cre.sh' to '~/bin' directory, if the directory doesn't exist create it:
`mkdir -p ~/bin`

**Then run these commands:**

If Your terminal is Bash:
```
chmod +x ~/bin/cre.sh
echo 'export PATH=$PATH:~/bin/cre.sh' >> ~/.bashrc
source ~/.bashrc
```

If Your terminal is Zsh:
```
chmod +x ~/bin/cre.sh
echo 'export PATH=$PATH:~/bin/cre.sh' >> ~/.bashrc
source ~/.bashrc
```

Now you can run the script from any directory in your machine. 

N.B: This only applies for the current user; if you have different users in your machine it will not work.
