# Event Manager Made in Ruby

Download Repo and run the file in ./lib

## The point of this project:

- Integrate API
- CSV file manipulation
- Data extraction for valuable analysis
- Automatic template-fitted file creation

OUTPUT
```
NAME | ZIPCODE | DAY OF REGISTERING | HOUR OF REGISTERING
Alice   84652           Wed                 18:00
.
.
.
Hours when most people register
(sorted Hash)

Days when most people register
(sorted Hash)
```
In the output you will find the ERB template which has been modified to HTML and fitted to a custom name, as well as legislators based on a users zipcode using Google Civic API.
