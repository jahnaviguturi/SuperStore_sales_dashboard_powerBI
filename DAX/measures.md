Total Sales = SUM(Superstore[Sales])
Total Profit = SUM(Superstore[Profit])
AvgShippingDays = DATEDIFF('Sheet1'[Order Date],'Sheet1'[Ship Date],DAY)
Total Orders = DISTINCTCOUNT(Superstore[Order ID])
