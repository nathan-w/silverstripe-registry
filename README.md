# Registry module

## Requirements

 * SilverStripe 3.0.2+
 * MySQL 5.1+ or SQL Server 2008+ database

## Installation

Copy the registry directory into your SilverStripe project, then append dev/build?flush=all
to the website URL in your browser. e.g. http://mysite.com/dev/build?flush=all

## Instructions

See `index.md` in the docs folder for more details.

## Known issues

PostgreSQL databases might have problems with searches, as queries done using `LIKE` are case sensitive.
