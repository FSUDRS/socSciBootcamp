# Data Dictionary for the Social Sciences Bootcamp 

## Authors

This is the data dictionary for the `authors.csv` file.

### PersonID 

A person ID is any *unique* identifier which is used to identify the person.

### LastName

The last name field contains the person's last name at the time of publication. Pseudonymous names are suffixed with (pseud)

### FirstName 

The first name field contains the author's first name at the time of publication

### DOB

This contains the author's date of birth, recorded in ISO format (YYYY-MM-DD). Unknown authors are keyed in as `0000`

Examples:

* 2018-09-21
* 2017-09-21

### WorkRef

This contains a list of pointers to the authors works, held in the `bibliography.csv` file. The allowable data is one or more URIs, with the prefix `BIB:` coming before each URI. (e.g. `BIB:blazing` as a substitute for `bibliography.csv#blazing`) 

## Bibliography 

Data dictionary for `bibliography.csv` 

I'm editing through the browser!
