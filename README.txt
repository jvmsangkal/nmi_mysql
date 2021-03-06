==========
nmi_mysql
==========

A simple and intuative mysql client wrapper for pymysql.
Ideal for performing simple and raw operations in mysql.

**Installation:**
*pip install nmi_mysql*

**Dependencies**
    * Python 3.4+
    * pymysql (http://www.pymysql.org/)

**Change Log**
    * v.0.63
	* removed unecessary error message upon close
	* raise error instead of returning None
    * v.0.62
        * returns affected rows when executing insert and update
        * defaults the return type for select to lists
    * v.0.61
        * fixed logging issues
    * v.0.58
        * added execute many
        * verified test for logger
    * v.0.57
        * fixed bug on type checking
    * v.0.56
        * updated base code for connection
        * added new docs
    * v.0.55
        * fixed null being converted to string
        * updated docs for examples

For full documentation and usage:
https://github.com/pprmint/nmi_mysql/blob/master/README.md 
