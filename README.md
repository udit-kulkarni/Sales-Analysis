**Sales for the year 2017**<br>
**SELECT SUM(sales.transactions.sales_amount) FROM sales.transactions INNER JOIN sales.date ON sales.transactions.order_date=sales.date.date where sales.date.year=2017;**<br>
![2017](https://user-images.githubusercontent.com/84023687/132974471-8d1168ec-dd47-465d-8e5a-1edcae949256.PNG)<br>

**Sales for the year 2018**<br>
**SELECT SUM(sales.transactions.sales_amount) FROM sales.transactions INNER JOIN sales.date ON sales.transactions.order_date=sales.date.date where sales.date.year=2018;**<br>
![2018](https://user-images.githubusercontent.com/84023687/133241362-34814048-62f0-4a24-930c-43bc194a647e.PNG)

**Sales for the year 2019**<br>
**SELECT SUM(sales.transactions.sales_amount) FROM sales.transactions INNER JOIN sales.date ON sales.transactions.order_date=sales.date.date where sales.date.year=2019;**<br>
![2019](https://user-images.githubusercontent.com/84023687/133241597-e47e818a-458e-4563-b749-68a0031f1195.PNG)


**Sales for the year 2020**<br>
**SELECT SUM(sales.transactions.sales_amount) FROM sales.transactions INNER JOIN sales.date ON sales.transactions.order_date=sales.date.date where sales.date.year=2020;**<br>
![2020](https://user-images.githubusercontent.com/84023687/133241610-adb2ed61-8d86-4f3d-8401-7469469d8293.PNG)<br>

**Star Schema**
![star_schema](https://user-images.githubusercontent.com/84023687/133241885-dd891c14-6f22-4325-b075-9b52e1040122.PNG)<br>


**DATA CLEANING and ETL**<br><br><br>
**ISSUES**<br>
![currency_issue](https://user-images.githubusercontent.com/84023687/133242076-a51e5a2f-87ab-4957-bb1f-3f8dc7e085a9.PNG)<br>
We Use the following command to convert USD to INR and convert all of the sales into one currency by normalising the amount<br>
![normalised-amount](https://user-images.githubusercontent.com/84023687/133242169-8ba8100e-7a46-44ca-8a2c-f9fd0c68ae5a.PNG)<br>

Sales cannot be -1 <br>
![data-cleaning_to_do](https://user-images.githubusercontent.com/84023687/133242346-9c747581-9ff8-4ebe-ae3a-1d02a8bdd312.PNG)<br>
![market_data_clearning_to_do](https://user-images.githubusercontent.com/84023687/133242362-84cb1733-2edb-4b58-8066-0c4aca242ef1.PNG)<br><br><br>


**Dashboard**
![Dashboard 1](https://user-images.githubusercontent.com/84023687/133242771-3dd20c41-d594-46b2-a3a8-ccdced30d475.png)<br><br>


https://user-images.githubusercontent.com/84023687/133244275-c65a200f-531b-49a0-b5c4-3d3ffd607641.mp4















