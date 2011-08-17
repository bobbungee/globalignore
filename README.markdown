# Github Gitignore Compiler

Compiles your choice of [Github gitignores](https://github.com/github/gitignore)
to be used by git as a global gitignore

## Instructions

1. First clone the [Github gitignores](https://github.com/github/gitignore)

        git clone git://github.com/github/gitignore.git

2. Next clone this repo

        git clone git://github.com/bobbungee/globalignore.git

3. Run the gitignore compiler and follow the onscreen instructions

        cd globalignore
        ./globalignore

4. Tell git to use the generated file as a global gitignore

        git config --global core.excludesfile ~/.globalignore

## Sample Usage

*Enter the path to the gitignores:*

    ~/gitignore
    
*Enter the gitignores you want, one per line (e.g. Java).*
*Type 'done' when done*

    Java
    Rails
    OSX
    done
