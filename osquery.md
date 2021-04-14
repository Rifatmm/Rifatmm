```sql
SELECT ProductName
FROM Products
WHERE ProductID = ANY
  (SELECT ProductID
  FROM OrderDetails
  WHERE Quantity = 10);
  
SELECT Abs(-243.5) AS AbsNum -- dkndkln dskgn dslkng kndsklng lkdsng 
SELECT PI();
PI(123);
AVG(53)
COS(2);
COUNT(ProductID)

```
