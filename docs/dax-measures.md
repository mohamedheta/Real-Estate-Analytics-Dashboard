# DAX Measures Documentation

## Key Measures

```DAX
Total Sales = SUM(Sales_New[SalePrice])

Total Properties = COUNTROWS(Properties)

Clients with Sales = DISTINCTCOUNT(Sales_New[ClientID])

Clients with Visits = DISTINCTCOUNT(Visits[ClientID])

Conversion Rate = DIVIDE([Clients with Sales],[Clients with Visits],0) * 100

Avg Price per m2 = AVERAGE(Properties[Price per meter])

Avg Days on Market = AVERAGEX(Sales_New, Sales_New[Days on Market])
```
