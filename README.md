# ai-dev-tools

##################################### Module 1 --- Homework #############################################
## Installing Python
winget install 9NQ7512CXL7T

## Installing Django
# Create a project folder
mkdir my-django-project
cd my-django-project

# Create virtual environment
python -m venv .venv

# Activate virtual environment
.venv\Scripts\Activate.ps1

# Install Django
pip install Django

# Verify Django installation
py -m django --version

##Output: 5.2.8


####################Creating Project and an App in Django ##################

# Navigate to where you want your project (e.g., Documents)
cd "c:\Users\heman\Documents"

mkdir myDjangoProject 

cd myDjangoProject

# Create virtual environment
py -m venv venv

# Activate it
venv\Scripts\activate

# Install Django
pip install django

# Outcome: Successfully installed asgiref-3.11.0 django-5.2.8 sqlparse-0.5.3 tzdata-2025.2

dir mysite
# Output
# Directory of c:\Users\heman\Documents\myDjangoProject\mysite

# 26/11/2025  14:14    <DIR>          .
# 26/11/2025  14:14    <DIR>          ..
# 26/11/2025  14:14               405 asgi.py
# 26/11/2025  14:14             3,283 settings.py
# 26/11/2025  14:14               784 urls.py
# 26/11/2025  14:14               405 wsgi.py
# 26/11/2025  14:14                 0 __init__.py

Open URL: http://127.0.0.1:8000/
Outcome: <img width="1522" height="822" alt="image" src="https://github.com/user-attachments/assets/d8ddf565-1466-4856-8e33-e8e8f4b6730c" />







