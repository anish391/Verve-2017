# Verve-2017
A website for Vidyalankar Institute of Technology's cultural festival Verve 2017. Capable of dynamically loading event cells from database. Allows user registration for the events of the festival.

### Getting Started:
1. Get [XAMPP](https://www.apachefriends.org/index.html).
2. Once the XAMPP Control Panel is open, start the Apache and MySQL services.
3. Open [PHPMyAdmin](http://localhost/phpmyadmin/).
4. Select the Database section and create a Database named "_verve_".
5. Select the Import section and upload the file "_verve.sql_". You will see the tables populated.
6. Download and store the project in a convenient location (C:\xampp\htdocs\Verve-2017-master).
7. You can now access the website at http://localhost/Verve-2017-master/.

### What works:
* Dynamic Event Cells:<br>
  Loads event cells dynamically based on database entries in the database table "_event_". Event information is displayed in modal boxes.
* Event Registration:<br>
  Allows users to register for events. Stores details such as event name, participating user, the user's college/university and contact     number.

### What doesn't work:
* Requires manual entry of events to the database. No Admin page for event entry.
* Payment for events not set-up.

## Home Page
![alt text](https://github.com/anish391/Verve-2017/blob/master/screenshots/HomePage1.PNG)
![alt text](https://github.com/anish391/Verve-2017/blob/master/screenshots/HomePage2.png)
## Event Registration Page
![alt text](https://github.com/anish391/Verve-2017/blob/master/screenshots/EventRegistration.PNG)
## Event Information
![alt text](https://github.com/anish391/Verve-2017/blob/master/screenshots/Event%20Information%20Popup.PNG)
## Acknowledgements

![alt text](https://github.com/anish391/Verve-2017/blob/master/screenshots/Acknowledgements.PNG)
Adopted from [Oxygen One Page Templates](https://demo.themeum.com/html/oxygen/)
