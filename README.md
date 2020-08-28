# DFA
deterministics finite autometa in TOC
class abc:
    def __init__(self):
        self.i=0
        data=input("enter your string:")
        length=len(data)
        
        if(length>=1):
            def second(self):
                if(length==self.i):
                    print("string is acepted")
                    return 
                elif(data[self.i] not in "ab"):
                    print("string must contain /'ab'")
                    return
                else:
                    self.i+=1
                second(self)
                
                
            def first(self):
                for j in data:
                    if(j=="a"):
                        self.i+=1
                        second(self)
                        return
                    else:
                        return("starting character must be a")
                    
            first(self)
        else:
            print("length must be >=1")

obj=abc()
