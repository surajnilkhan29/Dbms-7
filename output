SQL> select * from product;

no rows selected

SQL> insert into product values(101,'pen',10);

1 row created.

SQL> insert into product values(102,'notebook',50);

1 row created.

SQL> insert into product values(103,'charger',500);

1 row created.

SQL> commit;

Commit complete.

SQL> select * from product;

       PID PNAME                     PRICE
---------- -------------------- ----------
       101 pen                          10
       102 notebook                     50
       103 charger                     500

SQL> @"C:\Users\Prajakta\Desktop\Practicals\DBMS practical\pract-6 cursor\implicit.sql"

PL/SQL procedure successfully completed.

SQL> select * from product;

       PID PNAME                     PRICE
---------- -------------------- ----------
       101 pen                          11
       102 notebook                     55
       103 charger                     550
       104 phone                     20000

SQL> set serveroutput on
SQL> @"C:\Users\Prajakta\Desktop\Practicals\DBMS practical\pract-6 cursor\explicit.sql"
ID: 101, Name: pen, Price: 10
ID: 102, Name: notebook, Price: 50
ID: 103, Name: charger, Price: 500
ID: 104, Name: phone, Price: 20000

PL/SQL procedure successfully completed.


SQL> @"C:\Users\Prajakta\Desktop\Practicals\DBMS practical\pract-6 cursor\parametrized.sql"
Enter value for enter_price: 500
old   8: v_min_price := &enter_price;
new   8: v_min_price := 500;
ID: 104, Name: phone, Price: 20000

PL/SQL procedure successfully completed.

SQL> @"C:\Users\Prajakta\Desktop\Practicals\DBMS practical\pract-6 cursor\update.sql"
prices update for products below 5000.

PL/SQL procedure successfully completed.

SQL> select * from product;

       PID PNAME                     PRICE
---------- -------------------- ----------
       101 pen                          11
       102 notebook                     55
       103 charger                     550
       104 phone                     20000

SQL> commit;

Commit complete.
