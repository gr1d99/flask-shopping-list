[![Coverage Status](https://coveralls.io/repos/github/gr1d99/shopping-list/badge.svg?branch=challenge-2)](https://coveralls.io/github/gr1d99/shopping-list?branch=challenge-2) [![Build Status](https://travis-ci.org/gr1d99/shopping-list.svg?branch=challenge-2)](https://travis-ci.org/gr1d99/shopping-list) [![Code Climate](https://codeclimate.com/github/gr1d99/shopping-list/badges/gpa.svg)](https://codeclimate.com/github/gr1d99/shopping-list) [![Issue Count](https://codeclimate.com/github/gr1d99/shopping-list/badges/issue_count.svg)](https://codeclimate.com/github/gr1d99/shopping-list) [![Test Coverage](https://codeclimate.com/github/gr1d99/shopping-list/badges/coverage.svg)](https://codeclimate.com/github/gr1d99/shopping-list/coverage)

# shopping-list

Is a flask powered web application that allows users to keep track of their shopping items and also allows a user to 
share the shopping lists with others.

## Usage
> 1. Clone this repo `git clone https://github.com/gr1d99/shopping-list.git`
> 2. Change your current directory to `shopping-list`
> 3. On your terminal type `git checkout challenge-2`
> 4. Create a virtual enviroment `virtualenv --python=python3 env` then activate it `source env/bin/activate`
> 5. Install requirements `pip3 install -r requirements.txt`
> 6. Generate your SECRET_KEY by running `python manage.py generate_secret`, the command will generate an **`secret.ini`** file that will contain the apps secret key, 
> after running the command, add `app.secret_key = config['SECRET_KEY']['KEY']` in the **`main.py`** file.
> such that it looks likes
> ```python
>    # app conf
>    app.secret_key = config['SECRET_KEY']['KEY']
>    
>   
>    if __name__ == '__main__':
>        app.run()
>
>```
> after making the changes save your file. **DEBUG** is set to `True` but you may change it.
> 7. Finally deploy your web app by running the command `python manage.py runserver` 
>  The app does not have much functionality. What you can do for now is
> > - Register
> > - Login
> > - add create a shopping list through the dashboard.
> > - view created shopping list by clicking on the view button.
> > - delete created shopping lists
> > - view created shopping list at the home page


**NB:** This application has no database yet!.

Screenshots
===========
>## Home Page
>![Home Page](https://github.com/gr1d99/shopping-list/blob/challenge-1/screenshots/homepage.png)

>## Dashboard
>![Dashboard](https://github.com/gr1d99/shopping-list/blob/challenge-1/screenshots/dashboard.png)

>## Sign in
>![Sign in](https://github.com/gr1d99/shopping-list/blob/challenge-1/screenshots/signin.png)

