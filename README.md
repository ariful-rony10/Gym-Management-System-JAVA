![AIUB Logo](https://i.ibb.co/Bs2x24J/aiub-logo.jpg)

# GYM MANAGEMENT SYSTEM
[**DOWNLOAD PROJECT REPORT IN DOCS**](https://aiubedu60714-my.sharepoint.com/:w:/g/personal/17-35646-3_student_aiub_edu/EdwoqD1WWF9IlXqMgXPdvj4BNIwgQtFuoe-AzVTL-uEZOA?e=AjtPhU)

Prepared By
| Name      | ID |
| ----------- | ----------- |
| Islam, Md. Ariful      | 17-35646-3       |
| Ishrak, Md.Nafis   | 17-35500-3        |
|Ismail, Isrita  | 17-35675-3|
|Rafa, Humayara Chowdhury|17-35413-3|

**SUBJECT:** Advance Database Management System

**SECTION:** B

**Guided By:** **Juena Ahmed Noshin**, Department of Computer Science,  American International University-Bangladesh

## CONTENTS

- [GYM MANAGEMENT SYSTEM](#gym-management-system)
  - [CONTENTS](#contents)
    - [INTRODUCTION](#introduction)
    - [PROJECT PROPOSAL](#project-proposal)
    - [DIAGRAMS](#diagrams)
      - [**Use Case Diagram**](#use-case-diagram)
      - [**Class Diagram**](#class-diagram)
      - [**Activity Diagram**](#activity-diagram)
    - [USER INTERFACE](#user-interface)
    - [SCENARIO DESCRIPTION](#scenario-description)
    - [ER DIAGRAM](#er-diagram)
    - [NORMALIZATION](#normalization)
  - [### SCHEMA DIAGRAM](#-schema-diagram)
    - [TABLE CREATION](#table-creation)
    - [DATA INSERTION](#data-insertion)
    - [SQL](#sql)
    - [PL/SQL](#plsql)
    - [CONCLUSION](#conclusion)

### [INTRODUCTION](#introduction)

Our project is about a gym management system. We know in a gym there are various kinds of data that is need to keep safe. If we use a digital system for that then it will be very efficient. We know in a normal gym there are gym customer, staff, instrument etc. are exist. So in our data base we will keep the information about them. Additionally we will save the data about income and expense. So at last we hope that it will help a gym to maintain its activity efficiently.

### [PROJECT PROPOSAL](#project-proposal)

In gym management system, after the planning and analysis phase of the system gets completed. Then the next phase required to transform the collected required system information into structural blueprint which will serve as a reference while constructing the working system. It is a phase when most of the risks and error unveiled so it’s is good practices to take care of this thing from the start. This is a fully fledged system which will be the backbone of the while management of the gym so ignoring the risk or error is not an option as later it can make a greater form of itself. So, it is better to minimize the problems faced by both staff and the manager in the Organization.

### [DIAGRAMS](#diagrams)

#### [**Use Case Diagram**](#use-case-diagram)

---
![Use Case Diagram](https://i.ibb.co/LYdZtpz/user-case-diagram.jpg)

#### [**Class Diagram**](#class-diagram)

---
![Class Diagram](https://i.ibb.co/6gGmf6C/class-diagram.jpg)

#### [**Activity Diagram**](#activity-diagram)

----
![Activity Diagram](https://i.ibb.co/PwGLHWM/activity-dragram.jpg)

### [USER INTERFACE](#user-interface)

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/HKCSthQ/user-interface-1.jpg">  blah |  <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/YN8m7g7/user-interface-2.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/tsLL9fp/user-interface-3.jpg">|
|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/JFngxTN/user-interface-4.jpg">  |  <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/nBBG5V2/user-interface-5.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/qNyRPgv/user-interface-6.jpg">|
|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/tpr5PKJ/user-interface-7.jpg">  |  <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/0mQ3ZZ9/user-interface-8.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/g3x3dmJ/user-interface-9.jpg">|
|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/1byn4CF/user-interface-10.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/C8K27jm/user-interface-11.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/tsFWPnJ/user-interface-12.jpg">|
|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/182dL5z/user-interface-13.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/TWV7Qcp/user-interface-14.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/34JzcCS/user-interface-15.jpg">|
|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/wMCmm62/user-interface-16.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/3W2xdsh/user-interface-17.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/9q8SC71/user-interface-18.jpg">|
|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/PhVCHvT/user-interface-19.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/DrrCXd2/user-interface-20.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/87N1fVP/user-interface-21.jpg">|
|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/C6LDhkL/user-interface-22.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/njTPd3Q/user-interface-23.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/K6Hhx87/user-interface-24.jpg">|
|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/CPbGtNH/user-interface-25.jpg">|<img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/ZGFRTY8/user-interface-26.jpg">||


### [SCENARIO DESCRIPTION](#scenario-description)

An owner wants to make a database management system for his gym where an owner can own exactly one gym where gym will be identified by its registration number, name, phone, e-mail, address will be stored. Owner will be identified by his id and name address, phone, e-mail will be also stored. A gym has many branch where branch will be identified by id and name, place will be stored. An   owner can appoint many manager to manage many branch but a branch can manage by exactly one manager. Manager will be identified by his id and name, phone, e-mail, salary will also be stored. Manager can only hire a technician to provide service to his branch. Technician will be identified by his id and name, phone, address, salary, schedule will be stored. A manager can employ many trainer to train member. A trainer can be trained many member but a member can be trained by exactly one trainer. Trainer will be identified by his id and his name, address, phone, name, salary, category, e-mail, schedule will also be stored. A branch can offer many program. A program can offer by exactly one gym. Program will be identified by its id, name, duration, cost will be also stored. A member can enroll exactly one program. Member will be identified by his id, name, phone, e-mail, age, height, weight, blood group, address, schedule will also be stored.

### [ER DIAGRAM](#er-diagram)

![ER Diagram](https://i.ibb.co/48dQFRQ/er-diagram.jpg)

### [NORMALIZATION](#normalization)



**Own:**

UNF:
1.	Own `(g_reg_number, g_phone, g_mail, g_name, g_address, o_id, o_name, o_address, o_phone, o_mail)`
1NF:
           There is no multivalued attribute.
1.	`(g_reg_number, g_phone, g_mail, g_name, g_address, o_id, o_name, o_address, o_phone, o_mail)`
2NF:
1.	`(g_reg_number, g_phone, g_mail, g_name, g_address)`
2.`	(o_id, o_name, o_address, o_phone, o_mail)`
3NF:
1.	`(g_reg_number, g_phone, g_mail, g_name, g_address)`
2.	`(o_id, o_name, o_address, o_phone, o_mail)`

Table creation:
1.	`(g_reg_number, g_phone, g_mail, g_name, g_address, o_id)`
2.	`(o_id, o_name, o_address, o_phone, o_mail)`

**Appoints:**

UNF:
1.	`Appoints (o_id, o_name, o_address, o_phone, o_mail, m_id, m_salary, m_name, m_mail, m_phone)`
1NF:
            There is no multivalued attribute.
1.	`(o_id, o_name, o_address, o_phone, o_mail, m_id, m_salary, m_name, m_mail, m_phone)`
2NF:
1.	`(o_id, o_name, o_address, o_phone, o_mail)`
2.	`(m_id, m_salary, m_name, m_mail, m_phone)`
3NF:
1.	`(o_id, o_name, o_address, o_phone, o_mail)`
2.	`(m_id, m_salary, m_name, m_mail, m_phone)`

Table creation:
1.	`(o_id, o_name, o_address, o_phone, o_mail)`
2.	`(m_id, m_salary, m_name, m_mail, m_phone, o_id)`

**Hire:**

UNF:
1.	Hire `(te_id, te_name, te_phone, te_salary, te_address, te_schedule, m_id, m_salary, m_name, m_mail, m_phone)`
1NF:
            There is no multivalued attribute.
1.	`(te_id, te_name, te_phone, te_salary, te_address, te_schedule, m_id, m_salary, m_name, m_mail, m_phone)`
2NF:
1.	`(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2.	`(m_id, m_salary, m_name, m_mail, m_phone)`
3NF:
1.	`(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2.	`(m_id, m_salary, m_name, m_mail, m_phone)`

Table creation:
1.	`(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2.	`(m_id, m_salary, m_name, m_mail, m_phone, te_id)`

**Manage:**

UNF:
1.	Manage `(m_id, m_salary, m_name, m_mail, m_phone, b_id, b_place, b_name)`
1NF:	
           There is no multivalued attribute.
1.	`(m_id, m_salary, m_name, m_mail, m_phone, b_id, b_place, b_name)`
2NF:
1.	`(m_id, m_salary, m_name, m_mail, m_phone)`
2.	`(b_id, b_place, b_name)`
3NF:
1.	`(m_id, m_salary, m_name, m_mail, m_phone)`
2.	`(b_id, b_place, b_name)`


Table creation:
1.	`(b_id, b_place, b_name)`
2.	`(m_id, m_salary, m_name, m_mail, m_phone, b_id)`

**Service:**
UNF:
1.	Service `(te_id, te_name, te_phone, te_salary, te_address, te_schedule, b_id, b_place, b_name)`
1NF:
             There is no multivalued attribute.
1.	`(te_id, te_name, te_phone, te_salary, te_address, te_schedule, b_id, b_place, b_name)`
2NF:
1.	`(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2.	`(b_id, b_place, b_name)`
3NF:
1.	`(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2.	`(b_id, b_place, b_name)`

Table creation:
1.	`(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2.	`(b_id, b_place, b_name, te_id)`



**Has:**

UNF:
1.	Has `(g_reg_number, g_phone, g_mail, g_name, g_address, b_id, b_place, b_name)`
1NF:
   	There is no multivalued attribute.
1.	`(g_reg_number, g_phone, g_mail, g_name, g_address, b_id, b_place, b_name)`
2NF:
1.	`(g_reg_number, g_phone, g_mail, g_name, g_address) `
2.	`(b_id, b_place, b_name)`
3NF:
1.	`(g_reg_number, g_phone, g_mail, g_name, g_address) `
2.	`(b_id, b_place, b_name)`

Table creation:
1.	`(g_reg_number, g_phone, g_mail, g_name, g_address)`
2.	`(b_id, b_place, b_name, g_reg_number)`


**Offers:**

UNF:
1.	Offers `(p_id, p_name, duration, cost, b_id, b_place, b_name)`
1NF:
There is no multivalued attribute.
1.	`(p_id, p_name, duration, cost, b_id, b_place, b_name)`
2NF:
1.	`(p_id, p_name, duration, cost)`
2.`	(b_id, b_place, b_name)`
3NF:
1.	`(p_id, p_name, duration, cost)`
2.	`(b_id, b_place, b_name)`


Table creation:
1.	`(b_id, b_place, b_name)`
2.	`(p_id, p_name, duration, cost, b_id)`
**Employs:**

UNF:
1.	Employs `(m_id, m_salary, m_name, m_mail, m_phone, t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
1NF:
	There is no multivalued attribute.
1.	`(m_id, m_salary, m_name, m_mail, m_phone, t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
2NF:
1.	`(m_id, m_salary, m_name, m_mail, m_phone)`
2.	`(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
3NF:
1.	`(m_id, m_salary, m_name, m_mail, m_phone)`
2.	`(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`

Table creation:
1.	`(m_id, m_salary, m_name, m_mail, m_phone)`
2.	`(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail, m_id)`
**Trained:**

UNF:
1.	Trained `(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail, mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`
1NF:
	There is no multivalued attribute.
1.	`(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail, mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`
2NF:
1.	`(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
2.	`(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`
3NF:
1.	`(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
2.	`(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

Table creation:
1.	`(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
2.	`(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone, t_id)`

**Enroll:**

UNF:
1.	Enroll `(p_id, p_name, duration, cost, mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

1NF:
	There is no multivalued attribute.
1.	`(p_id, p_name, duration, cost, mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

2NF:
1.	`(p_id, p_name, duration, cost)`
2.	`(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

3NF:
1.	`(p_id, p_name, duration, cost)`
2.	`(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

Table creation:
1.	`(p_id, p_name, duration, cost)`
2.	`(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

### [SCHEMA DIAGRAM](#schema=diagram)
---
![Schema Diagram](https://i.ibb.co/B6NHG9m/schema-diagram.jpg)
### [TABLE CREATION](#table-creation)
```
.create table owner(o_id number(2) primary key, o_name varchar2(40) not null, o_address varchar2(40) not null, o_phone number(20) not null,o_mail varchar2(40)not null);
```
![Table Creaetion](https://i.ibb.co/2Y7j4Y7/create-table-1.jpg)

---

```
create table gym(g_reg_number number(20) primary key, g_name varchar2(40) not null, g_address varchar2(40) not null, g_phone number(20) not null,g_mail varchar2(40)not null,o_id number(2)not null);
```
![Table Creaetion](https://i.ibb.co/JFpBfXd/create-table-2.jpg)

---
```
create table technician(te_id number(2) primary key, te_name varchar2(40) not null, te_salary number(10) not null, te_phone number(20) not null,te_address varchar2(40)not null,te_schedule number(2)not null)
```

![Table Creation](https://i.ibb.co/tbG5TWr/create-table-3.jpg)

---
```
create table branch(b_id number(2) primary key, b_name varchar2(40) not null, b_place varchar2(40) not null, te_id number(2) not null,g_reg_number number(20)not null);
```

![Table Creation](https://i.ibb.co/TmcbYxj/create-table-4.jpg)

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

---
```

```

![Table Creation]()

### [DATA INSERTION](#data-insertion)

### [SQL](#sql)

### [PL/SQL](#pl-sql)

### [CONCLUSION](#conclution)

The project has been developed in a very short period of time and all efforts have been taken so that this project is very efficient in its execution there still exists some scope of improvement in our project. The following lists some of the enhancement that can be added incorporate into the project. Application of the project can be done more attractively. Database management and all maintenance module can be updated which helps the administrator. More security measures can be taken. There are also few features which can be integrated with this system to make it more flexible. Below list shows the future points to be consider: • Real-time Chat BOT option for members and trainer, so that members can directly enquiry theirs trainer on any time through the Chat BOT. • Automated Fitness suggestion by enquiring the condition of the health. • Real time Claim Processing Bot. • Video conversation option for trainers and members. • Online payment through face recognition. • Barcode generation for membership card and using this, members can take entry to Gym. • Finger print matching for taking entry to gym. “GYM MANAGEMENT SYSTEM” is successfully designed and developed to fulfilling the necessary requirements, as identified in the requirements analysis phase, such as the system is very much user friendly, form level validation and field level validation are performing very efficiently. The old manual system was suffering from a series of drawbacks. The present project has been developed to meet the aspirations indicated in the modern age.


















https://i.ibb.co/0tkWddz/create-table-5.jpg
https://i.ibb.co/wyBChKJ/create-table-6.jpg
https://i.ibb.co/LkbLTwd/create-table-7.jpg
https://i.ibb.co/QDxkWLw/create-table-8.jpg
https://i.ibb.co/nRNg7ps/create-table-9.jpg
https://i.ibb.co/3WZdj5G/create-table-10.jpg
https://i.ibb.co/YbC7DsZ/create-table-11.jpg
https://i.ibb.co/Q8Ds7xG/create-table-12.jpg
https://i.ibb.co/C9P5ScV/create-table-13.jpg
https://i.ibb.co/ChVhyBZ/create-table-14.jpg
https://i.ibb.co/0ZpzwYh/create-table-15.jpg
https://i.ibb.co/k4YDM2w/create-table-16.jpg
https://i.ibb.co/ZfpQkxh/create-table-17.jpg
https://i.ibb.co/61YtpYc/create-table-18.jpg
https://i.ibb.co/6YMRLyG/create-table-19.jpg
https://i.ibb.co/WFzXNJJ/create-table-20.jpg
https://i.ibb.co/N9rMSb3/create-table-21.jpg
https://i.ibb.co/RctCr1f/create-table-22.jpg
https://i.ibb.co/gJYjwgL/create-table-23.jpg
https://i.ibb.co/2c0mHFL/create-table-24.jpg
https://i.ibb.co/JBPxnGd/create-table-25.jpg
https://i.ibb.co/m8VvgrX/create-table-26.jpg
https://i.ibb.co/MhwvrxH/create-table-27.jpg
https://i.ibb.co/fQpC1hZ/create-table-28.jpg
https://i.ibb.co/gTRyJQn/create-table-29.jpg
https://i.ibb.co/VJMZx9x/create-table-30.jpg
https://i.ibb.co/QHpzMCq/create-table-31.jpg
https://i.ibb.co/9HvsG42/create-table-32.jpg
https://i.ibb.co/KmF5r68/create-table-33.jpg
https://i.ibb.co/Y3rgV56/create-table-34.jpg
https://i.ibb.co/mXNnRYv/create-table-35.jpg
https://i.ibb.co/bNBdSZG/create-table-36.jpg
https://i.ibb.co/dtcnG5F/create-table-37.jpg
https://i.ibb.co/DLNqZX4/create-table-38.jpg
https://i.ibb.co/ynp2XtV/create-table-39.jpg
https://i.ibb.co/jW4JGPN/create-table-40.jpg
https://i.ibb.co/9VMXT78/create-table-41.jpg
https://i.ibb.co/JjV49zf/create-table-42.jpg
https://i.ibb.co/cYmkmgr/create-table-43.jpg
https://i.ibb.co/drqTLfH/create-table-44.jpg
https://i.ibb.co/zXHhjct/create-table-45.jpg
https://i.ibb.co/WGYhf7m/create-table-46.jpg
https://i.ibb.co/P5fwLk4/create-table-47.jpg
https://i.ibb.co/h16G5qp/create-table-48.jpg
https://i.ibb.co/VVg7X53/create-table-49.jpg
https://i.ibb.co/Tr1Wz90/create-table-50.jpg
