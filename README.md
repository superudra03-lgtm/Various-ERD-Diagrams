ASG3:
Using ERDPlus, I’m going to create ER Diagrams, show the entities, and define the relationships between them. 

Diagram #1:
A health care organization keeps track of its doctors and outpatient locations
For each doctor, it keeps track of the DoctorID (unique), DoctorName, and DoctorYearOfMDGraduation (year of graduating from medical school)
For each outpatient location, it keeps track of the OLID (unique) and OLName
Each doctor works at either one outpatient location or none (strictly working in the main hospital), and each outpatient location can have between none (rehab and minor health issues only) and one doctor.

Diagram #2:
A health care organization keeps track of its doctors and outpatient locations
For each doctor, it keeps track of the DoctorID (unique), DoctorName, and DoctorYearOfMDGraduation (year of graduating from medical school)
For each outpatient location, it keeps track of the OLID (unique) and OLName
Each doctor works at either one or many outpatient locations, and each outpatient location must have at least one, but can have many doctors working at it
For each occurrence of a doctor working at an outpatient location, we keep track of the NoOfHoursPerWeek (number of hours per week that a doctor works at an outpatient location)

Diagram #3: 
A health care organization keeps track of its doctors and outpatient locations
For each doctor, it keeps track of the DoctorID (unique), DoctorName, and DoctorYearOfMDGraduation (year of graduating from medical school)
For each outpatient location, it keeps track of the OLID (unique) and OLName
Each doctor works at between 2 and 4 outpatient locations, and each location has between 3 and 10 doctors.

Diagram #4: 
A health care organization keeps track of its doctors
For each doctor, it keeps track of the DoctorID (unique), DoctorName, and DoctorYearOfMDGraduation (year of graduating from medical school)
A doctor can be a resident for either one or none of the faculty doctors.  A doctor can have many resident doctors, but does not have to have any.

Diagram #5: 
A health care organization keeps track of its doctors and outpatient locations
For each doctor, it keeps track of the DoctorID (unique), DoctorName, and DoctorYearOfMDGraduation (year of graduating from medical school)
For each outpatient location, it keeps track of the OLID (unique) and OLName
Each doctor works at between one and many outpatient locations, and each outpatient location must have at least one, but can have many doctors working at it
Each doctor manages between zero and one outpatient location, and each outpatient location has exactly one doctor managing it

Diagram #6:
A health care organization keeps track of outpatient locations and examination rooms within the outpatient locations
For each outpatient location, it keeps track of the OLID (unique) and OLName
For each examination room, it keeps track of the ERoomNumber (unique within its outpatient center, but examination rooms in different outpatient locations can have the same ERoomNumber) and ERoomSize
Each outpatient location must have at least one, but can have many examination rooms, and each examination room is located in one outpatient location

Diagram #7: 
The database shall keep track of multiple products
The database shall keep track of multiple suppliers
The database shall keep track of multiple components
Keep track of which suppliers provide which components for which product.
Every product contains one or more components, each of which is provided by one or more suppliers
Every supplier can provide many components for many products, but they also do not have to provide any components for any products.
Every component is provided by one or more suppliers for one or more products.



ASG4:
Snooty Fashions is an exclusive custom fashion designer business. Create the ER diagram for the Snooty Fashions Operations Database based on the following requirements. 
The Snooty Fashions Operations Database will keep track of the following: 

• For each designer: a unique designer identifier and the name (composed of first and last name); 

• For each customer: a unique customer identifier as well as his or her name and multiple phone numbers; 

• For each tailoring technician: a unique identifier as well as his or her name (composed of first and last name); 

• For each outfit: a unique outfit identifier as well as the outfit’s planned date of completion and its price; 

• For each fashion show: a unique show identifier as well as the date of the show and location; 

• Each designer designs many outfits. Each outfit has only one designer. 

• Each outfit is sold (in advance) to exactly one customer. Customers can buy one or more outfits (Snooty Fashions will not track customers who have not made any purchases yet). 

• Each tailoring technician must work on at least one outfit but can work on many. Each outfit has at least one tailoring technician working on it, but it can have many. 

• Snooty Fashions will keep track of the date when a tailoring technician started working on a particular outfit and when it was completed. The business also wants to know how long it took to work on a particular outfit. 

• Each designer can participate in a number of fashion shows but does not have to participate in any. Each fashion show can feature one or two Snooty Fashions designers. (Snooty Fashions will not keep track of fashion shows that do not feature Snooty Fashions designers.)
