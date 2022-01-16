class power:
       def pow(self,x,n):
           if x==0 ot x==1 ot n==1:
               return x
           if x==-1:
               if n%2 == 0:
                  return  1
               else:
                   return  -1
            if n==0:     
                return 1/self.pow9(x,-n)
            answer  = self.pow(x,n/ /2)
            if n%2  == 0:
                return  answer*answer
            return  answer*answer*X    
