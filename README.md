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
###.randomUsername() method  
This method literally returns random usernames. Here is how you use it:  
```python
from namegen import namegen
a = namegen().randomUsername() #returns one random username
b = namegen().randomUsername('f') #returns one random female username
c = namegen().randomUsername(count=10) #returns 10 random usernames
print(c)
#output for the print: ['Kerianne230', 'Kristian457', 'Darth518', 'Sauncho668', 'Antone170', 'Terri542', 'Robyn839', 'Graeme25', 'Elizabeth380', 'Ninetta409']
```


