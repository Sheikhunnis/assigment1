# assigment1
                                                            #python assigment



'''strings--> it is denoted in butween double qotations('x',"x")
varible--> it is used to store multiple datatpyes 
print--> it is keyword to print data
homogeneous --> it means same data in list eg:-[1,2,3,4,5],['shaik','unnis','hello'],[12.54,56.5,63.2]
heterogeneous --> deffirent data in list eg:-['shaik',12.3,5232,False]'''
   #creating a variable
a='helloworld'
print(a)
  #concatenation is used to add two strings in single variable
b='hello'
print(b,'shaikunnis') 
'''integer --> All whole numbers are integers. eg;-(124)
float --> it is denotes inside the point. eg:-(9.34)
collection datatypes --> List,Set,Dict,Tuple
datatypes --> string,integer,float,boolean'''


                        #list
                        
'''List it is denoted by square brackets being and end of the code[]
    it is used to store multiple datatypes in list
    it is mutable'''
list1=['hello',123,4.22,True] # created a list 
print(list1,'created data') #calling
print(type(list1))
    #data changing at specific place
a=list1[0]='world'
print(list1,'changed data')
#output-->hello
    #deleting data at specific places using key word is del
del list1[0]
print(list1,'deleted data')
    #calling data at specific places
#output-->[123,4.22,True]
a=(list1[0])
print(a,'calling data at specific place')
#output-->123
    #checking length in list 
print(len(list1),'is length')
#output-->3
    #adding data at specific places (append is keyword)
list1.append('computer')
print(list1,'data addes at last')
#output-->[123,4.22,True,computer]
  # adding two lists using + operator (or) using extend
list2=['shaikunnis',123,2.14]
print(list1+list2)
#output-->[123.4.22,True,'computer','shaikunnis',123,2.14]


                #set

'''set--> it is denotes by flower brackets {}
   it is immutable#once it is decleared it is not possible to updated,change,delete,call,add
   it is unordered 
   it ignores duplicates in set'''
set1={'shik',124,1232.45,True}  #created data
print(type(set1))#output-->set
print(set1)

                #tuple
                
'''tuple--> it is denotes by ()
once it is decleared it is not possible to updated,change,delete,add
it is immutable'''
tuple1=('hey',1212,23.34,True)
print(type(dict))
print(tuple1)

                #dictionary
#dic --> consists on key and value it is denoted by flower brackets {}
#it is mutable
dict={'brand':'vivo','price':20000,'storage':128}
print(dict,'created data')
print(type(dict))
print(dict['brand']) # calling value by using key
   #chainging data
dict['brand']='samsung'
print(dict,'brand is chainged')
#output-->{'brand':'samsung','price':20000,'storage':128}
    #removing data at specific place
del dict['brand']
print(dict)
#output-->{'price':20000,'storage':128}
    #checking length
a=(len(dict),'is length')
print(a)
#output-->2

        #Booleans
'''booleans=True,False is called as booleans 
    True value is 1 and False value is 0
    it is used to check which is big or small
    booleans operators is < and > '''
    
a=12
b=21
print(a>b) # output--> False because b is greater than a
print(a<b) # output--> True because a is lessthan b
print(a==b)# output--> False  because a and b is notequal
print(a!=b)# output--> True because a  is notequal to b


        #funtion
'''funtion is denotes to store a block of code by name
    name is used to calling data at specific place,time
    def is key word of funtion it is denoted before the funtion name
    and name is denoted after funtion and colan(:) is used at end of the funtion'''
#it is mostly useable in python
def a():
    print('shaikunnis')
a() # calling data  by funtion name 
#output-->shaikunnis
def c(a,b):
    print(a+b) # using add operator in funtion
c(1,2)
#3
#in funtion useing parameter it is inside of the closed brackets
def b(name):
    print('my name is ',name)
b('shaik')
#output-->my name is shaik





    

    
