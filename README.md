# JMC-ID

This is my Python ID Library, that adds an ID datatype for Python. 
*IT IS NOT A FULLY FUNCTIONAL LIBRARY, JUST MY ATTEMPT AT ONE*

## ID DATATYPES: 

The ID datatype is 8 integers


## USAGE

`id.py` has 2 Uses, to define and manipulate the ID Datatype, and the ability to Generate Custom IDs for usage.

### To Make an ID:

Import in the Type: 

`from id import ID`
and then define it like this:
`{var-name} = ID('{id-number}')`
The ID type requires it to be cast from a String, and to contain only Integers.

An Example Code could look like:
```python
from id import ID
guestID = ID('01234567')
print(guestID)
```

### To Generate a Random ID:

Import both the Type, and the Generation Function:
`from id import ID, generateID`

Then assign the output of the function to a variable 

`guestID = generateID()`

and use to your will

```python
print(type(guestID))
print(guestID)```


An Example would be:
```python 
from id import ID, generateID

guestID = generateID()
print(guestID)
```
