Different ways to reverse a String 
1. Using loops 

def rev(s):
    str = ""
	  for i in s:
		    str = i + str
	  return str

