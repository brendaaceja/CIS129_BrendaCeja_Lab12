# CIS129_BrendaCeja_Lab12
class Pet:
    def __init__(self):
        self.name = ""
        self.type = ""
        self.age = 0

    def setName(self, n):
        self.name = n

    def setType(self, t):
        self.type = t

    def setAge(self, a):
        self.age = a

    def getName(self):
        return self.name

    def getType(self):
        return self.type

    def getAge(self):
        return self.age

def main():
    # Declare the input variables
    inputName = input("Enter a pet name: ")
    inputType = input("Enter a pet type: ")
    inputAge = int(input("Enter a pet age: "))

    # Create the Pet object
    Animal = Pet()

    # Set values for the pet
    Animal.setName(inputName)
    Animal.setType(inputType)
    Animal.setAge(inputAge)

    # Show values for this pet
    print("The pet name is", Animal.getName())
    print("The pet type is", Animal.getType())
    print("The pet age is", Animal.getAge())

if __name__ == "__main__":
    main()
