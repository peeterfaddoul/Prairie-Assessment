Codi offers courses in different cohorts. In each cohort, various students are enrolled. Each cohort 
lasts up to into 6 to 7 months. In each cohort various topics are taught. One topic is taught by at most one mentor and one mentor can teach more than one topic. Mentors are split between two department that deliver different topics each (Full Stack Web Dev and English & Life Skills).

Consider the following requirements:  
1. Each mentor at Codi has an SSN, a name (first and last name), DOB, a seniority level(junior/mid/senior), a salary, an office, and topics specialty.  
2. Each student at Codi has a Student no, SSN, a name (first and last name), DOB, and several skills. 
3. Each Cohort at Codi has many registered students, a student can only belong to one Cohort, a Cohort has a Cohort ID, number, start date, end date.
4. Each cohort has multiple topics that are delivered by mentors.
5. Each topic is taught by one mentor, and each mentor can teach multiple topics.
6. Each topic has an ID, title, and description
7. Each mentor belongs to a department, where each department has a department ID, name, an office, and topic speciality.

The following are requested: 
1. Design and draw an ER diagram that captures the information about Codi: 
• Draw entities, relationships, and attributes.  
• Show relationship cardinality. 
• Underline the primary keys.  
2. Design a relational schema based on the ER diagram designed in the previous point by mapping the ER design to the corresponding relational schema. 
3. Implement the database schema using one of the relational DBMS (mysql, sql server) and add at least 4 records for each table.
4. Write the relational algebra expressions to satisfy the following queries: 
• Find the first name, last name, and rank for all mentors at Codi. 
• Find all instructors at office ‘333’. 
• Find all instructors who earn greater than $1000. 
• Find the first name, last name, and rank for all instructors who earn greater than $1000. 
• Find the first and last name of all instructors for the department named “English & Life Skills”. 
• Find the student number of all students having the “Development” skill 
• Find the student SSN of all students having the “Development” skill 