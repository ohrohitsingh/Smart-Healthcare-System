This is a project based on rural healthcare system. 
Rural Healthcare Management System
Making healthcare in rural areas more accessible.

Tech-Stack
Python
Flask
Database

Dataflow
Homepage --> Different Languages Implemented
|
|
Patient (Phone Number Login) - Phone Number is in the database - PATIENT PORTAL
|                                   |
|                                   |
|                                   SIGNUP PAGE
|
|
DOCTOR (Proper Login Page)
  - Name
  - Age
  - Speciality
  - Phone Number
  - License ID
  - Years of Experience
  - Location (Address)


Patient Portal
- Make an appointment 
  - Current problems that the patient is facing.
- Uploading Reports
- Patient History (Ask a bunch of Questions)
  - Blood Group
  - Diabetic History
  - etc.
  
Doctor's Portal
- Upcoming appointments 
  - Accept/Reject
- History of Patients

Setup
Download Python 3,

CD into the project directory.

Run python3 -m pip install venv

Now run python3 -m venv env

Now wait until it is done and if you are on windows type env/Scripts/activate

Now run python3 -m pip install -r requirements.txt

Then type set FLASK_APP="elaaj"

Then set FLASK_ENV="development"

Then flask run
