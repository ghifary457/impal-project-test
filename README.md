# [Flask Pixel Lite](https://appseed.us/product/pixel-bootstrap/flask/)

`Open-Source` seed project generated by AppSeed in **Flask** Framework on top of **[Pixel Lite](https://appseed.us/product/pixel-bootstrap/flask/)** design. `Pixel` is a free and open-source `Bootstrap 5` based UI Kit featuring over 80 fully coded UI elements and example pages that will help you prototype and build a website for your next project.

- 👉 [Flask Pixel Lite](https://appseed.us/product/pixel-bootstrap/flask/) - product page
- 👉 [Flask Pixel Lite](https://flask-pixel-lite.appseed-srv1.com/) - LIVE Deployment
- ✅ Compatible with [LIVE Deployer](https://appseed.us/go-live/)
  - `Drag & drop` deployment service 
  
<br />

## [Black Friday 2022](https://appseed.us) - `75%OFF`

> The campaign is active until `30.NOV` and applies to all products and licenses.

[![AppSeed - Black Friday 2022 Campaign, 75% OFF Discount (all products).](https://user-images.githubusercontent.com/51070104/201829599-9fe6bdd7-3f19-46f3-9115-962eeb13bf29.jpg)](https://appseed.us)

<br />

> 🚀 Built with [App Generator](https://appseed.us/generator/), Timestamp: `2022-05-31 08:12`

- ✅ `Up-to-date dependencies`
- ✅ Database: `sqlite`
- ✅ `DB Tools`: SQLAlchemy ORM, Flask-Migrate (schema migrations)
- ✅ Session-Based authentication (via **flask_login**), Forms validation
- ✅ `Docker`

<br />

![Pixel Bootstrap Lite - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168753915-d61b2f97-57b2-4d14-a774-d217d120ff62.png)

<br /> 

## ✨ Start the app in `Docker`

> 👉 **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ git clone https://github.com/app-generator/flask-pixel.git
$ cd flask-pixel
```

<br />

> 👉 **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />  

## ✨ How to use it

> Download the code 

```bash
$ git clone https://github.com/app-generator/flask-pixel.git
$ cd flask-pixel
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Create Users

By default, the app redirects guest users to authenticate. In order to access the private pages, follow this set up: 

- Start the app via `flask run`
- Access the `registration` page and create a new user:
  - `http://127.0.0.1:5000/register`
- Access the `sign in` page and authenticate
  - `http://127.0.0.1:5000/login`

<br />

## ✨ Code-base structure

The project is coded using blueprints, app factory pattern, dual configuration profile (development and production) and an intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/
   |    |
   |    |-- home/                           # A simple app that serve HTML files
   |    |    |-- routes.py                  # Define app routes
   |    |
   |    |-- authentication/                 # Handles auth routes (login and register)
   |    |    |-- routes.py                  # Define authentication routes  
   |    |    |-- models.py                  # Defines models  
   |    |    |-- forms.py                   # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>          # CSS files, Javascripts files
   |    |
   |    |-- templates/                      # Templates used to render pages
   |    |    |-- includes/                  # HTML chunks and components
   |    |    |    |-- navigation.html       # Top menu component
   |    |    |    |-- sidebar.html          # Sidebar component
   |    |    |    |-- footer.html           # App Footer
   |    |    |    |-- scripts.html          # Scripts common to all pages
   |    |    |
   |    |    |-- layouts/                   # Master pages
   |    |    |    |-- base-fullscreen.html  # Used by Authentication pages
   |    |    |    |-- base.html             # Used by common pages
   |    |    |
   |    |    |-- accounts/                  # Authentication pages
   |    |    |    |-- login.html            # Login page
   |    |    |    |-- register.html         # Register page
   |    |    |
   |    |    |-- home/                      # UI Kit Pages
   |    |         |-- index.html            # Index page
   |    |         |-- 404-page.html         # 404 page
   |    |         |-- *.html                # All other pages
   |    |    
   |  config.py                             # Set up the app
   |    __init__.py                         # Initialize the app
   |
   |-- requirements.txt                     # App Dependencies
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- run.py                               # Start the app - WSGI gateway
   |
   |-- ************************************************************************
```

<br />

## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

**Pixel PRO** is a premium design crafted by the `Themesberg` agency on top of Bootstrap 5 Framework. **Pixel** is a premium `Bootstrap 5 UI Kit` that provides 1000+ components, 50+ sections and 35 example pages including a fully fledged user dashboard.

- 👉 [Flask Pixel PRO](https://appseed.us/product/pixel-bootstrap-pro/flask/) - product page
- 👉 [Flask Pixel PRO](https://flask-pixel-pro.appseed-srv1.com/) - LIVE Demo

<br >

![Pixel Bootstrap PRO - Full-Stack Starter generated by AppSeed](https://user-images.githubusercontent.com/51070104/168760719-f0e45406-2b2a-43e0-badf-fa953edb62b8.png)

<br />

---
[Flask Pixel Lite](https://appseed.us/product/pixel-bootstrap/flask/) - Open-source starter generated by **[App Generator](https://appseed.us/generator/)**.
