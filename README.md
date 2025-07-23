# User Management System

Roles: 
1. Admin
2. Customer

Admin:
1. Admin can Create, Update, Read and Delete User.
2. Only Admin can access Create, Update, List and DeleteView.

Customer:
1. Customer can Register himself.
2. He can Watch and Update his profile with profile photo(using signals).
3. He can't access User's Create, Update, List, Delete Page(using custom Mixins).


# Versions
1. Python - 3.10
2. Django - 4.1.6
3. Postgresql - 15.0
4. Template - 'Corona' by Bootstrap Dash.

# Django Installation Steps :-
1. Install Python 3.10
2. Install Django version 4.1.6
3. Install all dependencies cmd -python -m pip install --user -r requirements.txt
4. Finally run cmd - python manage.py runserver
