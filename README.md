# Smart Attendance-system using Facial Recognition
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

### **To run this project,**

1) Clone this repository

```git clone https://github.com/Ratheshprabakar/Attendance-system```

2) Create the virtual environment

3) Install the requirements in the virtual environment

```pip install requirements.txt```

4) Change the directory to the admin_site and run the application 

```python app.py```

5) Change the directory to the teachers_site and run the application

``` python app.py```


## Output


**Student Addition**

![image](https://user-images.githubusercontent.com/37381228/113325510-2e587c00-9336-11eb-847d-a4d567d38fe7.png)


**Faculty Dashboard**

![image](https://user-images.githubusercontent.com/37381228/113325570-44fed300-9336-11eb-81e5-9ee587dcf207.png)


**Marking Attendance**

![Screenshot (58)](https://user-images.githubusercontent.com/37381228/113324942-572c4180-9335-11eb-98fe-b0242ae626f5.png)


![Screenshot (59)](https://user-images.githubusercontent.com/37381228/113324968-5f847c80-9335-11eb-9dc2-a531da3c1b07.png)


**Report Panel**

![image](https://user-images.githubusercontent.com/37381228/113325647-5811a300-9336-11eb-8862-33a239fd38c4.png)


**Consolidated Report**

![Screenshot (63)](https://user-images.githubusercontent.com/37381228/113324988-68754e00-9335-11eb-8c13-b726498accda.png)



> 
[Documentation Live Link](https://issuu.com/ratheshprabakar/docs/final_documentation__version_2.0_)

