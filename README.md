# CS 4400 Phase 4

1. Clone or Download Repository.

2. Download the virtualenv package for creating virtual environment
```
pip install virtualenv
```
3. Create a virtual environment for the project
```
virtualenv venv
source venv/bin/activate
```
4. Install required python libraries given in the requirements.txt file.
```
cd 4400Phase4
pip install -r requirements.txt
```
5. Start the application.
```
python 4400Phase4.py
```
6. Input your SQL (user is assumed to be 'root' and db is 'travel_reservation_service').
7. Open a web browser and paste the url from the terminal given under the field "running on".
# Technologies
## Backend
1. Flask: a web framework used to create web applications
2. Flask Boostrap: for adding CSS to applications
3. Flask_WTF and WTForms: for creating forms in flask
4. pymysql: used to connect to a database in python, execute commands, and get query results

Usage: Using pymysql the phase 3 database was connected into the Flask app. In each of the screens, the corresponding procedure was called using connection established using pymysql and the cursor object of this connection. Data to be displayed on the screens was also obtained using cursor object of connection of pymysql.

## Frontend
1. HTML
2. CSS
3. Javascript and Jquery

HTML and CSS was used to create the. skeleton of each of the webpages. Javascript was used for data validation before form submit. Jquery was used to create sortable tables (using datatables), to add the autocomplete features in the text fields, and to send and receive ajax requests to enable smooth interaction between server and client side.

## Contributions
1. Dewang Agarwal: Completed full-stack development of Screens 1-14 and conducted dynamic testing of the completed web-app.
2. Shashank Singhania: Completed full-stack development of Screens 15-20 and set-up of the Flask Application.
3. Hemang Dash: Completed full-stack development of Screens 21-24.
4. Amrit Iyer: Conducted sample testing of the completed web-app.
