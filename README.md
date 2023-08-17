# PythonHacks
In Ubuntu:
1. To check the python version
```
alias python=python3
python --version
```
2. To create virtual environment
   
```
python3 -m venv env_name
```
```
chmod +x env_name/bin/activate  -> Use this for give write access.
```

```
airflow_env/bin/activate -> Then activate.
In termianl type: deactivate -> To deactivate the virtual environment.
```
3. If you have installed lot of Packages or libraries you can remove all by:

Create a List of Installed Packages:
 ```
pip freeze > requirements.txt
 ```

Uninstall Packages: 
```
while read requirement; do pip uninstall -y $requirement; done < requirements.txt

```
