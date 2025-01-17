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
```
DEVELOPED BY: SOUNDARIYAN M.N
REG NO: 212222230146
```
![image](https://github.com/soundariyan18/DBMS/assets/119393307/686a5fa9-0555-4d4f-ae52-3d0390820614)



### Relational model
![image](https://github.com/soundariyan18/DBMS/assets/119393307/d8f43e5a-a81b-4eb4-908c-d800a7a94cdd)



### SQL DDL Schema 
```
CREATE TABLE Entity
(
  Address INT NOT NULL,
  Name INT NOT NULL,
  SSN INT NOT NULL
);

CREATE TABLE Branch
(
  Address INT NOT NULL,
  Affiliation INT NOT NULL,
  Name INT NOT NULL
);
```

## RESULT 
<div align="justify">
Thus the ER diagram was drawn and relational diagram, SQL DDL staements are generated using ERD plus tool.
</div>
