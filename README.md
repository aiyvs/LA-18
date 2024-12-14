# LA-18

class Ice_cream:
    def __init__(self, chocolate, whole_milk, heavy_cream):
        self.chocolate = chocolate
        self.whole_milk = whole_milk
        self.heavy_cream = heavy_cream
        
    def __str__(self):
        return f'''My ice cream has {self.chocolate},
        {self.whole_milk}, 
        {self.heavy_cream} ingredients.'''
    
choco = Ice_cream("Chocolate", "Whole Milk", "Heavy Cream")
mat = Ice_cream("Matcha", "Whole Milk", "Heavy Cream")
van = Ice_cream("Vanilla", "Whole Milk", "Heavy Cream")
    
print(choco)
print(mat)
print(van)
