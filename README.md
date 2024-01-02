# ritaclass Order:      
    def __init__(self, number: int, timestamp: date, customer: Customer):     
        self.number = number   
        self.timestamp = timestamp       
        self.products = []
        self.customer = customer    
        self.sum = 0
            
    def add_product(self, product: Product, quantity: int): 
        self.products.append({
            "product": product, 
            "quantity": quantity
        })
