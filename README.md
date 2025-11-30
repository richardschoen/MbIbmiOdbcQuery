# IBM i ODBC Query Helper Utility
This is a FREE IBM i app provided by MobiGoGo LLC (https://www.mobigogo.net)

The app allows developers to run one or more interactive IBM i ODBC queries in a MDI (Multi-Document) Window in a MS Windows environment. 

I plan to use it when I want to run multiple DB2 SQL queries and have them in a single UI with multiple result windows open. 
I don't plan to use this instead of ACS Run SQL Scripts, but will use it to augment when I need a better way to compare result sets together. 

This app is a self-contained DotNet 10 app so it runs on Windows only. 

Simply unzip to a directory and run the app ```MbibmiOdbcQuery```.   
(Suggested location: ```C:\Program Files\MbIbmiOdbcQuery``` or ```C:\MbIbmiOdbcQuery```)

If you have questions or problems with the app feel or a feature request free to open an issue.

<img width="787" height="587" alt="image" src="https://github.com/user-attachments/assets/908b3378-30eb-4b73-86c4-7a1acb2e098c" />

## Features
- Multi document interface. Can have one or more windows open to a single or multiple IBM i systems.
- Can duplicate window for already running connection along with SQL statement list for convenience.
- Can open/save SQL files.
- Highlight individual statements to run queries if multiple stored in an SQL file.
- Logs all SQL statements for easy recall and tracking when you're running many queries. (I always lose track of my statement history.)
- Store one or more system in the system list in the settings file.
- Run record queries to result sets.
- Perform action queries such as INSERT, UPDATE, DELETE.

## Pre-requisites
You need a Windows PC.  So far only tested on Windows 11 x86, but should rubn on Windows 11 ARM. Should also thoeretically run on Windows 10 or even Windows 7 if your machine if that far back.

You need to install the IBM i Access Windows package which contains the ODBC driver. This app uses the IBM i Access ODBC Driver.

