## Features of Hospital Single Linked List
1. Patient Management

  a. Add a Patient: store patient details (ID, name, age, gender, disease).<br/>
  <br>b. Remove a Patient: delete a patient by ID and update the assigned room’s capacity.<br/>
  <br>c. Find Patient by ID: search for a specific patient.<br/>
  <br>d. Display All Patients: show details of every patient, including their assigned room and doctor.<br/>

2. Doctor Management

  a. Add a Doctor: store doctor details (ID, name, specialty)<br/>
  <br>b. Find Doctor by ID: search for a specific doctor and display their details plus rooms.<br/>
  <br>c. Display All Doctors: show all doctors and their associated rooms.<br/>

3. Room Management

  a. Add Room under a Doctor: link a new room (room number, max capacity) to a doctor.<br/>
  <br>b. Assign Room to Patient: assign an available room to a patient, checking capacity.<br/>
  <br>c. Room Availability Check: ensures no duplicate room numbers and checks if a room is full.<br/>

4. Data Linking

  a. Each patient can be assigned to a room.<br/>
  <br>b. Each room belongs to a doctor.<br/>
  <br>c. From a patient, you can trace which room they are in and which doctor oversees it.<br/>

5. Menu-driven Console Interface (from main.cpp)

The system provides a menu with these options:

  a. Add Patient<br/>
  <br>b. Add Doctor<br/>
  <br>c. Add Room to Doctor<br/>
  <br>d. Assign Room to Patient<br/>
  <br>e. Remove Patient<br/>
  <br>f. Display All Doctors<br/>
  <br>g. Display All Patients<br/>
  <br>h. Find Doctor by ID<br/>
  <br>i. Find Patient by ID<br/>
  <br>j. Exit<br/>
