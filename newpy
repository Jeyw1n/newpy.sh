#!/bin/bash

if [ -n "$1" ]; then
    projectName="$1"
    
    mkdir "$projectName"
    echo " - Created new directory '$projectName'"
    cd "$projectName"

    python3 -m venv venv
    source venv/bin/activate
    echo " - Created python enviroment 'venv'"

    touch "main.py"
    echo " - Created 'main.py' file"

    echo
    ls -l

else
    echo "Enter project name! (newpy <name>)"
fi

