# Classwork3-28
#use classes to manage multiple data attributes

class Character():
    # this sets up the variables in the object
    def __init__(self):
        self.name=''
        self.sex=''
        self.max_hit_point=''
        self.current_hit_points=''
        self.armor_amount=''

# create an instance of this class
main_char = Character()
main_char.name = 'Sam'
main_char.sex = 'male'
main_char.max_hit_points = 50
main_char.max_current_hit_points = 50
main_char.armor_amount = 8

print('The main character of the game is', main_char.name)
print('The maximum amount of points is', main_char.max_hit_points)

class Address():
    # this holds all the field for a mailling address
    def __init_(self):
    # set up address fields
        self.name =''
        self.line1=''
        self.line2=''
        self.state=''
        self.city=''
        self.zip=''

home_address = Address()
home_address.name='Jane Smith'
home_address.line1='102 North Street'
home_address.line2='Carver CS Building'
home_address.city='New York City'
home_address.state='NY'
home_address.zip='10010'

vacation_home_address = Address()
vacation_address.name = 'Jane.Smith'
vacation_home_address.line1= '1722 Main Street'
vacation_home_address.line2= 'Apartment 4'
vacation_home_address.city= 'Panama City Beach'
vacation_home_address.state= 'Fl'
vacation_home_address.zip= '32407'

print('My vacation address is in', vacation_home_address.city)

# create a class reference

rental_home = vacation_home_address
rental_home.city = "San Francisco"
rental_home.state = 'CA'
rental_home.zip = '20001'
print("My rental house is in", rental_home.city)

