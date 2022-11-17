class Base(object):
 
    
    def __init__(self, name):
        self.name = name
 
    
    def getName(self):
        return self.name
 
 

class Child(Base):
 
    
    def __init__(self, name, age):
        Base.__init__(self, name)
        self.age = age
 
    
    def getAge(self):
        return self.age
 

 
 
class Father(Child):
 
    
    def __init__(self, name, age, hobby):
        Child.__init__(self, name, age)
        self.hobby = hobby
 
  
    def getAddress(self):
        return self.hobby
 

g = Father("Jordan",23, "Basketball")
print(g.getName(), g.getAge(), g.getAddress())
