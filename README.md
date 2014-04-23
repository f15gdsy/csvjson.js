# csvjson.js

Based on Aaron Snoswell's implementation of the CSV to JSON, I added the "emptyValue" as an argument option for the csv2json function. 
Its purpose is to give values to empty slot in the csv file other than 0.


csvjson.js is a simple standalone JavaScript file to convert between CSV data
and JSON objects. It is released under the MIT License and fits under 1kb when
minified (even less when gzipped).

At the moment it doesn't have any support for parsing JSON strings, only JSON
style objects (you'll need to use JSON.js to work around that).

The demo website shows how to use it.

Author: Aaron Snoswell (@aaronsnoswell, elucidatedbiany.com)
