# FaceTime Attendence
The inspiration behind FaceTime Attendance stems from the need for an efficient and accurate attendance system that leverages modern technology. Traditional attendance methods are prone to errors and time-consuming. We envisioned a solution that seamlessly integrates computer vision and real-time data management to streamline this process, making it quicker, more accurate, and user-friendly.

## Setup

### STEP 1: Create a virtual environment
- python3 -m venv myenv
- source myenv/bin/activate

### STEP 2: Install all the required packages
- pip install -r requirements.txt

### STEP 3: Database Setup
- Create an account/login on Firebase
- Create a database with your desired name
- Create a Realtime Database and Storage Database
- Get the URL and paste it in main.py file, AddDataToDatabase.py file and EncodeGenerator.py file
- From Project Settings, get the json file of Service Account key
- Keep it in a file named "serviceAccountKey.json"
- Run the command: "python AddDataToDatabase.py", this will add the data to the database
- Then run the command: "python EncodeGenerator.py", this will add the data to the storage
- Finally run the command "python main.py"
- The project should be runnning now
