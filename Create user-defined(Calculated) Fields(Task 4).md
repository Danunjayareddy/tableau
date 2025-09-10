Create User-Defined (Calculated) Fields

## Steps  
1. Data Pane → Right-click → Create → **Calculated Field**  
2. Enter Name (e.g., Profit Margin)  
3. Write formula → Click **OK**  

---

## Examples  

### Math  
`[Profit] / [Sales]`  

### String  
`UPPER([Region])`  

### Date  
`DATEDIFF('day', [Order Date], [Ship Date])`  

### Logical  
```tableau
IF [Discount] > 0.2 THEN "High Discount" 
ELSEIF [Discount] > 0.1 THEN "Medium Discount" 
ELSE "Low Discount" END
