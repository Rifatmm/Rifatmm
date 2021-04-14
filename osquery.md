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
```
