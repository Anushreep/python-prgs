Different ways to reverse a String 
1. Using loops 

def rev(s):
    str = ""
	  for i in s:
		    str = i + str
	  return str



2. Using Recursion

def revs(s):
	if len(s) == 0:
		return s
	else:
		return reverse(s[1:0]) + s[0]

	
>>> rev("anushree")
'eerhsuna'

3. Using slicing method 

def rev(s):
	s = s[::-1]
	return s

>>> rev("anushree")
'eerhsuna'

