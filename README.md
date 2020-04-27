# Linear_Search
This program would search a number out of a list using a technique called Linear Search



def linear_search(n,x):
    elements=[]
    for i in range(n):
        elements.append(i)
        flag=0
        count=0
    for i in elements:
        count+=1
        if(elements[i]==x):
            print("The element found at pos:",i)
            flag=1
            break;
    if(flag==0):
        print("Element not found")
        
    print("The no of iteration to find the number is:",count)
            
        
linear_search(12,4)        
