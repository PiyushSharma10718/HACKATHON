Creating the Virtual Environment :- python3 -m venv env // (python||python3)
Entering in the Virtual Environment :- env/Scripts/Activate
Inside the Virtual Environment :
    -> pip install fastapi uvicorn sqlalchemy

to run our fast-api-app :
    -> cd fastapi-api-app
    -> uvicorn main:app --reload

FOR REACT APP -->
Now we are going to use the second terminal in the vs code paralleling Because the React application will be running on the different Port !
1st Terminal for the FastAPI App !
2nd Terminal for the React App !

React app -->
    -> cd react-app
    -> npx create-react-app rohini-app
    -> npm i axios
