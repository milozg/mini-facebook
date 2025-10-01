# mini-facebook WebApp

mini‑facebook is a lightweight demonstration project, designed to showcase the core features one might expect in a Facebook‑style social site. It is not intended as production software, but rather as a learning tool or prototype.  

---

![mini_facebook_gif](https://github.com/user-attachments/assets/a595e80e-196e-428a-bd3a-c1e5d8456dd4)


---

## Features

- User registration, login, logout supported by Django's built in authorization  
- Profile pages  
- Creating and editing posts
- Viewing posts in a feed
- Following / unfollowing users

---

## Tech Stack

- **Backend / Web Framework**: Django
- **Database**: SQLite
- **Frontend / Static files**: HTML, CSS 

---

## Setup

If you wish, below are the typical steps to get this project running locally:

- Fork and clone the repository
- Now create a virtual environment
  ```bash
  pipenv shell
  ```
- And run the local server
  ```
  python manage.py runserver
  ```
- Go to http://127.0.0.1:8000/ and use the app!
