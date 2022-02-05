
my_list = list(range(20,200))
  
result3 = list(filter(lambda x: (x % 4 == 0), my_list)) 
result5 = list(filter(lambda x: (x % 8 == 0), my_list)) 
  
print(result3,"This number only divisible by 4 in 20-200 number \n") 
print(result5,"This number only divisible by 8 in 20-200 number \n") 
print("THANKING YOU FOR USING IT")
