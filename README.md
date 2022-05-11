# Chemistry_Calculator_26027
Install needed libarys with:
> pip3 install chemcalculator

> pip3 install chempy pytest


# GENERAL DEBUGGING NOTES
### Errors
This error usually means that the input to the function compute_mass(), has a mispelled element. Check if there are any capital letters that should be small, or other way around.
> ValueError: Chemical compound contains element not in periodic table.


### DECIMALS AND SCIENTIFIC NOTATION
The following function converts a number to scientific notation
> format(yield_moles,'.1E')

The '.1E' argument can be changed, to provide more decimal values.
E.g. '.1E' provides 1 decimal accuracy: 2.2E+05
E.g. '.2E' provides 1 decimal accuracy: 2.24E+05¨
And so on...


### TODO
Chapter 1
- [x] Støkometri, reaktions balancing og yield
- [] Confirm above works

Chapter 2
- [x] Redox
- [] Confirm above works
- [] Opløselighed
- [] Confirm above works
- [] Udfældnings reaktioner
- [] Confirm above works

Chapter 3
...