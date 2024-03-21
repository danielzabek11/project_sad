# Setting up virtual env on windows
First create virtual environment:
```shell
python -m venv venv
```
Then activate it:
```shell
venv\Scripts\activate
```
If you get error on activation try running windows powershell as administrator and write:
```shell
set-executionpolicy remotesigned
```
Then accept with (Yes to all) [A]
# Setting up vnev kernel in jupyter notebook
```shell
python -m ipykernel install --name=vnevtoy
```
You might have to install ipykernel first to run this command:
```shell
pip install ipykernel
```

After creating the kernel you can choose it through notebook UI Kernel -> Change kernel... and pick vnevtoy *Note sometimes it takes a while for it to appear try restarting kernel and waiting
# Installing reqs
When you are already in virtual env install reqs:
```shell
pip install -r requirements.txt
```


