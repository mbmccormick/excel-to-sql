# excel-to-sql

Generates a table, with data, on a SQL Server instance, based on information extracted from an Excel Spreadsheet.


## REQUIREMENTS

Excel to SQL has been tested on Windows Vista and Windows 7, on both 32-bit and 64-bit architectures. The application requires that the .NET Framework 3.5 be installed on the machine. Excel to SQL has only been tested with SQL Server 2005 and SQL Server 2008. Most likely, this utility will not work with MySQL, although this has not been tested. Microsoft Office does not need to be installed in order to run this tool.


## INSTALLATION

This utility is a standalone executable. There are three files that make up this utility: one executable (.EXE) and two assemblies (.DLL).


## USAGE

To use this tool, begin by starting up the executable. You should see a window with three textboxes. The first textbox lets you specify the source Excel Spreadsheet to extract the table schema and data from. The second textbox allows you to enter a connection string to the database server you wish to create this new table on. And lastly, the third textbox let's you specify a name for this new table.

When you have finished entering in your parameters, you can click the Import button to begin the import process. Upon successful completion, you will receive a confirmation dialog box to alert you of the tool's status.


## DISCLAIMER

Use this software at your own risk. While this tool has been tested thoroughly, on the above requirements, your mileage may vary. I take no responsibility for any harmful actions this tool might cause.


## LICENSE

This software, and its dependencies, are distributed free of charge and licensed under the GNU General Public License v3. For more information about this license and the terms of use of this software, please review the LICENSE.txt file.
