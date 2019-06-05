# I want to...

record feature ideas for future implementation or dismissal

    create kanban board
    record idea in "Backlog" section
        

create kanban board

    create project
    template projectName/pm.org


create project

    $ mkdir projectName
    $ cd projectName
    $ git init
    template projectName/.gitignore
    $ git add .
    $ git commit -m "Initialize with .gitignore"
    create github repository
    $ git remote add origin git@github.com:<<<projectName URL>>>.git
    $ git push -u origin master


add a reference to a document

    $ mkdir -p toplevel_dir/publishedYear/publishedMonth/
    $ cd toplevel_dir/publishedYear/publishedMonth/
    template references/README.md
    
    function F() { mkdir -p $1/$2/; cp ../../procedures/template/references/README.md $1/$2/; }


create haskell package

    create project
    template projectName/stack.yaml
    template projectName/packageName/
    
    
add a new module in src/

    $ echo "module Path.To.Module where" > Path/To/Module.hs
    add `Path.To.Module` to package.yaml > library > exposed-modules
    template projectName/packageName/test/Module.hs
    

add a new executable to a project

    echo -e "module Main where\n\nmain :: IO ()\nmain = undefined" >> Path/To/executableName/Main.hs
    add to package.yaml > executables
        executableName:
          main: Main.hs
          source-dirs: executableName
          dependencies:
            - base

work with this document

    Step name is not indented
    Steps are indented 4 spaces and appear in temporal order
    template requires copying a template AND updating the content of that template according to the needs of the project
