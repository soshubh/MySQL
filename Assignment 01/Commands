-- a) Create a database and tables inside the database. Use appropriate data type and
-- size.

-- Customer table
create table Customer(
 cust_id int,
 cust_name text
);

-- item table
create table Item(
 item_id int,
 item_name text,
 price int
);

-- sale table
create table Sale(
 bill_no int,
 bill_date date,
 cust_id int,
 item_id int,
 qty_sold int
);


-- b) Show the table description. 
DESCRIBE Customer;
DESCRIBE Item;
DESCRIBE Sale;


-- c) Insert around 10 records in each of the tables. 
-- Customer tables Insertion
Insert into Customer values(001,"Raambabu");
Insert into Customer values(002,"Mahajan");
Insert into Customer values(003,"Marlega");
Insert into Customer values(004,"Bachhan");
Insert into Customer values(005,"CuteBoy69");
Insert into Customer values(006,"Papa007");
Insert into Customer values(007,"SimpGod");
Insert into Customer values(008,"Devdash");
Insert into Customer values(009,"Durex");
Insert into Customer values(0010,"BsAbNi");

-- Item tables Insertion
Insert into Item values(01,"Samosa",5);
Insert into Item values(02,"ColdDrink",40);
Insert into Item values(03,"Chhola",200);
Insert into Item values(04,"Butter",10);
Insert into Item values(05,"Paneer",103);
Insert into Item values(06,"Aloo",37);
Insert into Item values(07,"Coffee",20);
Insert into Item values(08,"Chocolate",40);
Insert into Item values(09,"Dettol",321);
Insert into Item values(010,"Pen",7);

-- Sale table Insertion
-- Date - 'YYYY-MM-DD' 
Insert into Sale values(1,'2020-01-02',002,05,12);
Insert into Sale values(2,'2020-01-05',001,02,20);
Insert into Sale values(3,'2020-01-05',001,03,2);
Insert into Sale values(4,'2020-01-06',002,010,32);
Insert into Sale values(5,'2020-01-07',006,09,15);
Insert into Sale values(6,CURDATE(),002,08,65);
Insert into Sale values(7,'2020-01-09',007,01,45);
Insert into Sale values(8,'2020-01-10',003,07,25);
Insert into Sale values(9,CURDATE(),008,03,23);
Insert into Sale values(10,CURDATE(),005,06,5);

-- d) Show all the records of the table inserted. 
select * from Customer;
select * from Item;
select * from Sale;

-- 2) Item whose price is more then 100
SELECT * FROM Item WHERE price>100;

-- 3) Select bill_no and Customer id of todays Sale
SELECT bill_no,cust_id FROM Sale WHERE bill_date=curdate();

-- 4) Print Customer name with id 002
SELECT cust_name FROM Customer WHERE cust_id=002;

-- 5) Delete records of the Customer with id 005
  DELETE FROM Customer  WHERE cust_id=005;\
  
  SELECT * FROM Customer;
