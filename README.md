# Employee-Management-System

### <a name="Description"></a>Descriptions:

Developers are often tasked with creating interfaces that make it easy for non-developers to view and interact with information stored in databases. Often these interfaces are known as **C**ontent **M**anagement **S**ystems. In this mission, I architected and built a solution for managing a company's employees using node, inquirer, and MySQL.

### <a name="Screenshots"></a>Screenshots:

![Screenshot](https://user-images.githubusercontent.com/102123208/182981680-41be19e4-d36b-4910-b1a5-4e291675ff02.png)
![gif1](https://user-images.githubusercontent.com/102123208/182981922-9fde2e91-4690-417b-8e65-c103b2c21fd0.gif)


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
