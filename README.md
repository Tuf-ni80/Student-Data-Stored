# Student-Data-Stored
introduction: this project simply manage the student data. it has 5 option<br>
1.Accept Student<br>
2. Display Students<br>
3. Search Student<br>
4. Update Student<br>
5. Delete Student<br>
first we create a class for return a object that store the student data<br>
<br>![242795496-f0955274-a790-424b-8d35-02ea8c6207ff](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/a59920b6-c956-4752-9484-513fb978892a)<br>
then make a function load data to load data from file for example if we open program day 2 then it load day 1 data also "load_students()" to save data we make a funcion save_students(students) here students is a array that store data object.

# requirments
1. module tabulate:- to install tabulate use 'pip install tabulate' and import tabulate as 'from tabulate import tabulate' this module is use to print data in tabular formate like <br>
![Screenshot 2023-06-17 110134](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/7fb2951a-3cb1-4b1f-ba25-fc91bfa9828f)<br>
2. students.txt file:- create a students.txt file to store the data taken by admin from students.

# output
![Screenshot 2023-06-17 115930](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/44c2ec48-4507-497d-9034-c7b3a178c5cf)<br>
when select 1 option<br>
![Screenshot 2023-06-17 110426](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/6623e733-58cc-4ead-9550-6374f28e92f0)<br>
when selcect 2<br>
![Screenshot 2023-06-17 110454](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/0dc8c5ec-0e73-448d-9d43-a5d402612d56)<br>
this will print all the records persent in students.txt file<br>
Now select option 3<br>
![Screenshot 2023-06-17 110520](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/367aa843-f9c4-46be-b2ff-33809c6f6308)<br>
this option call search function that take one argument roll number to search student by roll number cause roll number is unique for every student
now select option 4 this option is for update records<br>
![Screenshot 2023-06-17 115915](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/aabf7d42-5614-41f7-9b6a-2a3d35537d65)<br>
records before updation<br>
![Screenshot 2023-06-17 110708](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/23134899-9549-48ab-a09d-f9cc9b38dbe2)<br>
after updation<br>
![Screenshot 2023-06-17 110956](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/4378b208-58bd-48d7-b1ed-0a527d230df9)<br>
option 5 is use to remve data from the records for example let roll number 4 is leave the school and we want to remove the records of that students then<br>
![Screenshot 2023-06-17 111020](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/4674540b-23d0-492a-b7d1-32abcba27a4e)<br>
Now new data records is<br>
![Screenshot 2023-06-17 111032](https://github.com/Tuf-ni80/Student-Data-Stored/assets/111050945/c45c0e5b-4d32-4317-a116-f9e976131724)
