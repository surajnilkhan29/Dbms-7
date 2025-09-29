declare 
cursor c1 is select * from product where price<5000 for update;
rec product%ROWTYPE;
begin
open c1;
loop
fetch c1 into rec;
exit when c1%NOTFOUND;
update product 
set price=rec.price*1.10 
where current of c1;
end loop;
close c1;
commit;
dbms_output.put_line('prices update for products below 5000.');
end;
/
