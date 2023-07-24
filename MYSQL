CREATE DATABASE Student;
CREATE DATABASE Employee;
CREATE DATABASE Bank;
CREATE DATABASE Library;
CREATE DATABASE Family;
USE Student;

CREATE TABLE studentdetails (
  id INT PRIMARY KEY AUTO_INCREMENT,
  name VARCHAR(50),
  age INT,
  course VARCHAR(50),
  address VARCHAR(100)
);
USE Employee;

CREATE TABLE employeedetails (
  id INT PRIMARY KEY,
  name VARCHAR(50),
  age INT,
  department VARCHAR(50),
  salary DECIMAL(10, 2)
);
USE Bank;

CREATE TABLE bankinfo (
  id INT PRIMARY KEY,
  account_number VARCHAR(20),
  account_holder VARCHAR(50),
  balance DECIMAL(10, 2),
  branch VARCHAR(100)
);
USE Library;

CREATE TABLE bookdetails (
  id INT PRIMARY KEY,
  title VARCHAR(100),
  author VARCHAR(50),
  publication_year INT,
  genre VARCHAR(50)
);
USE Family;

CREATE TABLE familytree (
  id INT PRIMARY KEY,
  name VARCHAR(50),
  age INT,
  relationship VARCHAR(50),
  occupation VARCHAR(50)
);
INSERT INTO Student.studentdetails (id,name, age, course, address)
VALUES
  (1,'Jo', 20, 'CS', '123'),
  (2,'Ja', 22, 'ME', '456');
  SELECT * FROM Student.studentdetails;
  INSERT INTO Employee.employeedetails (id,name, age, department, salary)
VALUES
  (1,'MJ', 30, 'HR', 45000),
  (2,'ED', 28, 'Finance', 55000);
  SELECT * FROM Employee.employeedetails;
  INSERT INTO Bank.bankinfo (id,account_number, account_holder, balance, branch)
VALUES
  (1,'1234567890', 'JD', 5000.50, 'DB'),
  (2,'9876543210', 'JS', 10000.75, 'UB');
  SELECT * FROM Bank.bankinfo;
  INSERT INTO Library.bookdetails (id,title, author, publication_year, genre)
VALUES
  (1,'TGG', 'F.SF', 1925, 'F'),
  (2,'Introduction', 'JS', 2021, 'CS');
  SELECT * FROM Library.bookdetails;
  INSERT INTO Family.familytree (id,name, age, relationship, occupation)
VALUES
  (1,'JJ', 50, 'Father', 'Engineer'),
  (2,'EJ', 48, 'Mother', 'Teacher');
SELECT * FROM Family.familytree;
