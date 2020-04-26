# Linear_Search
This program would search a number out of a list using a technique called Linear Search



def search(a, n, x): 
  
    for i in range (0, n): 
        if (a[i] == x): 
            return i; 
    return -1; 
  
a = [ 2, 3, 4, 10, 40 ]; 
x = 10; 
n = len(a); 
result = search(a, n, x) 
if(result == -1): 
    print("Element is not present in array") 
else: 
    print("Element is present at index", result); 
