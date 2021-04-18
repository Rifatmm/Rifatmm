```sql
SELECT ProductName
FROM Products
WHERE ProductID = ANY
  (SELECT ProductID
  FROM OrderDetails
  WHERE Quantity = 10);
  
SELECT Abs(-243.5) AS AbsNum -- dkndkln dskgn dslkng kndsklng lkdsng 
SELECT PI();

SELECT AVG(Price) AS AveragePrice FROM Products;
COS(2);
COUNT(ProductID)
SELECT PI();
SELECT COS(2);
SELECT ATAN(2.5);
SELECT FLOOR(25.75) AS FloorValue;
SELECT LOG(2);
SELECT CEILING(25.75) AS CeilValue;
SELECT COUNT(ProductID) AS NumberOfProducts FROM Products;
/* efefmeklfel;kfmew

efewfepowfewofkewofke
efowefewofjpeowfjew
ewfkewpfkewfpokew
*/

SELECT u.username,
       p.pid,
       p.name,
       pos.local_address,
       pos.local_port,
       p.path,
       p.cmdline,
       pos.remote_address,
       pos.remote_port
  FROM processes as p
  JOIN users as u
    on u.uid=p.uid
  JOIN process_open_sockets as pos
    on pos.pid=p.pid
 WHERE pos.remote_port !='0' AND pos.remote_address != '127.0.0.1'
 limit 1000;
 
 SELECT DISTINCT 
       process.name, 
       listening.port, 
       listening.address, 
       process.pid 
  FROM processes.path AS process 
  JOIN listening_ports AS listening 
    ON process.pid = listening.pid 
 WHERE address != '127.0.0.1';
 
SELECT ProductName
FROM Products
WHERE ProductID = ANY (SELECT ProductID FROM OrderDetails WHERE Quantity = 10);
SELECT CEILING(25.75) AS CeilValue;
SELECT MAX(Price) AS LargestPrice FROM Products;
SELECT MIN(Price) AS SmallestPrice FROM Products;
SELECT ROUND(235.415, 2) AS RoundValue;
```
