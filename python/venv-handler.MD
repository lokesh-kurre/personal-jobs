# Python - Virtual Environment Handler

It makes easy to handle different python virtual environment present in the system. A single interface to manage all the task create, activate, deactivate, list, remove any python virtual environment.

## Requirement
1. Python
2. PIP
3. VirtualEnv - PIP Module
This assumes that, you have already install python and had setup in environment.

## Installation Steps
Copy and paste the following command into terminal
```
curl -fsSL https://gist.githubusercontent.com/lokesh-kurre/4ff86d8aa58e8a4f2fe7508e422afee8/raw/install.cmd -o install.cmd && install.cmd && del install.cmd
```

## Info
```
$ venv
Makes Easy to Handle Python Virtual ENV

venv [command] [venvName] [targetDirectoy]

Possible Commands:

    -c, --create       Create Python Virtual Env with given names, in default directory
    -t, --target       Create Python Virtual Env in given directory
    -a, --activate     Activate Python Env with Given name, if it exist Do nothing
    --config           Config Venv Details
    -d, --deactivate   Deactivate the Activate Env
    -l, --list         List The Available Python Virtual Env
    -h, --help, -?     Displays help command
```
Created By Lokesh Kurre &hearts;
