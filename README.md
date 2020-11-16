# how-to-turn-into-a-loop

retailList = []

def start():
    
    location = input("enter the location: ")
    
    date = input("please enter the date: ")
    
    return location, date


   
    
start()

taxRate = float(input("enter the tax rate as a decimal: "))      
 

transactNum = int(input("enter the transaction number: ")) 

retailAmount = float(input("enter the retail amount: "))
retailList.append(retailAmount)




def firstSummary():
    
    print("transaction Summary: ")
    
    print("Transaction Number: ", + transactNum)
    
    print("Retail Amount: ", + retailAmount)
    
    
def main():

    inOne = transactNum
    
    inTwo = retailAmount
    retailList.append(inTwo)
    
    total = inTwo * taxRate
       
    amountTotal = inTwo + total
       
    print(inOne)
    print(total)
    print(amountTotal)
       
   
   
        
    
        
    
    
        
firstSummary()
main()       
