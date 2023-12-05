class addition:
    def __init__(self, val1,val2,val3):
        self.num1=val1
        self.num2=val2
        self.num3=val3

    def Add(self):
        self.res = ((self.num1+self.num2+self.num3)*100)/300
    
    def display(self):
        print(self.res)
sbjt1=int(input("subject1 marks: "))
sbjt2=int(input("subject2 marks: "))
sbjt3=int(input("subject3 marks: "))
objt1=addition(sbjt1,sbjt2,sbjt3)
objt1.Add()
objt1.display()

