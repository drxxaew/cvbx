class Human :
    name = ''
    age = -1
    height = 0

    def print (self):
        print(f'Имя: {self.name}')
        print (f'Возраст: {self.age}')
        print (f'Рост: {self.height}')
        print ('-'*30)
p1 = Human ()
p1.name = 'K'
p1.age = 41
p1.height = 200

p1.print()



p2 = Human ()
p2.name = 'L'
p2.age = 18
p2.height = 130

p2.print()
