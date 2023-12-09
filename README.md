# Workout-Recommendation-Using-Content-Based-Filtering-Algorithm
<h2>This project is made using Python, Streamlit and Python Notebook. 
<br>The workout videos are recommended using Content Based Filtering Algorithm. 
  <br>The user can select any title within the given dataset and the workouts will be recommended according to it.</h2>

<h3>The steps to implement the Content Based Filtering Algorithm are:</h3>
1. Create a table under a database to store all the values of the required entities, such as 'title', 'description, 'video_path', etc.<br>
2. Host the videos on any cloud or store it in your local drive. Set the path of the videos or any other files accordingly.<br>
3. Export .CSV file from the required table.<br>
4. Use any python notebook in order to implement the algorithm (Eg: Kaggle, Jupyter).<br>
5. Make sure to have the .CSV file on the same directory as your notebook in order to read the .CSV file through the notebook.<br>
6. Implement the Algorithm as shown in 'recommender-system.ipnyb'.<br>
7. Export the .pkl files using 'pickle.dump.'<br>

<br><br>
<h3>Creatiing the user interface using Python and Streamlit:</h3>
1. Create a sjango project.<br>
2. Create a virtual environment (say: new_venv).<br>
3. Create a python file 'workout.py'.<br>
4. Import all the necessary libraries like streamlit, etc.<br>
5, Install the necessary libraries (Eg: pip install streamlit).<br>
6. Import the .CSV file and .pkl file. Make sure to keep it in the same directory within the 'workout.py'.<br>
7. Activate the virtual environment (new_venv\Scripts\Activate).<br>
8. Run the python file (streamlit run workout.py).<br>
<br>
<h3>The project should run now.</h3>
