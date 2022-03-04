![AIUB Logo](https://i.ibb.co/Bs2x24J/aiub-logo.jpg)

# GYM MANAGEMENT SYSTEM

[**DOWNLOAD PROJECT REPORT IN DOCS**](https://aiubedu60714-my.sharepoint.com/:w:/g/personal/17-35646-3_student_aiub_edu/EdwoqD1WWF9IlXqMgXPdvj4BNIwgQtFuoe-AzVTL-uEZOA?e=AjtPhU)

Prepared By
| Name                     | ID         |
| ------------------------ | ---------- |
| Islam, Md. Ariful        | 17-35646-3 |
| Ishrak, Md.Nafis         | 17-35500-3 |
| Ismail, Isrita           | 17-35675-3 |
| Rafa, Humayara Chowdhury | 17-35413-3 |

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
    - [SCHEMA DIAGRAM](#schema-diagram)
    - [TABLE CREATION](#table-creation)
      - [**DATA INSERTION:**](#data-insertion)
    - [SQL](#sql)
      - [**SINGLE ROW:**](#single-row)
      - [**GROUP FUNCTION:**](#group-function)
      - [**SUB-QUERY:**](#sub-query)
      - [**JOINING:**](#joining)
      - [**VIEWS:**](#views)
      - [**SYNONYM:**](#synonym)
    - [PL/SQL](#plsql)
      - [**FUNCTION:**](#function)
      - [**PROCEDURE:**](#procedure)
      - [**RECORD:**](#record)
      - [**CURSOR:**](#cursor)
      - [**TRIGGER:**](#trigger)
      - [**PACKAGE:**](#package)
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

|                                                                                                              |                                                                                                         |                                                                                                         |
| :----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------: |
| <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/HKCSthQ/user-interface-1.jpg">  blah | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/YN8m7g7/user-interface-2.jpg">  | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/tsLL9fp/user-interface-3.jpg">  |
|    <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/JFngxTN/user-interface-4.jpg">    | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/nBBG5V2/user-interface-5.jpg">  | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/qNyRPgv/user-interface-6.jpg">  |
|    <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/tpr5PKJ/user-interface-7.jpg">    | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/0mQ3ZZ9/user-interface-8.jpg">  | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/g3x3dmJ/user-interface-9.jpg">  |
|   <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/1byn4CF/user-interface-10.jpg">    | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/C8K27jm/user-interface-11.jpg"> | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/tsFWPnJ/user-interface-12.jpg"> |
|   <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/182dL5z/user-interface-13.jpg">    | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/TWV7Qcp/user-interface-14.jpg"> | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/34JzcCS/user-interface-15.jpg"> |
|   <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/wMCmm62/user-interface-16.jpg">    | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/3W2xdsh/user-interface-17.jpg"> | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/9q8SC71/user-interface-18.jpg"> |
|   <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/PhVCHvT/user-interface-19.jpg">    | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/DrrCXd2/user-interface-20.jpg"> | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/87N1fVP/user-interface-21.jpg"> |
|   <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/C6LDhkL/user-interface-22.jpg">    | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/njTPd3Q/user-interface-23.jpg"> | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/K6Hhx87/user-interface-24.jpg"> |
|   <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/CPbGtNH/user-interface-25.jpg">    | <img width="1604" alt="User Interface Screenshot" src="https://i.ibb.co/ZGFRTY8/user-interface-26.jpg"> |                                                                                                         |

### [SCENARIO DESCRIPTION](#scenario-description)

An owner wants to make a database management system for his gym where an owner can own exactly one gym where gym will be identified by its registration number, name, phone, e-mail, address will be stored. Owner will be identified by his id and name address, phone, e-mail will be also stored. A gym has many branch where branch will be identified by id and name, place will be stored. An   owner can appoint many manager to manage many branch but a branch can manage by exactly one manager. Manager will be identified by his id and name, phone, e-mail, salary will also be stored. Manager can only hire a technician to provide service to his branch. Technician will be identified by his id and name, phone, address, salary, schedule will be stored. A manager can employ many trainer to train member. A trainer can be trained many member but a member can be trained by exactly one trainer. Trainer will be identified by his id and his name, address, phone, name, salary, category, e-mail, schedule will also be stored. A branch can offer many program. A program can offer by exactly one gym. Program will be identified by its id, name, duration, cost will be also stored. A member can enroll exactly one program. Member will be identified by his id, name, phone, e-mail, age, height, weight, blood group, address, schedule will also be stored.

### [ER DIAGRAM](#er-diagram)

![ER Diagram](https://i.ibb.co/48dQFRQ/er-diagram.jpg)

### [NORMALIZATION](#normalization)

**Own:**

UNF:

1. Own `(g_reg_number, g_phone, g_mail, g_name, g_address, o_id, o_name, o_address, o_phone, o_mail)`
1NF:
           There is no multivalued attribute.
1. `(g_reg_number, g_phone, g_mail, g_name, g_address, o_id, o_name, o_address, o_phone, o_mail)`
2NF:
1. `(g_reg_number, g_phone, g_mail, g_name, g_address)`
2.`(o_id, o_name, o_address, o_phone, o_mail)`
3NF:
1. `(g_reg_number, g_phone, g_mail, g_name, g_address)`
2. `(o_id, o_name, o_address, o_phone, o_mail)`

Table creation:

1. `(g_reg_number, g_phone, g_mail, g_name, g_address, o_id)`
2. `(o_id, o_name, o_address, o_phone, o_mail)`

**Appoints:**

UNF:

1. `Appoints (o_id, o_name, o_address, o_phone, o_mail, m_id, m_salary, m_name, m_mail, m_phone)`
1NF:
            There is no multivalued attribute.
1. `(o_id, o_name, o_address, o_phone, o_mail, m_id, m_salary, m_name, m_mail, m_phone)`
2NF:
1. `(o_id, o_name, o_address, o_phone, o_mail)`
2. `(m_id, m_salary, m_name, m_mail, m_phone)`
3NF:
1. `(o_id, o_name, o_address, o_phone, o_mail)`
2. `(m_id, m_salary, m_name, m_mail, m_phone)`

Table creation:

1. `(o_id, o_name, o_address, o_phone, o_mail)`
2. `(m_id, m_salary, m_name, m_mail, m_phone, o_id)`

**Hire:**

UNF:

1. Hire `(te_id, te_name, te_phone, te_salary, te_address, te_schedule, m_id, m_salary, m_name, m_mail, m_phone)`
1NF:
            There is no multivalued attribute.
1. `(te_id, te_name, te_phone, te_salary, te_address, te_schedule, m_id, m_salary, m_name, m_mail, m_phone)`
2NF:
1. `(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2. `(m_id, m_salary, m_name, m_mail, m_phone)`
3NF:
1. `(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2. `(m_id, m_salary, m_name, m_mail, m_phone)`

Table creation:

1. `(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2. `(m_id, m_salary, m_name, m_mail, m_phone, te_id)`

**Manage:**

UNF:

1. Manage `(m_id, m_salary, m_name, m_mail, m_phone, b_id, b_place, b_name)`
1NF:
           There is no multivalued attribute.
1. `(m_id, m_salary, m_name, m_mail, m_phone, b_id, b_place, b_name)`
2NF:
1. `(m_id, m_salary, m_name, m_mail, m_phone)`
2. `(b_id, b_place, b_name)`
3NF:
1. `(m_id, m_salary, m_name, m_mail, m_phone)`
2. `(b_id, b_place, b_name)`

Table creation:

1. `(b_id, b_place, b_name)`
2. `(m_id, m_salary, m_name, m_mail, m_phone, b_id)`

**Service:**
UNF:

1. Service `(te_id, te_name, te_phone, te_salary, te_address, te_schedule, b_id, b_place, b_name)`
1NF:
             There is no multivalued attribute.
1. `(te_id, te_name, te_phone, te_salary, te_address, te_schedule, b_id, b_place, b_name)`
2NF:
1. `(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2. `(b_id, b_place, b_name)`
3NF:
1. `(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2. `(b_id, b_place, b_name)`

Table creation:

1. `(te_id, te_name, te_phone, te_salary, te_address, te_schedule)`
2. `(b_id, b_place, b_name, te_id)`

**Has:**

UNF:

1. Has `(g_reg_number, g_phone, g_mail, g_name, g_address, b_id, b_place, b_name)`
1NF:
    There is no multivalued attribute.
1. `(g_reg_number, g_phone, g_mail, g_name, g_address, b_id, b_place, b_name)`
2NF:
1. `(g_reg_number, g_phone, g_mail, g_name, g_address)`
2. `(b_id, b_place, b_name)`
3NF:
1. `(g_reg_number, g_phone, g_mail, g_name, g_address)`
2. `(b_id, b_place, b_name)`

Table creation:

1. `(g_reg_number, g_phone, g_mail, g_name, g_address)`
2. `(b_id, b_place, b_name, g_reg_number)`

**Offers:**

UNF:

1. Offers `(p_id, p_name, duration, cost, b_id, b_place, b_name)`
1NF:
There is no multivalued attribute.
1. `(p_id, p_name, duration, cost, b_id, b_place, b_name)`
2NF:
1. `(p_id, p_name, duration, cost)`
2.`(b_id, b_place, b_name)`
3NF:
1. `(p_id, p_name, duration, cost)`
2. `(b_id, b_place, b_name)`

Table creation:

1. `(b_id, b_place, b_name)`
2. `(p_id, p_name, duration, cost, b_id)`
**Employs:**

UNF:

1. Employs `(m_id, m_salary, m_name, m_mail, m_phone, t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
1NF:
 There is no multivalued attribute.
1. `(m_id, m_salary, m_name, m_mail, m_phone, t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
2NF:
1. `(m_id, m_salary, m_name, m_mail, m_phone)`
2. `(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
3NF:
1. `(m_id, m_salary, m_name, m_mail, m_phone)`
2. `(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`

Table creation:

1. `(m_id, m_salary, m_name, m_mail, m_phone)`
2. `(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail, m_id)`
**Trained:**

UNF:

1. Trained `(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail, mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`
1NF:
 There is no multivalued attribute.
1. `(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail, mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`
2NF:
1. `(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
2. `(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`
3NF:
1. `(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
2. `(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

Table creation:

1. `(t_id, t_phone, t_address, t_name, t_category, t_salary, t_schedule, t_mail)`
2. `(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone, t_id)`

**Enroll:**

UNF:

1. Enroll `(p_id, p_name, duration, cost, mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

1NF:
 There is no multivalued attribute.

1. `(p_id, p_name, duration, cost, mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

2NF:

1. `(p_id, p_name, duration, cost)`
2. `(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

3NF:

1. `(p_id, p_name, duration, cost)`
2. `(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

Table creation:

1. `(p_id, p_name, duration, cost)`
2. `(mem_Id, mem_name, mem_schedule, mem_address, blood_group, weight, height, age, mem_mail, mem_phone)`

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
create table manager(m_id number(2) primary key, m_name varchar2(40) not null, m_salary number(10) not null, m_phone number(20) not null,m_mail varchar2(40)not null, o_id number(2), te_id number(2), b_id number(2));
```

![Table Creation](https://i.ibb.co/0tkWddz/create-table-5.jpg)

---

```
create table program(p_id number(2) primary key, p_name varchar2(40) not null, duration varchar2(40) not null, cost number(20) not null,b_id number(2)not null);
```

![Table Creation](https://i.ibb.co/LkbLTwd/create-table-7.jpg)

---

```
create table trainer(t_id number(2) primary key, t_name varchar2(40) not null, t_address varchar2(40) not null, t_phone number(20) not null,t_mail varchar2(40)not null, t_category varchar2(40),t_salary number(10),t_schedule number(2),m_id number (2));
```

![Table Creation](https://i.ibb.co/wyBChKJ/create-table-6.jpg)

---

```
create table member(mem_id number(2) primary key, mem_name varchar2(40) not null, mem_address varchar2(40) not null, mem_phone number(20) not null,mem_mail 
```

![Table Creation](https://i.ibb.co/QDxkWLw/create-table-8.jpg)

---

```
varchar2(40)notnull,mem_schedule number(2), blood_group varchar2(2),weight number(2), height number(2), age number(3), t_id number(2), p_id number(2));
```

#### **DATA INSERTION:**

---

```
1. insert into owner values('1', 'ROBIN','DHAKA','01626485694','KHAIRUL11100000@GMAIL.COM');
2. insert into owner values('2', 'xxx','DHAKA','01656485694','xxx@GMAIL.COM');
3. insert into owner values('3', 'yyy','DHAKA','01646485694','yyy@GMAIL.COM');
4. insert into owner values('4', 'abc','DHAKA','01636485694','abc@GMAIL.COM');
5. insert into owner values('5', 'def','DHAKA','01616485694','def@GMAIL.COM');

```

![DATA INSERTION](https://i.ibb.co/nRNg7ps/create-table-9.jpg)

---

```
6. insert into technician values('10', 'tareq','5000','01726485694','chittagong', '12');
7. insert into technician values('11', 'robik','5000','01526485694','dhaka', '11');
8. insert into technician values('12', 'shanto','5000','01326485694','comilla', '10');
9. insert into technician values('13', 'saha','5000','01926485694','jamalpur', '9');
10. insert into technician values('14', 'shudip','5000','01626485694','chittagong', '8');

```

![DATA INSERTION](https://i.ibb.co/3WZdj5G/create-table-10.jpg)

---

```
11. insert into gym values('102564856','rex_gym','dhaka','01254689756','rex@gmail.com','1');
12. insert into gym values('102565856','3ex_gym','dhaka','01255689756','3ex@gmail.com','2');
13. insert into gym values('102574856','mex_gym','dhaka','01354689756','mex@gmail.com','3');
14. insert into gym values('102568856','tex_gym','comilla','01754689756','tex@gmail.com','4');
15. insert into gym values('102564876','lex_gym','dhaka','01254789756','lex@gmail.com','5');
```

![DATA INSERTION](https://i.ibb.co/YbC7DsZ/create-table-11.jpg)

---

```
16. insert into branch values('15','rex_gym_br_1','mirpur','10','102564856');
17. insert into branch values('16','rex_gym_br_2','kuratoli','11','102564856');
18. insert into branch values('17','rex_gym_br_3','dhanmondi','12','102564856');
19. insert into branch values('18','rex_gym_br_4','komolapur','13','102564856');
20. insert into branch values('19','rex_gym_br_5','bashundara','14','102564856');


```

![DATA INSERTION](https://i.ibb.co/Q8Ds7xG/create-table-12.jpg)

---

```
21. insert into manager values('20','mr x','20000','01565854536','x@gmail.com','1','10','15');
22. insert into manager values('21','mr y','20000','01665854536','y@gmail.com','1','11','16');
23. insert into manager values('22','mr z','20000','01765854536','z@gmail.com','1','12','17');
24. insert into manager values('23','mr a','20000','01675854536','a@gmail.com','1','13','18');
25. insert into manager values('24','mr b','20000','01875854536','b@gmail.com','1','14','19');

```

![DATA INSERTION](https://i.ibb.co/C9P5ScV/create-table-13.jpg)

---

```
26. insert into program values('30','body_bulding','2','5000','15');
27. insert into program values('31','muscle_bulding','2','7000','15');
28. insert into program values('32','6_pack','2','9000','15');
29. insert into program values('33','4_pack','2','6000','15');
30. insert into program values('34','complete_pacakge','5','15000','15');

```

![DATA INSERTION](https://i.ibb.co/ChVhyBZ/create-table-14.jpg)

---

```

31. insert into trainer values('35','ab','dhaka','016258569558','ab@gmail.com','body_bulding_specialist','15000','11','20');
32. insert into trainer values('36','bc','dhaka','016258569558','bc@gmail.com','muscle_bulding_specialist','15000','9','20');
33. insert into trainer values('37','cd','dhaka','018258569558','cd@gmail.com','6_pack_specialist','15000','7','20');
34. insert into trainer values('38','de','dhaka','018298569558','de@gmail.com','4_pack_specialist','15000','02','20');
35. insert into trainer values('39','ef','dhaka','019298569558','ef@gmail.com','specialist_trainer','30000','04','20');

```

![DATA INSERTION](https://i.ibb.co/0ZpzwYh/create-table-15.jpg)

---

```


36. insert into member values('40','ccc','dhaka','0125648569','ccc@gmail.com','11','b+','50','5.1','30','35','30');
37. insert into member values('41','aaa','dhaka','0125648569','aaa@gmail.com','12','b+','56','5.3','32','36','31');
38. insert into member values('42','bbb','dhaka','01256485694','bbb@gmail.com','13','0+','40','5.5','33','37','32');
39. insert into member values('43','ddd','dhaka','0115648569','ddd@gmail.com','14','a+','59','5.7','34','38','33');
40. insert into member values('44','eee','dhaka','0135648569','eee@gmail.com','02','b+','50','5.8','35','39','34');


```

![DATA INSERTION](https://i.ibb.co/k4YDM2w/create-table-16.jpg)

### [SQL](#sql)

  #### **SINGLE ROW:**
  


```
select * from owner where o_name='ROBIN'; 
```

![SINGLE ROW](https://i.ibb.co/ZfpQkxh/create-table-17.jpg)

---

```
select b_name, b_place from branch where b_id=16;
```

![SINGLE ROW](https://i.ibb.co/61YtpYc/create-table-18.jpg)

---

```
select t_id,t_name,t_category from trainer
where t_salary=15000;

```

![Table Creation](https://i.ibb.co/6YMRLyG/create-table-19.jpg)

---

  #### **GROUP FUNCTION:**
  

```
 select o_id, sum(m_salary) from manager group by o_id;
select m_id, avg(t_salary) from trainer group by m_id;

```

![GROUP FUNCTION](https://i.ibb.co/WFzXNJJ/create-table-20.jpg)

---

```
select m_id, sum(t_salary) from trainer where t_salary15000
group by m_id;

```

![GROUP FUNCTION](https://i.ibb.co/N9rMSb3/create-table-21.jpg)

---
  #### **SUB-QUERY:**
  

```
select t_name from trainer 
where t_salary(select t_salary from trainer where t_name='ab');

```

![SUB-QUERY](https://i.ibb.co/RctCr1f/create-table-22.jpg)

---

```
select m_id from manager where m_salary = (select m_salary from manager where m_id='22');
```

![SUB-QUERY](https://i.ibb.co/gJYjwgL/create-table-23.jpg)

---

```
select te_name from technician where te_salary=(select te_salary from technician where te_id='10');
```

![SUB-QUERY](https://i.ibb.co/2c0mHFL/create-table-24.jpg)

---

  #### **JOINING:**
  

```
select m.m_id,m.m_name, o.o_id, o.o_name
from manager m, owner o
where m.o_id=o.o_i

select m.m_id,m.m_name, te.te_id, te.te_name
from manager m, technician te
where m.te_id=te.te_id;

```

![JOINING](https://i.ibb.co/JBPxnGd/create-table-25.jpg)

---

```
select b.b_id,b.b_name, te.te_id, te.te_name
from branch b, technician te where b.te_id=te.te_id;

```

![JOINING](https://i.ibb.co/m8VvgrX/create-table-26.jpg)

---
  #### **VIEWS:**
  

![Table Creation](https://i.ibb.co/MhwvrxH/create-table-27.jpg)
![Table Creation](https://i.ibb.co/fQpC1hZ/create-table-28.jpg)
![Table Creation](https://i.ibb.co/gTRyJQn/create-table-29.jpg)

---

  #### **SYNONYM:**
  

![SYNONYM](https://i.ibb.co/VJMZx9x/create-table-30.jpg)
![SYNONYM](https://i.ibb.co/QHpzMCq/create-table-31.jpg)
![SYNONYM](https://i.ibb.co/9HvsG42/create-table-32.jpg)

---

### [PL/SQL](#pl-sql)

 #### **FUNCTION:**

 

1. Create a function that returns the total number of Members stored inside the GYM

```
   CREATE OR REPLACE FUNCTION totalMembers 
RETURN number IS 
   total number(2) := 0; 
BEGIN 
   SELECT count(*) into total 
   FROM  Member;  
   RETURN total; 
END;

DECLARE 
   b number(2); 
BEGIN 
   b := totalMembers(); 
   dbms_output.put_line('Total no. of  Members: ' || b); 
END;
```

![FUNCTION](https://i.ibb.co/KmF5r68/create-table-33.jpg)

---

2. Create a function that returns the total number of trainers inside the GYM.

```
CREATE OR REPLACE FUNCTION totaltrainers 
RETURN number IS 
   total number(2) := 0; 
BEGIN 
   SELECT count(*) into total 
   FROM  trainer;  
   RETURN total; 
END;

DECLARE 
   b number(2); 
BEGIN 
   b := totaltrainers(); 
   dbms_output.put_line('Total no. of  trainers: ' || b); 
END;

```

![FUNCTION](https://i.ibb.co/Y3rgV56/create-table-34.jpg)

3. Create a function that returns the total number of Managers inside the GYM.

```
CREATE OR REPLACE FUNCTION totalManagers
RETURN number IS 
   total number(2) := 0; 
BEGIN 
   SELECT count(*) into total 
   FROM  Manager;  
   RETURN total; 
END;

DECLARE 
   b number(2); 
BEGIN 
   b := totalManagers(); 
   dbms_output.put_line('Total no. of  Managers: ' || b); 
END;

```

![FUNCTION](https://i.ibb.co/mXNnRYv/create-table-35.jpg)

#### **PROCEDURE:**

1. Create a procedure to update the value of the address column of owner table from DHAKA to RANGPUR.

```
CREATE OR REPLACE PROCEDURE updateAddress(update_address IN owner.o_address%TYPE) 
IS
BEGIN
   UPDATE owner
   SET o_address ='RANGPUR'
   WHERE o_address= update_address;
END;
/
begin
updateAddress('DHAKA');
end;
/
select * from owner;

```

![PROCEDURE](https://i.ibb.co/bNBdSZG/create-table-36.jpg)

2. Create a procedure to update the value of the salary column of technician table from 5000 to 8000.

```
CREATE OR REPLACE PROCEDURE updateSalary(update_salary IN technician.te_salary%TYPE) 
IS
BEGIN
   UPDATE technician
   SET te_salary ='8000'
   WHERE te_salary= update_salary;
END;
/
begin
updateSalary('5000');
end;
/
select * from technician;

```

![PROCEDURE](https://i.ibb.co/dtcnG5F/create-table-37.jpg)

3. Create a procedure to update the value of the salary column of manager table from 20000 to 35000.

```
CREATE OR REPLACE PROCEDURE updateSalary(update_salary IN manager.m_salary%TYPE) 
IS
BEGIN
   UPDATE manager
   SET m_salary ='35000'
   WHERE m_salary= update_salary;
END;
/
begin
updateSalary('20000');
end;
/
select * from manager;

```

![PROCEDURE](https://i.ibb.co/DLNqZX4/create-table-38.jpg)

#### **RECORD:**

1. Create a record that can output the name of all the gym inside the GYM.

```
declare
gym_rec gym%rowtype;
begin
for gym_rec
in(select * from gym)
loop
dbms_output.put_line(gym_rec.g_name);
end loop;
end
 ```

![RECORD](https://i.ibb.co/ynp2XtV/create-table-39.jpg)

2. Create a record that can output the name of the owner whose id is 3.

```
declare
owner_rec owner%rowtype;
begin
select * into owner_rec from book
where o_id='3';
dbms_output.put_line(owner_rec.o_name);
end
```

![RECORD](https://i.ibb.co/jW4JGPN/create-table-40.jpg)

3.Create a record that can output the salary of the technician whose id is

```
declare
technician_rec technician%rowtype;
begin
select * into technician_rec from technician
where te_id='2';
dbms_output.put_line(technician_rec.te_salary);
end
```

![RECORD](https://i.ibb.co/9VMXT78/create-table-41.jpg)

#### **CURSOR:**

1.Create a cursor that can output the id and name of all the programs are sorted in.

```
declare
pid program.p_id%type;
pname program.p_name%type;
cursor c_program is
select p_id,p_name from program;
begin
open c_program;
loop
fetch c_program into pid,pname;
exit when c_program%notfound;
dbms_output.put_line(pid||' '||pname);
end loop;
close c_program;
end
 ```

 ![CURSOR](https://i.ibb.co/JjV49zf/create-table-42.jpg)

2.Create a cursor that can output the id and place name of all the branches are listed.

```
declare
bid branch.b_id%type;
bplace branch.b_place%type;
cursor c_branch is
select b_id,b_place from branch;
begin
open c_branch;
loop
fetch c_branch into bid,bplace;
exit when c_branch%notfound;
dbms_output.put_line(bid||' '||bplace);
end loop;
close c_branch;
end
/
```

 ![CURSOR](https://i.ibb.co/cYmkmgr/create-table-43.jpg)

3. Create a cursor that can output the name and address of all the members are listed.

```
Declare
memname member.mem_name%type;
memaddress member.mem_address%type;
cursor c_member is
select mem_name,mem_address from member;
begin
open c_member;
loop
fetch c_member into memname,memaddress;
exit when c_member%notfound;
dbms_output.put_line(memname||' '||memaddress);
end loop;
close c_member;
end
```

 ![CURSOR](https://i.ibb.co/drqTLfH/create-table-44.jpg)

#### **TRIGGER:**

1. Create a trigger in such a way that whenever a new row is inserted into the owner table an output ‘New Owner Added’ is generated.

```
CREATE OR REPLACE TRIGGER owner_added
after INSERT ON owner
FOR EACH ROW 
BEGIN 
   dbms_output.put_line('New Owner Added'); 
END; 
/ 
select * from Owner;
insert into owner values(OWNER_SEQ.nextval, 'ref','PABNA','01711585460','ref1@GMAIL.COM');
 ```

![TRIGGER](https://i.ibb.co/zXHhjct/create-table-45.jpg)

2. Create a trigger in such a way that whenever a new row is inserted into the trainer table an output ‘New Trainer Added’ is generated.

```
CREATE OR REPLACE TRIGGER  trainer_added
after INSERT ON trainer
FOR EACH ROW 
BEGIN 
   dbms_output.put_line('New trainer Added'); 
END; 
/ 
select * from trainer;
insert into trainer values(TRAINER_SEQ.nextval,'mi','BHOLA','01829996958','mi202@gmail.com','specialist_trainer','40000','05','5');
 
```

![TRIGGER](https://i.ibb.co/WGYhf7m/create-table-46.jpg)

3. Create a trigger in such a way that whenever a row is deleted from the Trainer table an output ‘A Trainer Deleted’ is generated.

```
CREATE OR REPLACE TRIGGER technician_Added
 after INSERT ON technician 
FOR EACH ROW 
BEGIN 
            dbms_output.put_line('New technician Added'); 
END; 
/ 
select * from technician;
 insert into technician values(TECH_SEQ.nextval, 'prodip','10000','01324485663','Savar', '7');
```

![TRIGGER](https://i.ibb.co/P5fwLk4/create-table-47.jpg)

#### **PACKAGE:**

1. Create a package that contains a procedure which can display the gym name of any gym whose id is passed as its parameter.

```
CREATE PACKAGE g_package AS 
   PROCEDURE display_g_name(gid gym.g_reg_number%type); 
END g_package;
/
CREATE OR REPLACE PACKAGE BODY g_package AS
   PROCEDURE display_g_name(gid gym.g_reg_number%TYPE)IS 
   gname gym.g_name%TYPE; 
   BEGIN 
      SELECT g_name INTO gname 
      FROM gym
      WHERE g_reg_number = gid; 
      dbms_output.put_line('Gym Name: '||gname); 
   END display_g_name; 
END g_package;
/
begin
g_package.display_g_name('3');
end;
 ```

![PACKAGE](https://i.ibb.co/h16G5qp/create-table-48.jpg)

2. Create a package that contains a procedure which can display the branch name of any branch whose id is passed as its parameter.

```
CREATE PACKAGE b_package AS 
   PROCEDURE display_b_name(bid branch.b_id%type); 
END b_package;
/
CREATE OR REPLACE PACKAGE BODY b_package AS
   PROCEDURE display_b_name(bid branch.b_id%TYPE)IS 
   bname branch.b_name%TYPE; 
   BEGIN 
      SELECT b_name INTO bname 
      FROM branch
      WHERE b_id = bid; 
      dbms_output.put_line('Branch Name: '||bname); 
   END display_b_name; 
END b_package;
/
begin
b_package.display_b_name('2');
end;
 ```

![PACKAGE](https://i.ibb.co/VVg7X53/create-table-49.jpg)

3. Create a package that contains a procedure which can display the book name of any book whose id is passed as its parameter.

```
CREATE PACKAGE m_package AS 
   PROCEDURE display_m_phone(mname member.mem_name%type); 
END m_package;
/
CREATE OR REPLACE PACKAGE BODY m_package AS
   PROCEDURE display_m_phone(mname member.mem_name%TYPE)IS 
   mphone member.mem_phone%TYPE; 
   BEGIN 
      SELECT mem_phone INTO mphone 
      FROM member
      WHERE mem_name = mname; 
      dbms_output.put_line('Member Phone Number: '||mphone); 
   END display_m_phone; 
END m_package;
/
begin
m_package.display_m_phone('bbb');
end;
```

![PACKAGE](https://i.ibb.co/Tr1Wz90/create-table-50.jpg)

### [CONCLUSION](#conclution)

The project has been developed in a very short period of time and all efforts have been taken so that this project is very efficient in its execution there still exists some scope of improvement in our project. The following lists some of the enhancement that can be added incorporate into the project. Application of the project can be done more attractively. Database management and all maintenance module can be updated which helps the administrator. More security measures can be taken. There are also few features which can be integrated with this system to make it more flexible. Below list shows the future points to be consider: • Real-time Chat BOT option for members and trainer, so that members can directly enquiry theirs trainer on any time through the Chat BOT. • Automated Fitness suggestion by enquiring the condition of the health. • Real time Claim Processing Bot. • Video conversation option for trainers and members. • Online payment through face recognition. • Barcode generation for membership card and using this, members can take entry to Gym. • Finger print matching for taking entry to gym. “GYM MANAGEMENT SYSTEM” is successfully designed and developed to fulfilling the necessary requirements, as identified in the requirements analysis phase, such as the system is very much user friendly, form level validation and field level validation are performing very efficiently. The old manual system was suffering from a series of drawbacks. The present project has been developed to meet the aspirations indicated in the modern age.
