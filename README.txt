Download and Extract the provided source code zip file. (download button is located below)

Open your Terminal/Command Prompt window. (make sure to add "python" and "pip" in your environment variables)

Change the working directory to the extracted source code folder. i.e. cd C:\Users\Personal-23\Desktop\Library_Management_Django_Project

Run the following commands:
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
Keep the terminals open and running.
Open a web browser and browse http://localhost:8000/ or http://127.0.0.1:8000/