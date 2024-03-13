# EXP NO 1: ER DIAGRAM CREATION, RELATIONAL MODEL AND SCHEMA GENERATION  
### DATE
## AIM:
<div align="justify">
   To create a ER Diagram for Bank management system or College management system using ERD Plus tool and generate the relational model with schema. 
</div>

## Algorithm
1. Create a login with https://erdplus.com.
2. Create a new ER Diagram with name
3. Create a strong entity, relation and attributes.
4. Create a weak entity, relation and attributes.
5. Specify attributes unique, multivalued and composite attributes.

### ER Diagram 
![image](https://github.com/bhuvanselva/DBMS/assets/119847426/31c2bb8a-351a-458b-b3e5-24a37b0c7384)

### Relational model
![Screenshot 2024-03-13 105340](https://github.com/bhuvanselva/DBMS/assets/119847426/5f665d24-85a3-426e-9553-4dede4f8f1ce)

### SQL DDL Schema 
```
CREATE TABLE Student
(
  Surname INT NOT NULL,
  GiveNames INT NOT NULL,
  Student_ID INT NOT NULL,
  Date_of_bIrth INT NOT NULL
);

CREATE TABLE Program
(
  Name INT NOT NULL,
  Program_ID INT NOT NULL,
  Creditpoints INT NOT NULL,
  Yearcommenced INT NOT NULL
);

CREATE TABLE Course
(
  Name INT NOT NULL,
  Course_ID INT NOT NULL,
  NewAttribute INT NOT NULL,
  Year_commenced INT NOT NULL
);
```
## RESULT 
<div align="justify">
Thus the ER diagram was drawn and relational diagram, SQL DDL staements are generated using ERD plus tool.
</div>
