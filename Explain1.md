
# For my dear students..
💜, 🌸

# How to prepare my system to start development with laravel framework ?
1. [download composer](https://getcomposer.org/)
2. [download xampp](https://www.apachefriends.org/download.html)

# How to create a new laravel project ? 
It's easy to create and initialize new laravel project, just follow these simple steps down below
1. make a new folder, name it as you like (e.g: ```programmer-univers```)
2. open Command line (or CMD) 
3. in cmd, type ```cd c:\programmer-univers``` and hit enter. **note that you need to specify the correct path**
4. in cmd, type ```composer create-project laravel/laravel [your-project-name-here]```
5. in cmd, type ```code .```


# How to prepare laravel project ?
Now that we've created our new laravel project and opened the visual studio code into it
We are ready for the next few steps to prepare laravel project.
#### 1. from VS code, open file .env
    We need to modify this file sense it comes missing some properties
#### 2. inside .env file you need to replace/insert the next few lines:
    - SESSION_LIFETIME=1440 
    - SESSION_DOMAIN="localhost" 
    - SESSION_SECURE_COOKIE=false 
#### 3. for you database system
    - DB_CONNECTION=mysql 
    - DB_HOST=127.0.0.1 
    - DB_PORT=3306   
    - DB_DATABASE=database-name 
    - DB_USERNAME=root 
    - DB_PASSWORD=root

And now we ready for some real programming 💪
