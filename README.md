# namegen  
A handly library I made that has a list of US names (female/male/both), and can generate random names, and random usernames.  
  
## Usage  
###Installation  
Download/Clone namegen.py into your local python directory, then bring the library into your project using:  
```python
from namegen import namegen
```  
###.names() method  
This method just returns a list of names. Here is how you use it:
```python
from namegen import namegen
#default param is ALL names for this method
allNames = namegen().names()
#males
males = namegen().names('m')
#females
females = namegen().names('f')
```  
###.random() method  
This method returns random names. Here is how you use it:  
```python
from namegen import namegen
#default param is from ALL names and count=1
a = namegen().random() #will be one random name
b = namegen().random('f') #will be one random female name
c = namegen().random('m', count=1000) #will be 1000 random male names
```


