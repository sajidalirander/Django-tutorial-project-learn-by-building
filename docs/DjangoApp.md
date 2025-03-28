# Create a Django App
Activate the virtual environement 
```
source .venv/bin/activate
```
Run the adminstrative utility in the project folder (where `manage.py` resides):
```
cd defaultDjango
python manage.py startapp myApp
```
The command creates a folder `myAPP` which contains the following main files:
1. `views.py`: contains the functions that define pages in the web app. 
2. `models.py`: contains classes defining the data objects.

### Creating a simple view
Modify `myApp/views.py` to creates a single view for the app's home page:


### Map the URL

