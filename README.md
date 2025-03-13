# END-TO-END-BostonHousePricing

## Steps:

### Software and tools requriement
    - github
    - VS code IDE
    - Heroku account/Render
    - Git CLI
### Create a new env for project
    - conda create -p venv python==3.7 -y


### Note: try to deploy on heroku.

### Process:
- Write a pickle file 'regmodel.pkl'
- Import the pickle file in 'app.py'
- Get imput data from app.py
- Show result by `flask run`


### app.py code explanation:
- import libraries.
- ` app=Flask(__name__)`
- load regmodel and scalar
- routes to imput data and output data.


### Video Demo:
