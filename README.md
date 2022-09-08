# Solipath Python/Poetry example project
This is a quick showcase of using Solipath for a python project

Please note that Python and ZLib are compiled from source on Linux and Mac. It will take some time to get ready.

To install poetry dependencies and run tests from the command line:
```bash
./solipath poetry install
./solipath poetry run pytest
```

or from command prompt:
```cmd
solipath poetry install
solipath poetry run pytest
```

If you have vscode so you can start it from the command line
Running the following command would start up vscode with path variables set from solipath
```bash
./solipath code .
```

I suspect that the same would apply for any other kind of editor as long as you prefix the command that would normally start it with solipath

If you have an existing python project, all you should need to do is copy the solipath, solipath.bat (once it is there), and the solipath.json files over to your project.


## Licensing
I threw on an MIT License on this project just because my understanding is that if it doesn't have some kind of license, it becomes impossible for people to use. Please let me know if there is anything I can do to make this easier!
