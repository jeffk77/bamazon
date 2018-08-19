# Bamazon App

## Description

This is a straight-forward command line store app, utilizing the npm [inquirer] package and the MySQL database backend, which also utilizes the npm [mysql] package. The application has two modes, customer, and manager.

### Customer Interface

The customer mode, allows the user to view the inventory store items, with a simple dataset for each one: item ID, description, department and price. The user can then purchase one of the items as long as the item is in stock. If it is not, the app will prompt the user to modify their order.

To run the customer interface please follow the steps below:

	git clone git@github.com:jeffk77/bamazon.git
	cd bamazon
	npm install
	node bamazonCustomer.js

### Manager Interace

The manager interface presents a list of four options, as below. 

	? Please select an option: (Use arrow keys)
	❯ View Products for Sale 
	  View Low Inventory 
	  Add to Inventory 
	  Add New Product
	  
To run the manager interface please follow the steps below:

	git clone git@github.com:jeffk77/bamazon.git
	cd bamazon
	npm install
	node bamazonManager.js