# bash-csvio
CSV input/output in pure bash

Function parse_line() takes an input content array and a delimiter (comma default),
and populates global ${CELLS[@]} array with its content.

Function write_line() takes a delimiter and zero or more content cells, writes
content to stdout in delimited .csv format, quoting as required.

This code is mainly a port of AgilePro's beautiful Java implementation.
