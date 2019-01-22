# assignment07 (1.0 points)
### deadline: Tuesday, 1/22, 10 pm

[summary of the inclass assignment]

The first two phases of the inclass assignment is the same as the previous inclass assignment.

#### phase 1. obtain the java files from the repository
1. download the java files from the repository
   
   find your downloaded .zip file (**If it's in the lab machine, it should be in the ```downloads``` folder**)
   
![alt text](https://github.com/COSC111-2019Winter/assignments/blob/master/download.png "The download button in GitHub repo page")

2. right-click (in Mac, maybe ctrl-leftclick), and you will see unzip option (or ```uncompress``` option or ```extract all...```), click that option, and uncompress the ```assignment07-master.zip``` file.

3. after you uncompress the zip file, there should be a folder with all the java files. The folder name should be ```assignment07-master```.


#### phase 2. set up BlueJ project
4. create a BlueJ project; you can give any name to your project; and know where the project is in your file system, that is the actual folder in Windows/Mac (we did it in the last assignment).

5. in the BlueJ project window, close the project (by clicking the Project button in the menu bar and "close") and then **close** the BlueJ window

6. go to your folder (file system), find the folder that have all the java files (we did it in step 3), and copy the java files to the BlueJ project folder in your file system (not in BlueJ)

7. open BlueJ project again, and open the project if it's not opened (by clicking Project button in the menu and "open project", then find your BlueJ project folder, "click select folder"), you should see the new classes you just added.

#### phase 3. assignment tasks
8. **Task 1**: inside the main method in Main class, use **one** ```System.out.print``` (not ```System.out.println```) to print the following text:

![alt text](https://github.com/COSC111-2019Winter/assignments/blob/master/assignment07_01.PNG "The download button in GitHub repo page")

Please use escape sequences to print tabs, new lines, and double quotations to make your output exactly the same as the above picture.

9. **Task 2**: Exercise 2-3 in Chapter 2, Think Java. I *modified* this exercise to suit our class's progress.

The point of this exercise is to (1) use some of the arithmetic operators, and (2) start thinking about compound entities (like time of day) that are represented with multiple values.

(1) Create a new class in your BlueJ project, called ```Time.java```. Remove everything automatically-generated in the new ```.java``` file. Write your own ```Time``` class, just like the ```Hello``` class we did in the previous assignments.
(2) Following the example program in "Printing Variables" [section 2.4](http://greenteapress.com/thinkjava6/html/thinkjava6003.html#sec22), create variables named hour, minute, and second. Assign values that are 11:02:03, that is: hour is 11, minute is 2, and second is 3.
(3) Make the program calculate and display the number of seconds since midnight.

#### phase 4. upload the new ```.java``` files (keep the original filenames; do not change the filenames)
Upload the Time.java and Main.java you wrote in this assignment to this repository.
**ignore the .class files, we only need .java files**


---
### Grading
Each class (.java) worths 0.25 points. In total, it's 1.0 points.
If the format of ```.java``` file is different from the **auto-indent format** BlueJ producdes, the ```.java``` file will be rejected as a submission (i.e., point 0 unless you resubmit and will suffer late penalty.)

* convention 1: when a variable name contains more than one word, like firstName, capitalize the first letter of each word except the first.

---

That's it!

Siyuan
1/22/2019
