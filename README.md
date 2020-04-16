Step 1: Lichess OAuth App
-----------------------

Go here: https://lichess.org/account/oauth/app

Make an app, the homepage url is: http://127.0.0.1:5000/ the callback url is: http://127.0.0.1:5000/authorize

Step 2: Make .env file
----------------------
make a `.env` file with the following contents:

```
LICHESS_CLIENT_ID="{ lichess client id }"
LICHESS_CLIENT_SECRET="{ lichess client secret }"
SECRET_KEY="{ secure random key for flask sessions }"
```

Step 3: Run the App
-------------------
run the app:
```
python app.py
```

Step 4: Load the url
--------------------
Load this url in your browser:
http://127.0.0.1:5000/


Step 5: ???
-----------
???

Step 6: profit
--------------
Profit

