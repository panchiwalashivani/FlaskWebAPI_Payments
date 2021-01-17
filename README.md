# FlaskWebAPI_Payments

### How to run the project
Have `pipenv` installed in your system

run the following command to do so.

   1.   cd `filed_payments`
   2. run command `pipenv install`
   3. run to go in virtual environment, inside the project run command `pipenv shell`
   4. run command to run the flask server `flask run`
   5. To exit server run `ctrl+c`
   6. To exit the virtual env run command in terminal `deactivate`
   
   
   ## How to test the application
 
   1. run the server first using above step
   2. in seperate terminal, run `cd application/test` ie go to test folder
   3. run comands: `pytest test_external_payment.py`
