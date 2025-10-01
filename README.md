## Features of Hospital Single Linked List
1. Patient Management

  a. Add a Patient: store patient details (ID, name, age, gender, disease).<br/>
  <br>b. Remove a Patient: delete a patient by ID and update the assigned room’s capacity.
  c. Find Patient by ID: search for a specific patient.
  d. Display All Patients: show details of every patient, including their assigned room and doctor.

2. Doctor Management

  a. Add a Doctor: store doctor details (ID, name, specialty)
  b. Find Doctor by ID: search for a specific doctor and display their details plus rooms.
  c. Display All Doctors: show all doctors and their associated rooms.

3. Room Management

  a. Add Room under a Doctor: link a new room (room number, max capacity) to a doctor.
  b. Assign Room to Patient: assign an available room to a patient, checking capacity.
  c. Room Availability Check: ensures no duplicate room numbers and checks if a room is full.

4. Data Linking

  a. Each patient can be assigned to a room.
  b. Each room belongs to a doctor.
  c. From a patient, you can trace which room they are in and which doctor oversees it.

5. Menu-driven Console Interface (from main.cpp)

The system provides a menu with these options:

  a. Add Patient
  b. Add Doctor
  c. Add Room to Doctor
  d. Assign Room to Patient
  e. Remove Patient
  f. Display All Doctors
  g. Display All Patients
  h. Find Doctor by ID
  i. Find Patient by ID
  j. Exit
