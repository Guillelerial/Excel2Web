# Excel2Web
Enhanced excel table on wordpress based web.

## Description of work
The idea is to populate an HTML table representing products of a store with information from an excel file.
This table will have, at least, the following info:
Name, Supplier, Origen, Price per unit, Unit base

We then want to append additional columns for the user to type in:
Quantity, Comments


There will be a cart summary window where selected items will appear along with the aggregated cost.


This page will also have a section to provide name of customer, city, CP, address, and comments. This fileds, must be marked as mandatory so they have to be filled before the customer can send the order.



## How to Run 

### Start php server with
cd path_to_repo
php -S localhost:8000

Open any file you want to check on your browser of choice
Check <file.php> --> http://localhost:8000/<path_to_file>/<file.php>
