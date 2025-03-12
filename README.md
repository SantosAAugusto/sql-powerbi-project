# Description
This project aims to guide how to connect an SQLite Database to Power BI.
This is necessary because Power BI does not natively support direct connections to SQLite.
Therefore, the installation of an ODBC driver and the connection between the driver and the database are required.
Afterward, it will be possible to connect the SQLite database through the ODBC option in Power BI Desktop.
Once the connection is established, the tables present in the database will be available in Power BI, and the dashboard can be built.

## Driver Installation
The ODBC Driver can be found in the following link: [ODBC Driver](https://www.devart.com/odbc/sqlite/).

Notice: there's a free trial. In case you or your company want to use for a long period, you have to pay for it.
For our explanation, there's no need to pay, but you will only have 30 days of using.

## Driver Configuration on the Operating System
After installation, you will need to open the 'ODBC Data Sources' on your computer and add the newly installed driver.
When you click 'Add', in the window that opens, give the driver a name of your choice and specify the path where your SQLite Database is located.

## Connecting the Database into Power BI
First, open a Power BI project. After, click in 'Get data' and select 'ODBC' option.
Then, in the next window, select the Driver you installed, which now have a Database connection (your SQLite Database).
