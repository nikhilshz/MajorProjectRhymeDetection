# Rhyme Detection

## Backend Setup
1. Start by navigating to the backend server directory: `cd server`
2. Create a virtual environment: `virtualenv venv`
3. Activate the virtual environment: `source ./venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Set Flask app and environment variables:
    ```
    export FLASK_APP=server
    export FLASK_ENV=development
    ```
6. Start the Flask server: `flask run`

## Frontend Setup
1. Navigate to the frontend directory: `cd app`
2. Install dependencies: `pnpm install`
3. Start the server: `pnpm dev`
4. Access the server at [http://localhost:3000/](http://localhost:3000/).
