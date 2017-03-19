# Python 3 Flask and sqlite3 Login Page
Creating a Login page using Python, Flask, and sqlite3 Database.

## How To Guide
### Pre-requisites
1. pip base installs
```
pip install virtualenv
pip install --upgrade pip
```
2. Setup a Python Virtual Environment
http://docs.python-guide.org/en/latest/dev/virtualenvs/
3. Install Flask
```
pip install Flask
```
4. Create Database
In a terminal, in the project folder, create the sqlite Database:
```
sqlite3 database.db < schema.sql
```
5. Execute the
```
pythnon main.py
```
## Issues
Works great, but found that refreshing the page inserts the last user again.
