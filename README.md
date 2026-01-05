# Hospital Management System
Hospital Management System using MySQL, Php and Bootstrap


## Prerequisites
1. Install XAMPP web server
2. Any Editor (Preferably VS Code or Sublime Text)
3. Any web browser with latest version

## Languages and Technologies used
1. HTML5/CSS3
2. JavaScript (to create dynamically updating content)
3. Bootstrap (An HTML, CSS, and JS library)
4. XAMPP (A web server by Apache Friends)
5. Php
6. MySQL (An RDBMS that uses SQL)
7. TCPDF (to generate PDFs)

## Steps to run the project in your machine
1. Download and install XAMPP in your machine
2. Clone or download the repository
3. Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.
4. Start the Apache and Mysql in your XAMPP control panel.
5. Open your web browser and type 'localhost/phpmyadmin'
6. In phpmyadmin page, create a new database from the left panel and name it as 'myhmsdb'
7. Import the file 'myhmsdb.sql' inside your newly created database and click ok.
8. Open a new tab and type 'localhost/foldername' in the url of your browser
9. Hurray! That's it!
    


### Starting Apache And MySQL in XAMPP:
  The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To start Apache or MySQL manually, click the ‘Start’ button under ‘Actions’.
  
  
<p align="center"><img src="https://user-images.githubusercontent.com/36665975/59350977-fcc68900-8d3a-11e9-9450-e5c478497caa.png"></img></p>

## GETTING INTO THE PROJECT:
Hospital Management System in php and mysql. This system has a ‘Home’ page from where the patient, doctor & administrator can login into their accounts by toggling the tabs accordingly.shows the ‘Home’ page of our project.

