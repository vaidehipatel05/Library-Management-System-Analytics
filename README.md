# Library-Management-System-Analytics
To analyze and visualize data from a library management system using Snowflake  Data Platform, incorporating multiple fact and dimension tables for comprehensive insights.

Schema: Star schema with multiple fact and dimension tables:
Fact Tables: 
checkoutsfact (checkoutid, bookid, borrowerid, checkoutdate, returndate)
finepaymentsfact (paymentid, checkoutid, paymentdate, amount)

Dimension Tables: 
bookdim (bookid, title, author, genre, publishyear)
borrowerdim (bor_index, borrowerid, name, address)
librarybranchdim (branchid, branchname, location)
datedim (dateid, day, month, year, weekday)


