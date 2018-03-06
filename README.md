# SSIS-Project-Self-Learning

This project is designed for the SSIS starter to get familiar with control flow and data flow tasks with SSIS toolbox.
The project includes 21 packages covering from basic data load to advanced event/parameter and deployment process.

The operating platform for the project is Windows 10 + SQL Server 2016 + Visual Studio 2015(SSDT).

The Zip file is the practice dataset.
The bak file is the SQL Server database backup file. You need to restore it to your SQL Server before the practice.

## Attention: When loaded the project into visual studio, please update the connection manager according to your SQL Server instance setup (name, password, logging credential, etc).

Below is the funcation explanation of each pacakges:

## 0.Excel2SQL.dtsx
This package is to extract data from Excel sheet and then load to SQL Server table.

## 1.SQL2Excel.dtsx
This package is to extract SQL Server table data and load to Excel sheet.

## 2.Flat2SQL.dtsx
This package is to extract txt file data and load to SQL Server table.

## 3.Sorting.dtsx
This package is to load data into database while sorted the record by some columns.

## 4.Aggregate.dtsx
This package is to read the data and then calculate aggregation by different categories.

## 5.RowSampling.dtsx
This package is to practice row sample pick up by number data flow task.

## 6.PercentageSampling.dtsx
This package is to practice row sample pick up by percentage data flow task.

## 7.UnionAll.dtsx
This package is to extract two different Excel sheets and the union them together and then load into SQL Server table.

## 8.Variable.dtsx
This package is to practice how to use variable in SSIS.

## 9.Expression.dtsx
This package is to practice how to use expression in SSIS.

## 10.Conditional_Split.dtsx
This package is to split dataset into two different categories according to split conditions.

## 11.Lookup_Cache.dtsx
This package is to practice how to use lookup task and play with different cache modes.

## 12.Foreach_Loop.dtsx
This package is to practice how to use foreach loop container with File Enumerator.

## 13.Foreach_look_for_row.dtsx
This package is to practice foreach loop container with ADO Enumerator.

## 14.Foreach_item_enumerator.dtsx
This package is to practice foreach loop container with Item Enumerator.

## 15.Foreach_look_for_schema.dtsx
This package is to practice foreach loop container with ADO.NET Schema Rowset Enumerator.

## 16.Script.dtsx
This package is to practice how to use script in SSIS.

## 17.Script_Component.dtsx
This package is to practice how to use script component in SSIS.

## 18.Constraints.dtsx
This package is to practice how to play constraints in SSIS.

## 19.Events.dtsx
This package is to practice how to use events in SSIS.

## 20.Parameter_Deploy.dtsx
This package is to practice how to use parameter tab and deploy package or project into SQL Server.
