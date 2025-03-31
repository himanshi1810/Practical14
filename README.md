# Practical 14
# Employee Database Setup

This project contains SQL scripts to create and populate into table: **Employee**

## 📌 Table: Employee



### **Insert Data For Task 1**
```sql
create database Practical14;
use Practical14
CREATE TABLE Employee (
    Id INT IDENTITY(1,1) PRIMARY KEY,
    Name VARCHAR(50) NOT NULL,
    DOB DATE NOT NULL,
    Age INT NULL
);
INSERT INTO Employee (Name, DOB, Age) VALUES
('John Doe', '1990-05-15', 34),
('Alice Smith', '1985-10-20', 38),
('Robert Johnson', '1992-03-12', 32),
('Emma Williams', '1994-07-25', 30),
('Michael Brown', '1988-09-17', 36),
('Sophia Miller', '1993-11-30', 31),
('David Wilson', '1986-01-10', 38),
('Olivia Moore', '1995-06-22', 29),
('James Taylor', '1991-04-05', 33),
('Emily Anderson', '1987-08-14', 37),
('Daniel Thomas', '1996-02-28', 28),
('Mia Martinez', '1989-12-03', 35),
('William Garcia', '1984-07-09', 40),
('Charlotte Lopez', '1997-05-18', 27),
('Benjamin Hernandez', '1998-09-22', 26),
('Amelia Gonzalez', '1983-06-11', 41),
('Lucas Young', '1990-11-07', 34),
('Harper Hall', '1992-08-19', 32),
('Ethan Allen', '1995-03-25', 29),
('Abigail Scott', '1981-10-15', 43),
('Henry Adams', '1982-04-12', 42),
('Evelyn Nelson', '1994-12-29', 30),
('Alexander Carter', '1986-07-02', 38),
('Ella Mitchell', '1999-01-17', 25),
('Sebastian Perez', '1980-05-08', 44),
('Avery Roberts', '1993-09-14', 31),
('Matthew Turner', '1987-11-27', 37),
('Scarlett Phillips', '1991-06-09', 33),
('Jack Campbell', '1996-10-03', 28),
('Lily Parker', '1985-02-20', 39);

```
