# ti

Small template initializer

This is little is cript is needed to create frequently used templates for programming, writing, etc.


#### Usage:
- To get some general help, you can simply run `ti`.
- To list all existing templates run `ti list`, this will show all the templates in your *templates* directory.
- To create a new template, just make a new dir where ever you want, put everything in it and finally run `ti new <dir>`
- To initalize one of your templates run `ti init <name>`
- To show the structure of already existing template run `ti show <name>`
- To delete a template, run `ti del <name>`

#### Requirements:
The only thing is needed is `tree`, please install if it's not already installed on your system.

#### Workflow:
A template is simply a folder with everything you want your template to be inside of it. When you create, initialize or delete a template, one of those folders is being created, copied or deleted, really simple. All templates are stored in the *templates* directory, which you can change by changing the content of the variable of the same name, the default directory is `~/.config/ti`.

#### Installation:
Just allow script execution and copy or move the script itself in one of your path directories.
```
chmod +x ti
```
```
cp ti /usr/local/bin/ti
```

### Note:
Please, keep in mind, that this is not a fully stable piece of software, which will be updated in the future. I would love to see your bug reports, ideas and proposals, thanks!
