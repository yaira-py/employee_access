class Employee:
    def __init__(self,name,access_level):
        self.name=name
        self.access_level=access_level

class Security:
    def __init__(self):
     self.clearance=3
     self.access_log=[]

    def Swip_badge(self,employee):
        if employee.access_level>= self.clearance :
          self.access_log.append(employee)
          print(f'{employee.name} access granted')

        else:
            print(f'{employee.name} access denied')



gate=Security()
user_name=input('enter ur name: ')
user_level=input('enter employee access level(1-3): ')
try:
   user_level=int(user_level)
   emp=Employee(user_name,user_level)
   gate.Swip_badge(emp)


except ValueError:
   print('pls enter a whole number')

