# Configuring the Python Interpreter

Used for linting.

Example of project configuration (MyProject.sublime-project):

```json
{
    "folders":
    [
        ...
    ],
    "settings":
    {
        "python_interpreter": "~/virtualenvs/my_project/bin/python3"
    }
}
```

Support Dark Mode in macOS Mojave:

```bash
$ defaults write com.sublimetext.3 NSRequiresAquaSystemAppearance 0
```
