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
![download](https://github.com/DrUmaRaniV/DBMS/assets/119393307/d6c707dc-38ac-453f-ac14-cbb877d4542b)



### Relational model

![Screenshot 2023-10-29 210705](https://github.com/DrUmaRaniV/DBMS/assets/119393307/86a08856-4c70-400a-aaf3-21a5f397ce4a)



### SQL DDL Schema 
```
CREATE TABLE BANK
(
  CODE INT NOT NULL,
  NAME INT NOT NULL,
  ADDRESS INT NOT NULL
);

CREATE TABLE BANK_BRANCH
(
  ADDRESS INT NOT NULL,
  BRANCH_NO INT NOT NULL
);

CREATE TABLE ACCOUNT
(
  ACCOUNT_NO INT NOT NULL,
  BALANCE INT NOT NULL
);

CREATE TABLE CUSTOMER
(
  SSN INT NOT NULL,
  NAME INT NOT NULL,
  ADDRESS INT NOT NULL,
  PHONE INT NOT NULL
);

CREATE TABLE LOANS
(
  LOAN_NO INT NOT NULL,
  AMOUUNT INT NOT NULL
);
```
## RESULT 
<div align="justify">
Thus the ER diagram was drawn and relational diagram, SQL DDL staements are generated using ERD plus tool.
</div>
