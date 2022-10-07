class Student:
    def __init__(self):
        self._name = ''

    def getName(self):
        return self._name

    def setName(self, newName):
        self._name = newName

studente = Student()
newName = input('Inserire nome:')
studente.setName(newName)
