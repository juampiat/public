##### Ansible Múltiple Versions running in the same Ubuntu Linux

```sudo apt update```
```sudo apt upgrade```
```python3 -m pip install --upgrade pip```
```apt install python3.8-venv```

##### Creation of virtual environments (3 dif ver)
```python3 -m venv ~/ansible-2.x-env```
```python3 -m venv ~/ansible-5.x-env```
```python3 -m venv ~/ansible-6.x-env```

##### Ingreso al entorno virtual correspondiente versión 2.x

```source ~/ansible-2.x-env/bin/activate```
```pip install ansible==2.10.7```

```source ~/ansible-5.x-env/bin/activate ```
```pip install ansible==5.12.3```

```source ~/ansible-6.x-env/bin/activate``` 
```pip install ansible==6.7.0```
##### Deactivate virtual environments

```deactivate```

In your file:  alias .bashrc / .zshrc optativo.

sw_ans_2='source ~/ansible-2.x-env/bin/activate'
sw_ans_5='source ~/ansible-5.x-env/bin/activate'
sw_ans_6='source ~/ansible-6.x-env/bin/activate'
sw_d=deactivate

Go to [Papers](../papers.md)
Go to [Index](../../readme.md)