1.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails;
2.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails;
3.
SELECT MIN(OrderID) AS 'Menor'
FROM OrderDetails;
4.
SELECT MAX(OrderID) AS 'Maior'
FROM OrderDetails
WHERE Quantity > 5;
5.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails
WHERE ProductID = 3;
6.
SELECT MAX(OrderDetailID) AS 'Maior'
FROM OrderDetails
WHERE Quantity < 10;
7.
SELECT MIN(ProductID) AS 'Menor'
FROM OrderDetails;
8.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
ORDER BY ProductID ASC;
9.
SELECT MIN(OrderID) AS 'Menor'
FROM OrderDetails
ORDER BY Quantity DESC;
10.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
WHERE ProductID <> 2;
11.
SELECT MIN(OrderDetailID) AS 'Menor'
FROM OrderDetails
ORDER BY OrderID;
12.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails
WHERE OrderID > 50;
13.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
WHERE ProductID = 4
ORDER BY OrderDetailID;
14.
SELECT MIN(OrderDetailID) AS 'Menor'
FROM OrderDetails
WHERE Quantity > 15;
15.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
WHERE ProductID BETWEEN 5 AND 10;
16.
SELECT MIN(OrderID) AS 'Menor'
FROM OrderDetails
WHERE Quantity % 5 = 0;
17.
SELECT MAX(OrderDetailID) AS 'Maior'
FROM OrderDetails
ORDER BY Quantity;
18.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails
WHERE OrderID < 30;
19.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
ORDER BY ProductID DESC;
20.
SELECT MIN(ProductID) AS 'Menor'
FROM OrderDetails
WHERE Quantity > 20;
21.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
WHERE ProductID = 6
ORDER BY OrderID;
22.
SELECT MIN(OrderID) AS 'Menor'
FROM OrderDetails
ORDER BY OrderDetailID ASC;
23.
SELECT MAX(OrderDetailID) AS 'Maior'
FROM OrderDetails
WHERE ProductID > 10;
24.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails
ORDER BY OrderID;
25.
SELECT MAX(OrderID) AS 'Maior'
FROM OrderDetails
WHERE Quantity < 10;
26.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails
WHERE ProductID % 2 = 0;
27.
SELECT MAX(OrderDetailID) AS 'Maior'
FROM OrderDetails
WHERE Quantity % 3 = 0;
28.
SELECT MIN(ProductID) AS 'Menor'
FROM OrderDetails
WHERE Quantity BETWEEN 5 AND 15;
29.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
WHERE OrderID BETWEEN 50 AND 100;
30.
SELECT MIN(OrderID) AS 'Menor'
FROM OrderDetails
WHERE Quantity < 8
ORDER BY ProductID;
31.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
ORDER BY OrderDetailID;
32.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails
WHERE OrderID < 20;
33.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
WHERE ProductID < 10;
34.
SELECT MIN(OrderDetailID) AS 'Menor'
FROM OrderDetails
WHERE Quantity > 12;
35.
SELECT MAX(OrderID) AS 'Maior'
FROM OrderDetails
WHERE ProductID LIKE '2%';
36.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails
WHERE OrderID BETWEEN 10 AND 30;
37.
SELECT MAX(OrderDetailID) AS 'Maior'
FROM OrderDetails
WHERE ProductID BETWEEN 3 AND 8;
38.
SELECT MIN(OrderID) AS 'Menor'
FROM OrderDetails
ORDER BY Quantity ASC;
39.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
WHERE ProductID NOT BETWEEN 5 AND 15;
40.
SELECT MIN(OrderDetailID) AS 'Menor'
FROM OrderDetails
WHERE Quantity > 18;
41.
SELECT MAX(OrderID) AS 'Maior'
FROM OrderDetails
ORDER BY ProductID;
42.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails
WHERE ProductID < 12;
43.
SELECT MAX(OrderDetailID) AS 'Maior'
FROM OrderDetails
WHERE Quantity BETWEEN 7 AND 14;
44.
SELECT MIN(OrderID) AS 'Menor'
FROM OrderDetails
ORDER BY Quantity;
45.
SELECT MAX(Quantity) AS 'Maior'
FROM OrderDetails
WHERE OrderID > 30;
46.
SELECT MIN(OrderDetailID) AS 'Menor'
FROM OrderDetails
WHERE Quantity % 2 = 0;
47.
SELECT MAX(OrderID) AS 'Maior'
FROM OrderDetails
ORDER BY ProductID DESC;
48.
SELECT MIN(Quantity) AS 'Menor'
FROM OrderDetails
WHERE ProductID LIKE '%5';
49.
SELECT MAX(OrderDetailID) AS 'Maior'
FROM OrderDetails
WHERE Quantity < 20;
50.
SELECT MIN(OrderID) AS 'Menor'
FROM OrderDetails
WHERE Quantity > 25;

