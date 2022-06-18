# E-commerce


This is an e-commerce app built with React and Django that allows the user to create an account, log in, and add/remove items to/from the cart. Once the user has selected the items they wish to purchase they are shown a total of their expenses and are able to utilize PayPal to pay for their items. They are then able to view their profile for a summary of their purchases and are able to see the paid and delivery status of their purchases. There are also some actions available to users that have admin privileges related to changing user information and deleting users. 


<h3>Commands required to run this app: </h3>

*Note: These CLI commands require Python and Node.Js*

### `Python environment and dependencies`

<ul>
  <li>Create a python virtual environment (venv) </li>
  <li>Activate the virtual environment and navigate to the main project folder </li>
  <li>Pip install "requirements.txt" for the dependencies necessary for this project </li>
</ul>

    pip install -r requirements.txt
    
<h4> Run the backend server </h4>
<ul>
  <li>Navigate to the backend folder (folder with manage.py) </li>
  <li>Run the following command</li>
</ul>

    python manage.py runserver

### `Frontend`

<h4> Run the frontend server </h4>
<ul>
  <li>Navigate to the frontend folder</li>
  <li>Use the following commands</li>
</ul>

    npm install
    npm start

### `Open the app`
Finally, with both servers running, open the following url to use the app!
    
    localhost:3000


### `Admin login (optional)`

<ul>
  <li> Admin functionality is available if desired</li>
  <li> You will need to create an admin user</li>
  <li> Navigate to backend and use the following command</li>
</ul>

    python manage.py createsuperuser
    
  then paste the following in your browser and login
  
    localhost:8000/admin


