record feature ideas for future implementation or dismissal

    create kanban board
    record idea in "Backlog" section
        

create kanban board

    create project
    $ mkdir projectName/pm
    template projectName/pm/projectName.org


create project

    $ mkdir projectName
    $ git init projectName
    template projectName/.gitignore
    $ git -C projectName add .
    $ git -C projectName commit -m "Initialize with .gitignore"
    create github repository
    $ git -C projectName remote add origin git@github.com:<<<projectName URL>>>.git
    $ git -C projectName push -u origin master


work with this document

    Step name is not indented
    Steps are indented 4 spaces and appear in temporal order
    template requires copying a template AND updating the content of that template according to the needs of the project
