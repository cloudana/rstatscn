## rstatscn 1.1.3

### minor update

* import the functions from httr and jsonlite

## rstatscn 1.1.2

### minor update

* do not run the tests requiring the internet resources 

## rstatscn 1.1.1

### bug fixes

* for some pages, the row name is duplicated. need to set the row name prefix to fix the issue.
to set the row name prefix , use the function statscnRowNamePrefix() , to unset it
call statscnRowNamePrefix(NULL)

## rstatscn 1.0.2

### bug fixes

* It requires the httr 1.1.0 to run. Increase the httr version in DESCRIPTION

## rstatscn 1.0.1

### bug fixes

* the http status check. `success` -> `Success`, which should be changed recently

