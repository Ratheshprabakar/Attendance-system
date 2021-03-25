# Attendance-system
To decrease the burden of taking the manual attendance everytime, I am working on the project of smart attendance system (i.e)Automating the attendance process using facial recognition.


## Admin authorization : 
![img](https://github.com/Ratheshprabakar/Attendance-system/blob/master/OTHERS/REVIEW_PPT/admin.png)
   - Admin can register the 
     - Faculty Addition
     - Add the faculty details and store it in the database.
     - Student Addition
     - Create training data of each student by entering his roll id and taking snaps of his or her frontal face.
     - Create model for that particular roll id and save it on Database.

## Teacher authorization
![img](https://github.com/Ratheshprabakar/Attendance-system/blob/master/OTHERS/REVIEW_PPT/teachers_site.png)
   - Teacher has to login first
   - Attendance tab
     - Snap is taken and it is sent to our model. 
     - Select mark their attendance.
     - Report tab
     - Select by date and time, roll id.
     - View the absent hours of any particular student.
     - Report generation in Excel format.
     - Editable and can be able to add ON DUTY.
   - Alert tab
      - Send email to the students and parents regarding their attendance.
      - Email alert using flask_mail.

To run this project,
1) Clone this repository

```git clone https://github.com/Ratheshprabakar/Attendance-system```

2) Create the virtual environment

3) Install the requirements in the virtual environment

```pip install requirements.txt```

4) Change the directory to the admin_site and run the application 

```python app.py```

5) Change the directory to the teachers_site and run the application

``` python app.py```


[Documentation Live Link](https://issuu.com/ratheshprabakar/docs/final_documentation__version_2.0_)
