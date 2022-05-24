# Coderbyte-First-Factorial-Solution

def FirstFactorial(num):

  # code goes here
  if(num < 1 or num > 18):
    print("İnvalid input")
  else:
    i=num - 1
    numb=num
    while(i!=0):
      
      func = numb * i
      i=i-1
      numb = func
  num = func
  return num

# keep this function call here 
print(FirstFactorial(input()))
