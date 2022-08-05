# Employee-Management-System

### <a name="Description"></a>Descriptions:

Developers are often tasked with creating interfaces that make it easy for non-developers to view and interact with information stored in databases. Often these interfaces are known as **C**ontent **M**anagement **S**ystems. In this mission, I architected and built a solution for managing a company's employees using node, inquirer, and MySQL.

### <a name="Screenshots"></a>Screenshots:



### <a name="Installation"></a>Installations:

I created the Employee Management System with npm packages: **MySQL**, **Node**, **Inquirer**, and **console.table** design pattern.


### <a name="Usage"></a>Usages:

Designed the following database schema containing three tables:

- **Department**:

  - **id**
  - **name**

- **Role**:

  - **id**
  - **title**
  - **salary**
  - **department_id**

- **Employee**:

  - **id**
  - **first_name**
  - **last_name**
  - **role_id**
  - **manager_id**