![image](https://user-images.githubusercontent.com/36665975/66569676-ad2d8800-eb89-11e9-94e5-ea407622a1fe.png)

'About Us' page allows us to get some more information about the quality and the services of the hospital.

![image](https://user-images.githubusercontent.com/36665975/66569816-f4b41400-eb89-11e9-9377-d9ce53ded088.png)

‘Contact’ page allows users to provide feedback or queries about the services of the hospital.shows the ‘Contact’ page.

![image](https://user-images.githubusercontent.com/36665975/66569890-157c6980-eb8a-11e9-9b2f-c0e8a6ef702e.png)

The ‘Home’ page consists of 3 modules:
1. Patient Module
2. Doctor Module
3. Admin Module

### Patient Module:

  &nbsp; &nbsp; &nbsp; This module allows patients to create their account, book an appointment to see a doctor and see their appointment history.
  The registration page(in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.
  
  ![image](https://user-images.githubusercontent.com/36665975/66570027-5b393200-eb8a-11e9-9e97-088630b5e583.png)

Once the patient has created his/her own account after clicking the ‘Register’ button, then he will be redirected to his/her Dashboard.

![image](https://user-images.githubusercontent.com/36665975/66570123-8c196700-eb8a-11e9-845f-ea02013f1d5c.png)

The Dashboard page allows patients to perform two operations:

**1. Book appointment:**

  &nbsp; &nbsp; &nbsp; Here, the patients can able to book their appointments to see a doctor. The appointment form requires patients to select the doctor that they want to see, Date and Time that they want to meet with the doctor. The consultancy fee will be shown accordingly to the patient as it was already determined by the doctor.

![image](https://user-images.githubusercontent.com/36665975/66570202-c256e680-eb8a-11e9-8839-6c7fef68ac4c.png)

After clicking on the ‘Create new entry’ button, the patient will receive an alert that acknowledges the successful appointment of the patient. 

![image](https://user-images.githubusercontent.com/36665975/66570280-ec100d80-eb8a-11e9-96c2-08e5441954d0.png)

**2. View patients’ Appointment History:**

  &nbsp; &nbsp; &nbsp; Here, the patient can see their appointment history which contains Doctor Name, Consultancy Fee, Appointment Date and Time.
	
![image](https://user-images.githubusercontent.com/36665975/66570349-0ea22680-eb8b-11e9-94fe-22a86070a274.png)

Once the patient has logged out of his account, if he wants to go into his account again, he can login his account, instead of register his account again. shows the login page.
Clicking on ‘Login’ button will redirect the patient to his dashboard page which we have seen earlier 

![image](https://user-images.githubusercontent.com/36665975/66570502-588b0c80-eb8b-11e9-88e3-5294ae896ace.png)

This is how the patient module works. On the whole, this module allows patients to register their account or login their account(if he/she has one), book an appointment and view his/her appointment history.

### Doctor Module:

  &nbsp; &nbsp; &nbsp; The doctors can login into their account which can be done by toggling the tab from ‘Patient’ to ‘Doctor’.shows the login form for a doctor. Registration of a doctor account can be done only by admin. We will discuss more about this in Admin Module.
  
![image](https://user-images.githubusercontent.com/36665975/66570609-8bcd9b80-eb8b-11e9-8099-9f285aa7fe0f.png)

Once the doctor clicking the ‘Login’ button, they will be redirected to their own dashboard

![image](https://user-images.githubusercontent.com/36665975/66570642-a0119880-eb8b-11e9-8d23-be898e1bfa29.png)

In this page, doctor can able to see their appointments which has been booked by the patients. shows the appointment of the doctor ‘Ganesh’ which has been booked by the patient ‘Kenny Sebastian’ (Fig 1.6). This means that the doctor ‘Ganesh’ will have an appointment with the patient ‘Kenny Sebastian’ on 10-10-2019 10AM. 

![image](https://user-images.githubusercontent.com/36665975/66570704-be779400-eb8b-11e9-92ae-21d8e0e4aba4.png)

In real-time, the doctors will have thousands of appointments. It will be easier for a doctor to search for appointment in the case of more appointments. To make it easier, I have a ‘Search’ box in the navigation bar which allows doctors to search for a patient by their contact number.
&nbsp; &nbsp; &nbsp; Once everything is done, the doctor can logout of their account. Thus, in general, a doctor can login into his/her account, view their appointments and search for a patient. This is all about Doctor Module.

### Admin Module:
   
   &nbsp; &nbsp; &nbsp; This module is the heart of our project where an admin can see the list of all patients. Doctors and appointments and the feedback/queries received from the ‘Contact’ page. Also admin can add doctor too. 
  &nbsp; &nbsp; &nbsp; Login into admin account can be done by toggling into admin tab of the Home page.shows the login page for admin.
  &nbsp; &nbsp; &nbsp; `username`: admin, `password`: admin123

![image](https://user-images.githubusercontent.com/36665975/66570795-e961e800-eb8b-11e9-94e2-79940ff1d45e.png)

On clicking the ‘Login’ button, the admin will be redirected to his/her dashboard 


![image](https://user-images.githubusercontent.com/36665975/66570841-03032f80-eb8c-11e9-9cfc-62b6b869c918.png)

This module allows admin to perform five major operations:

**1. View the list of all patients registered:**

  &nbsp; &nbsp; &nbsp; Admin can able to view all the patients registered. This includes the patients’ First Name, Last Name, Email ID, Contact Number and Password.As like in doctor module, admin can also search for a patient by their contact number in the search box.
  
  ![image](https://user-images.githubusercontent.com/36665975/66571179-83c22b80-eb8c-11e9-8819-008cdd2b0c2e.png)
  
**2. View the list of all doctors registered:**

  &nbsp; &nbsp; &nbsp; Details of the doctors can also be viewed by the admin. This details include the Name of the doctor, Password, Email and Consultancy fees. Searching for a doctor can be done by using the doctor’s Email ID in the search box.

![image](https://user-images.githubusercontent.com/36665975/66571329-a5bbae00-eb8c-11e9-89be-ce1a9c73e01b.png)

**3. View the Appointment lists:**

  &nbsp; &nbsp; &nbsp; Admin can also able to see the entire details of the appointment that shows the appointment details of the patients with their respective doctors. This includes the First Name, Last Name, Email and Contact Number of patients, doctor’s name, Appointment Date, Time and the Consultancy Fees. 
  
  ![image](https://user-images.githubusercontent.com/36665975/66571377-c3891300-eb8c-11e9-92d2-6755204564c7.png)
  
**4. Add Doctor:**

  &nbsp; &nbsp; &nbsp; Admin alone can add a new doctor since anyone can register as a doctor if we put this section on the home page. This form asks Doctor’s Name, Email ID, Password and his/her Consultancy Fees. 
  
  ![image](https://user-images.githubusercontent.com/36665975/66571687-55911b80-eb8d-11e9-9859-54e15d4ad8a0.png)
  
  After adding a new doctor, if we check the doctor’s list, we will see the details of new doctor is added to the list 
  
  ![image](https://user-images.githubusercontent.com/36665975/66571496-03e89100-eb8d-11e9-954e-7e3704bd0ca3.png)
  
**5. View User’s feedback/Queries:**

  &nbsp; &nbsp; &nbsp; Admin is allowed to view the feedback/Query that has been given by the user in the ‘Contact’ page (Refer Fig 1.3). This includes User’s Name, Email Id, Contact Number and the message(Feedback/ Query)
  
  ![image](https://user-images.githubusercontent.com/36665975/66571573-27134080-eb8d-11e9-8c1f-191a9f491872.png)
  
  &nbsp; &nbsp; &nbsp; Taking everything into consideration, admin can able to view the details of patients and doctors, appointment details, Feedback by the user and can add a new doctor. Once everything is done, the admin can logout from his account.



  




