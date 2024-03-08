postgres db name: login DB
table name: employees


select * from "employees";

INSERT INTO employees (ID,email_address,first_name,last_name) VALUES 
(1000, 'dptest@getnada.com', 'dp', 'reddy'),
(1001, 'parul@getnada.com', 'Parul', 'Jain'),
(1002, 'harsh@getnada.com', 'Harsh', 'singh'),
(1003, 'rohith@getnada.com', 'Rohith', 'L')


Execution steps: from post man or explorer

http://localhost:8080/api/v1/employees/1000

http://localhost:8080/api/v1/employees/
