# airthmetricks
An airthmetricks prototype application to help facilitate and manage the results of math tests for elementary teachers. The app is created on node js platform using express framework. The data is stored in mysql db using sequelize ORM.Routing is established using express router. It provides basic authentication using passport js library.

#### Demo - https://airthmetricks.herokuapp.com/

#### Test Data 
##### Example Here
Teacher login - gupta123/tester123
Student login - kenny123/tester123

###### Data Creation Steps For Administrator. Need to do in sequence
- Add Teachers
- Add Classrooms 
- Add Students
- Add Tests

#### use cases for teacher
(A)
1. Login as a teacher
2. Add student to class 101

(B)
1. Login as a teacher
2. View grade level leader board
3. View class level leader board

#### use case for student
1. Login as a student (username/password) 
2. Click on Start button
3. Test begins, student answers questions one by one
4. - Once, all questions answered, result is submitted to DB and student is logged out automatically - DONE
     OR
  - Once, student runs out of time, result is submitted to DB and student is logged out automatically - Need to test this scenario
