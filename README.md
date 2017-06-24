# Simple Chama Bookkeeping

The simple chama bookkeeping is based on mangoO Microfinance Management system - a lightweight, yet powerful software solution for small microfinance institutions. It uses web technologies like PHP, MySQL, JavaScript (with jQuery), and CSS. 

## Features
- Customer management
- Share account management
- Savings account management
- Loan management
- Employee management
- Reporting
- Accounting

## Installation
Requires a PHP-capable webserver and a MySQL database. For testing purposes, using XAMPP is recommended.

To connect to the test database included in this repository (sunbird_test.sql), the required configuration is as follows.
Server: 127.0.0.1 /
Database user: root /
Database password: '' (empty password).
These are the current default settings included in ./config/config.php. They should only be used for test installations. Make sure to change database user and password for any productive environment! It is also highly recommended to change the password pepper in each new installation by editing ./config/pepper.php.

The default login for the program GUI is:
Username: admin
Password: password

## Licence
This software is licensed under the GNU General Public License 3.0, a copy of which can be found in the LICENSE file.
