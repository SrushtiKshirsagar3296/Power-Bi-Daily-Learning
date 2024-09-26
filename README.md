# Power-Bi-Daily-Learning
# 1) THESE ARE THE TABLES THAT I HAVE IMPORTED FROM A DATASET CONTAINING TABLE NAME AS table_orders AND table_customers
![Screenshot 2024-09-26 211505](https://github.com/user-attachments/assets/ae68e1a2-c269-4e71-b464-f2c0e686de90)
![Screenshot 2024-09-26 211512](https://github.com/user-attachments/assets/5275aa51-29ee-4d74-b40e-a0c3cfed42d2)

# Report view
1)Report view is the area  to create visuals, Table view helps to check and modify tables,Model view helps one to create data model 
![Screenshot 2024-09-26 211637](https://github.com/user-attachments/assets/aef31af3-174d-4d85-af0d-1e36e8abe60c)
2)This is the exactly as report view but in mobile layout format
![Screenshot 2024-09-26 211707](https://github.com/user-attachments/assets/0cbeff54-092c-447d-8e61-f34cf11823a6)
# Diagram View
1)This is the diagram view ,we can define relationships between tables by connecting the common column , thus defining a relationship between the whole dataset , so that we can acess , modify it as per our requirements
![Screenshot 2024-09-26 211543](https://github.com/user-attachments/assets/f1ee4b65-21ff-4493-918b-823be4c58b42)
# Merging And Appending
1)merging allows us to combine two tables vertically based on the common column, here I have merged both the colums , and extracted customer_name from table_customers and imported it to table_orders
![Screenshot 2024-09-26 215614](https://github.com/user-attachments/assets/95fb1ce8-ca85-4adc-87cd-7928eceed6c5)
2)Appending allows us to combine two tables Horizontally based on the column names and type.
Here if there are additional customers name that I have to add , I will create a new table called customer_ising , and then I'll append it with the table_customer, having common attribute Cust_iD
![Screenshot 2024-09-26 215622](https://github.com/user-attachments/assets/c1e33df5-592a-4492-93e0-73639278857c)
# Insights
1) These are the virtual representation of the data set , it includes the sum of the bill amount by the customer, sum of the quantity of food oordered on the respective dates, total order value, sum of the large order value (>500 $), min order value ,max order value, count of the order, average order
2) I Used DAX formulas such as SUM , CALCULATE, DIVIDE, MIN, MAX
![Screenshot 2024-09-27 002645](https://github.com/user-attachments/assets/b28a5a69-5906-4dd4-8400-339af20a9ba9)

3) These aare the insights for Cust_Id 2
![Screenshot 2024-09-27 002851](https://github.com/user-attachments/assets/44b95876-f3de-445f-9222-22378d07b662)





