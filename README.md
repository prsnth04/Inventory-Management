# Inventory-Management
This inventory management is reponse to below requirement
 * Code a Python program that will read from the text file __inventory.txt__ and perform the following on the data, to prepare for presentation to your managers:
    * We’ve provided a template for you in a file named __inventory.py__, where a Shoe class should be defined.
    * Inside this file, create a class named Shoes with the following attributes:
        * country,
        * code,
        * product,
        * Cost,
        * quantity
     * Then you must define the following functions outside the class:
        * __read_shoes_data__ - This function will open the file inventory.txt and read the data from this file, then create a shoes object with this data and append this object into the shoes list. One line in this file represents data to create one object of shoes. You must use the try-except in this function for error handling. Remember to skip the first line using your code.
        * __capture_shoes__ - This function will allow a user to capture data about a shoe and use this data to create a shoe object and append this object inside the shoe list.
        * __view_all__ - This function will iterate over the shoes list and print the details of the shoes returned from the __str__ function. Optional: you can organise your data in a table format by using Python’s tabulate module.
        * __re_stock__ - This function will find the shoe object with the lowest quantity, which is the shoes that need to be re-stocked. Ask the user if they want to add this quantity of shoes and then update it. This quantity should be updated on the file for this shoe.
        * __seach_shoe__ - This function will search for a shoe from the list using the shoe code and return this object so that it will be printed.
        * __value_per_item__ - This function will calculate the total value for each item . Please keep the formula for value in mind; value = cost * quantity. Print this information on the console for all the shoes.
        * __highest_qty__ - Write code to determine the product with the highest quantity and print this shoe as being for sale.
