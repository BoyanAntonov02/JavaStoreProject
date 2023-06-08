# JavaStoreProject
University project

========TASK========
Assignment: The assignment solution includes modeling and implementation of the charging process
and selling goods in a shop. The store is loaded with goods that will be sold. Each commodity is defined by
identification number, name, unit delivery price and category (food and non-food goods). In addition,
each product has an expiration date. The selling price of the goods is determined as follows:
Food and non-food goods have a different % markup, which is determined in the store. If the expiration date is approaching, 
ie. less than a given number of days until its expiry, the selling price of the goods is reduced by a certain %. The number of days until
expiration and % discount are different for each store. Expired goods fitness should not be sold.
The store is staffed by cashiers who have a name, an ID number and a specific monthly salary. 
One cashier can work at each of the checkouts in the store. Any cashier can works at a different checkout. At each of the cash registers in the store, 
the cashiers mark the goods that customers want to buy. If the customers have enough money to buy the goods,
their cashiers sell them and issue receipts.When selling a product, check if there is enough of it available. If
quantity is not enough to throw an exception. The exception to indicate from which commodity what quantity is missing to complete the purchase.
The receipt must contain at least the following information: serial number, cashier who issues the receipt, date and time of issuance of the receipt,
list of goods that are included in the receipt including their price and quantity and the total value to be paid by the customer.
It is necessary to store the total number of receipts issued to date and the total amount that is generated as turnover on issuance. 
When issuing the receipt a note needs its contents to be displayed and saved to a file. Any receipt should be kept in a separate file with a file name 
that contains the sequence number of the issued receipt. It should be possible to check how many have been issuedreceipts at the moment. 
The information in the file where the receipt is recorded it must be readable.
The project must use exception handling approaches and implement unit tests.
