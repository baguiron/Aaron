class num1(object):
 
    def __init__(self, name):
        self.name = name
 
  
    def getName(self):
        return self.name
 
  
    def isnum2(self):
        return False
 
 

class num2(num1):
 
    def isnum2(self):
        return True
 
 
emp = num1("1.") 
print(emp.getName(), emp.isnum2())
 
emp = num2("2.")  
print(emp.getName(), emp.isnum2())
