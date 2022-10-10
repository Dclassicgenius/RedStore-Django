# RedStore-Django

This is an e-comerce website. The user interface was developed usin HTML, CSS and JS and python and django framework was used for the server side 


## Installation and Setup

1. Download or clone the app and open the folder in the cli
2. Create a virtual environment using: 


```bash
  python<version> -m venv <virtual-environment-name>
```
3. Activate virtual environment using:
* for Mac 
 ```bash
  source env/bin/activate
```
* for windows
```bash
  env/Scripts/activate.bat //In CMD
  env/Scripts/Activate.ps1 //In Powershel
```
4. Once the virtual environment is activated, install dependencies using `pip`:
```python
  pip install -r requirements.txt
```
5. Create a `.env` file using the `.env.example` file to fill out the required environment variables.
6. Start the web server using `python manage.py runserver` command. The app will be served at http://localhost:8000/
7. Go to http://localhost:8000/ in your browser to use the app.

## Features
- Store 
  - every available product in the store is displayed here with the name rating and price.
  - On clicking each product, a brief description of the product is shown as well as the size and colour variations. The user can then add the item to cart from here
  - A user will need to register to be able to proceed to checkout.

- Checkout
  - User can enter their billing addres and information, view and confirm their orders.

- User
  - The user can view products in store, place and track orders, view order history and edit their information.
  
- Admin
  - Create new user and products
  - Update user information and products
  - Delete products



## Demo

![Development environment](https://github.com/Dclassicgenius/RedStore-Django/blob/master/screenshots/Screenshot%202022-10-10%20at%2015.11.13.png)
![Development environment](https://github.com/Dclassicgenius/RedStore-Django/blob/master/screenshots/Screenshot%202022-10-10%20at%2015.11.40.png)
![Development environment](https://github.com/Dclassicgenius/RedStore-Django/blob/master/screenshots/Screenshot%202022-10-10%20at%2015.12.34.png)
![Development environment](https://github.com/Dclassicgenius/RedStore-Django/blob/master/screenshots/Screenshot%202022-10-10%20at%2015.33.35.png)
![Development environment](https://github.com/Dclassicgenius/RedStore-Django/blob/master/screenshots/Screenshot%202022-10-10%20at%2015.13.58.png)


