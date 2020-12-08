#WHERE

- Fetch `firstname`, `lastname` and `jobtitle` from the `employees` table where job title 'Sales Rep'.
- Fetch `firstname`, `lastname` and `jobtitle` from the `employees` table where job title 'Sales Rep' and working on 'San Francisco' office.
- Fetch `firstname`, `lastname` and `jobtitle` from the `employees` table where job title 'Sales Rep' or working on 'San Francisco' office and sort in order by `officeCode` and `jobtitle`.

#DISTINCT

- Fetch `lastname` of all employees from the `employees` table.
- Fetch unique `lastname` of all employees from the `employees` table.

#DISTINCT & NULL

- Fetch all `state` from the `customers` table.
- Fetch all `state` from the `customers` table excluding NULL.


#AND

- Fetch all `customers` from the `customers` table which `country` is 'USA' and `city` is 'CA'.
- Fetch all `customers` from the `customers` table which `country` is 'USA' and `city` is 'CA' and creditlimit is greater than 100000.

#OR

- Fetch all `customers` from the `customers` table which `country` is 'USA' and `country` is 'France'.
- Fetch all `customers` from the `customers` table which `country` is 'USA' or `country` is 'France' and creditlimit is greater than 100000.

#IN

- Fetch all `customers` from the `customers` table which `country` is 'USA' and `country` is 'France'.
- Fetch all `customers` from the `customers` table which `country` is 'USA' or `country` is 'France' and creditlimit is greater than 100000.
- Fetch all `orders` which total order value (`quantityordered` * `priceeach`) is greater than 60000.

#NOT IN

- Fetch all `customers` from the `customers` table which `country` not in 'USA' and 'France'.
- Fetch all `customers` from the `customers` table which `country` is 'USA' or `country` is 'France' and creditlimit is greater than 100000.

#BETWEEN

- Fetch all `products` which `buyprice` BETWEEN 90 AND 100.
- Fetch all `products` which `buyprice` NOT BETWEEN 20 AND 100.


#LIKE (%,_)
- Fetch all `employees` which `firstname` is like 'T_m'.
- Fetch all `employees` which `lastname` is not like 'B%'.
- Fetch all `products` which `productcode` is contains '_20'.

#TABLE ALIAS

- Fetch all `oid` from the `orderdetails` table which order total (`quantityordered` * `priceeach`) is greater than 60000
- Get total order (`quantityordered` * `priceeach`) date wise.

