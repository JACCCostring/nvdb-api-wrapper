# nvdb-api-wrapper
Classes Wrapper made after NVDB Les (OOP) Python Library for Reading and Writing to NVDB.

The finality of this wrapp clasess are to make it possible from QGIS to read and write to NVDB.

But for writing to NVDB i made some class wrapper calling NVDB API Les and Write endpoints and the writing said of the class make used of some xml/json templates, for writing back to NVDB once NVDB Objects are change/modified in QGIS.

Documentation still in development, since i'm not finished yet with some implementations and code refactoring.


<b>Dependencies</b>: The construction of DelvisKorriger Class depend on PyQt, because of the use of pyqtSiganl and slots.