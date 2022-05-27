<h1 align="center">Face_Recognition_Attendance_System
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Microsoft_logo.svg/480px-Microsoft_logo.svg.png" alt="Logo" width="25" height="25">
</h1>

<p align="center">
 <a target="_blank" href="https://drive.google.com/file/d/1SlxT2vWntjKAhiEyiHitDtI7gr1OgDVj/view?usp=sharing">Link to the Executable Application File</a>
  
  ## About The Project
  Recognize and manipulate faces from Python or from the command line with the  face recognition library.It recognize faces and take automatic attendance.
  Built using dlib's state-of-the-art face recognition built with deep learning. For Graphical User Interface Pyqt is used.
  
  
  ## Features :clipboard:
------------------------------
* Check Camera
* Capture Faces
* Train Faces
* Recognize Faces & Attendance
* Store Data on My Sql Database and in form of CSV file
  
  ## Screenshots :camera:
  ---------------------------------------
  * Main Window 
  
  
  <img width="264" alt="image" src="https://user-images.githubusercontent.com/87435764/170625882-7035d59b-344b-4b4a-adb2-6acd2276607b.png">
  
  * If we click on Start-
  
<img width="480" alt="image" src="https://user-images.githubusercontent.com/87435764/170626255-2fbbeb77-fea4-4e49-adf5-fea8544a8c16.png">
<img width="473" alt="image" src="https://user-images.githubusercontent.com/87435764/170626360-a421d55c-249b-4bae-865e-4061599a7023.png">
<img width="143" alt="image" src="https://user-images.githubusercontent.com/87435764/170626463-8d087694-9231-4db3-a20c-395c0e42c5b2.png">
  
  * If we click on Database records will be shown to us in form of CSV file
  <img width="362" alt="image" src="https://user-images.githubusercontent.com/87435764/170626562-7c37319c-6da1-47b9-ac03-7ad2d0eb1c91.png">
  
  * Records in  MySql Database
<img width="299" alt="image" src="https://user-images.githubusercontent.com/87435764/170626686-3f59cd14-9a38-4546-8486-7f85f6606622.png">


  
  ## Tech Used :computer:
  -------------------------------------
  Build With - 
* Python 3.10.4
 
  Module Used -

  All The Module are Latest Version.
* ```pip install cmake```
* ```pip install dlib```
* ```pip install face_recognition```
* ```pip install panda```
* ```pip install numpy ```
* ```pip install csv```
*  ```pip install mysql_connector```
*  ```pip install opencv-contrib-python```

  Software Used -
* Pyqt5
* VS CODE 
* Git
  
  ## Connecting with Database
  ---------------------------------------------------
* Install MySql with user='root',Password='Divya@123'
*  Create Database named 'attendance'
*  Create table named 'students' having columns Name,Time,status,Date
  
  
  <img width="324" alt="image" src="https://user-images.githubusercontent.com/87435764/170624572-5b8e51e7-26b2-4075-a259-7c72764399e6.png">
  
  ## Add new faces
  -----------------------------------------------------------
   You can add new faces for decoding in ImagesAttendance folder.
  
  ##  Having Problems??
  ---------------------------------------
  If you face any problem using provided executable application file then you can also clone the source code and using pyinstaller can create your own executable file.
  
  To install pyinstaller
 * ```pip install pyinstaller``` 
 
  If you face any issues in making exe refer this - https://github.com/ageitgey/face_recognition/issues/357
  
  
## How Face Recognition Works

If you want to learn how face location and recognition work instead of
depending on a black box library, [read my article](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78).
