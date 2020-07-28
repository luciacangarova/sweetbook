WAD GROUP PROJECT

To run our project (I hope the following steps are correct!):
1. git clone https://github.com/princesszet/sweetbook_project.git
2. mkvirtualenv sweetbook
3. pip install -r requirements.txt
4. python manage.py migrate
5. python manage.py makemigrations sweetbook
6. python manage.py migrate
7. python populate_sweetbook.py
8. python manage.py runserver
