def fix_teen(n):
  
"""Take an int value and return that value fixed for the 'teen rule'
      
     teen rule: for 13-19, but not 15 or 16, replace with 0
  
"""
  
     if n == 15 or n == 16: 
    
          return n
  
     elif n >= 13 and n <= 19: 
   
          return 0 
  
     else:
    
          return n
    


def no_teen_sum(a, b, c):
  
     a = fix_teen(a)
  
     b = fix_teen(b)
  
     c = fix_teen(c)
  
     return a+b+c 