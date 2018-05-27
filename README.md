# OTP-in-Python
Here I have uploaded a program that creates a OTP in Python.

## Step-1

import the library named "random" by

from random import *

Note: Down bellow I will explain diffrence that has on above line and just "import random"

## Step-2

Now write the code: _print(randint(0,9),randint(0,9),randint(0,9),sep="")_

**randint(0.9):** Here you get a random integer between your given range, in our case it's form 0 to 9

**sep="":** It removes the spaces between the numbers

And all the random integers are wraped in **print()** which will print it.

## Step-3

Run it!

If running in comand prompt then to go the location (directory) and then write "python _your file name_.py

If running in any editor having compiler then just find run button and just run it!!


## Diffrence between _from random import *_ and _import random_

### from random import *

This method imports the random library in your namespace and you don't need to insert random._methods_ example:

from random import *

print(randint(0,9),randint(0,9),randint(0,9))

Output: 0 5 9

Note: Usally this approach not preferred.

### import random

This is the preferred approach of importing any library and the example is bellow:

import random

print(random.randint(0.9),random.randint(0.9),random.randint(0.9))

Output: 1 8 2
