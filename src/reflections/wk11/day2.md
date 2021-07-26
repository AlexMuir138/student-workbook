Journal 46
What is the difference between a primary key and a foreign key

Foreign keys are attributes that you assign so that you can access many to many relationships where primary keys are simply the ids you can pull from an object.

What is an Alias?

An assigned shorthand for variables that have specific functions or long names.

Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors_patients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)
string  sql = @"
    //   SELECT
    //   d.*,
    //   dp.*
    //   FROM doctors_patients dp
    //   JOIN keeps d ON d.id = dp.keepId
    //   WHERE dp.patientId = @PatientId;

https://github.com/AlexMuir138/RealmCommander.git