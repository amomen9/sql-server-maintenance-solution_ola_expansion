# SQL Server Maintenance Solution
[![licence badge]][licence]
<!-- [![stars badge]][stars] -->
<!-- [![forks badge]][forks] -->
<!-- [![issues badge]][issues] -->
<!-- [![bug report badge]][bug report]-->
<!-- [![feature request badge]][feature request] -->

## Getting Started

Download [MaintenanceSolution.sql](/MaintenanceSolution.sql). This script creates all the objects and jobs that you need.

Download original repository's scripts by <a href="https://ola.hallengren.com/contact.html">Ola Hallengren</a> at [https://ola.hallengren.com/contact.html(https://ola.hallengren.com/downloads.html)](https://github.com/olahallengren/sql-server-maintenance-solution)


You can also download the objects as separate scripts:
 - [DatabaseBackup](/DatabaseBackup.sql): SQL Server Backup
 - [DatabaseIntegrityCheck](/DatabaseIntegrityCheck.sql): SQL Server Integrity Check
 - [IndexOptimize](/IndexOptimize.sql): SQL Server Index and Statistics Maintenance
 - [CommandExecute](/CommandExecute.sql): Stored procedure to execute and log commands
 - [CommandLog](/CommandLog.sql): Table to log commands

Note that you always need CommandExecute. DatabaseBackup, DatabaseIntegrityCheck, and IndexOptimize are using it.
You need CommandLog if you are going to use the option to log commands to a table.

Supported versions: SQL Server 2019, SQL Server 2022, Azure SQL Database, and Azure SQL Managed Instance. </br>
                    SQL Server 2008, SQL Server 2008 R2, SQL Server 2012, SQL Server 2014, SQL Server 2016, SQL Server 2017 can be supported with slight modification of the code. Please let me know if you need this project for these versions.

## Documentation

<ul>
<li>Backup: https://ola.hallengren.com/sql-server-backup.html</li>
<li>Integrity Check: https://ola.hallengren.com/sql-server-integrity-check.html</li>
<li>Index and Statistics Maintenance: https://ola.hallengren.com/sql-server-index-and-statistics-maintenance.html</li>
</ul>

[licence badge]:https://img.shields.io/badge/license-MIT-blue.svg
<!--[stars badge]:https://img.shields.io/github/stars/amomen9/sql-server-maintenance-solution.svg -->
<!-- [forks badge]:https://img.shields.io/github/forks/amomen9/sql-server-maintenance-solution_ola_expansion.svg -->
[issues badge]:https://img.shields.io/github/issues/amomen9/sql-server-maintenance-solution.svg
[bug report badge]:https://img.shields.io/github/issues/amomen9/sql-server-maintenance-solution/Bug%20Report.svg
[feature request badge]:https://img.shields.io/github/amomen9/olahallengren/sql-server-maintenance-solution/Feature%20Request.svg

[licence]:https://github.com/amomen9/sql-server-maintenance-solution/blob/master/LICENSE
[stars]:https://github.com/amomen9/sql-server-maintenance-solution/stargazers
[forks]:https://github.com/amomen9/sql-server-maintenance-solution/network
[issues]:https://github.com/amomen9/sql-server-maintenance-solution/issues
[bug report]:https://github.com/amomen9/sql-server-maintenance-solution/issues?q=is%3Aopen+is%3Aissue+label%3A%22Bug+Report%22
[feature request]:https://github.com/amomen9/sql-server-maintenance-solution/issues?q=is%3Aopen+is%3Aissue+label%3A%22Feature+Request%22
