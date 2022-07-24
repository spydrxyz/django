# Django Installation

#### **Author:** Shajjad Hossain
*UI/UX Designer, Tirzok Private Limited*

---
Based on your operating system kindly follow steps by steps to avoid any kind of error.
## Windows
- Step 1: Download [Python](https://www.python.org/downloads/) from official website
- Step 2: Install python3 using custom settings and checked `install for all user`
- Step 3: Create venv using `c:\Program Files\Python[version]\python.exe -m venv [folder_path]` (e.g. "c:\Program Files\Python37\python.exe" -m venvvertual_environment)
- Step 4: Go to venv folder using `cd [folder_name]` (e.g. cd vertual_environment)
- Step 5: Activate venv using `\Scripts\activate.bat`
- Setp 6: Install requiremnets using `pip install -r requirements.txt` if available
- Step 7: Make migration using `python manage.py makemigrations`
- Step 8: Migrate using `python manage.py migrate`
- Step 9: Create super user using `python manage.py createsuperuser`
- Step 10: Run the project using `python manage.py runserver`


## Ubuntu
- Step 1: Intstall python3 using `sudo apt-get install python3-venv`
- Step 2: Create venv using `python3 -m venv [folder_name]` (e.g. python3 -m virtualenv testenv)
- Step 3: Activate env using `source env/bin/activate`
- Step 4: Install requiremnets using `pip install -r requirements.txt` if available
- Step 5: Make migration using `python manage.py makemigrations`
- Step 6: Migrate using `python manage.py migrate`
- Step 7: Make super user using `python manage.py createsuperuser`
- Step 8: Run the project using `python manage.py runserver`

---
