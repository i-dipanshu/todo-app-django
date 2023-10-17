# Sample Todo App Built using Django

## Activate virtual env


### 1. Windows
```powershell
python -m venv myenv
myenv\Scripts\python -m pip install --upgrade pip
```

## Start the application 

```sh
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
**Open localhost at port 8000 to view the application**