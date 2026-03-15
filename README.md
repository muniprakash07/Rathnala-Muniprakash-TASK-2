# Bitwise Operator Tasks (1–8)
1)
   a=10
   b=6
   print(a&b)=2
   result(a&b)=2
  
2)    
   x=12
   y=5 
  print(x|y)
  result(x|y)=13

 3)     
   num=8
   print(~num)
   result(~num)=-9

 4)  
   a=15
   b=9
   print(a^b)
   result(a^b)=6

 5)
   num=7
   print(num<<2)
   result(num<<2)=28

 6)
    num=20
   print(num>>20)
   result(num>>20)=10

  7)  
    a=13
    b=12
    print(a&b)
    result(a&b)=12

  8)  
    a=17
    b=12
    print(a^b)
    result(a^b)=29


# String Tasks (9–14)

  9) 
    a="hi"
     print(a*4)
     result(a*4)=hihihihi

  10)   
     a="python"
     print(a*3)
     result(a*3)=pythonpythonpython

  11)
    str1="super"
    str2="man"
    print(str1+str2)
    result(str1+str2)=superman

   12) 
       string1= "hello"
       string2= "world"
       string3= " "
       print(string1+string3+string2)
       result(string1+string3+string2)=hello world
       
    13)
      name="muni"
      print(name *5)
      result(name *5)= munimunimunimunimuni
      
    14)
      str1="data"
      str2="science"
      print(str1+str2)
      result(str1+str2)=datascience

    # TASK (15-20) - (TYPE CASTING) 

  15)
    name=input("enter your name:- ")
    print("user name is:- ",name)
    print("data type of name is:- ",type(name))
    data type of name is :-<class string>

    16)
      age=input("enter your age:- ")
      print("user age is:- ",age)
      print("data type of age is:- ",type(age))
      data type of age is :-<class string>
      
     17)
       num1=15
       num2=19
       num1=int (input("enter your num:-"))
       num2=int (input("enter your num:-"))
       print("the sum of num1 and num2 is:- ",num1+num2)
       the sum of num1 and num2 is:-  34
       
    18)
      name1 english marks=98
      name2 maths marks=99
      name1=int(input("enter your english marks:- "))
      name2=int(input("enter your maths marks:- "))
      print("the average of marks of both subjects is:- ",(name1+name2)/2)
      the average of marks of both subjects is:-  98.5

    19)  
      a=6
      b=9
      a=int(input("enter a number:- "))
      b=int(input("enter a number:- "))
      print("3*a*2+b-2 is :- ",3*a*2+b-2)
     the result(3*a*2+b-2) is  = 43

    20)
      num=input("enter a number:- ")
      print("data type before casting is:- ",type(num))
      converted_num=int(num)
      print("data type after casting is:- ",type(converted_num))
      enter a number:- 27
      data type before casting is:-  <class 'str'>
      data type after casting is:-  <class 'int'>

   # Unit Digit Tasks (21–25)

     21)
        num = "1234"
        print(" ", num[-1])
        result=4

     22)
       num=4546
       print(" ",num%10)
       result=6

     23)
       num=6543
       print(" ",num//10)
       result=654

     24) 
       num=1234
       print(" ",num//100)
       result=12

     25)  
       num=98765
       print(" ",num%10)
       result=5


   # If Statement Tasks (26–30)

     26)
        if 10 >= 5:
            print(" 10 is greater than or equal to 5")
        result= 10 is greater than or equal to 5

     27)
       num=67
        if num > 50:
            print("num is greater than 50")
        result=num is greater than 50

     28)   
        if age >= 18:
            print("eligible")
        result=eligible

     29)
       num=543
       if num > 100:
           print("num is greater than 100")
       result=num is greater than 100

     30)
       num=7
       if num >= 0:
           print("num is positive")
       result=positive

  #  If-Else Tasks (31–34)    


     31)
       num=9
       if num % 2 == 0:
           print("num is even")
       else:
           print("num is odd")
       result=num is odd   

     32)
        marks=87
        if marks >= 35:
            print("pass")
        else:
            print("fail")
        result=pass

      33)
         num=64
         if num >= 0:
            print("positive")
         else:
             print("negative")
         result=positive

      34)
        num=15
        if num > 10:
            print("num is greater than 10")
        else:
            print("num is not greater than 10")
        result=num is greater than 10

    
  # Nested If Tasks (35–37)


35)
  age=18
height=160
weight=67
if age>=18 :
    if height>=160 :
        if weight>=60 :
            print("selected")
        else:
            print(" weight is rejected")
    else:
        print("age is rejected")
else:
    print("height is rrejected")
 result=selected

36)
 marks=78
age=16
if marks >= 60 :
    if age >= 17 :
        print("eligible for admission")
    else:
        print("age is not eligible for admission")
else:
    print("marks is not eligible for admission")
    
    result= age is not eligible for admission

37)      
Age = 19
Height = 169
Weight = 60
if age >= 16 :
    if height >= 150 :
        if weight >= 50 :
            print("selected for sports")
        else:
            print("age is rejected for sports")
    else:
        print("height is rejected for sports")
else:
    print("weight is rejected for sports")
result = selected for sports

  # Match Statement Tasks (38–40)

  38)
day = int(input("enter a day number between 1 to 7:- "))
match day :
    case 1:
        print("sunday")
    case 2:
        print("monday")
    case 3:
        print("tuesday")
    case 4:
        print("wednesday")
    case 5:
        print("thursday")
    case 6:
        print("friday")
    case 7:
        print("saturday")

 result=sunday

39)
if num == 1:
    print("you have selected red")
elif num == 2:
    print("you have selected green")
elif num == 3:
    print("you have selected blue")
else :
    print("you have entered an invalid number")

result = you have entered an invalid number

 40)
if num== 1:
    print("you have selected Apple")
elif num == 2:
    print("you have selected Mango")            
elif num == 3:
    print("you have selected Orange")
elif num == 4:
    print("you have selected Banana")
else:
    print("you have entered an invalid number")

result = you have entered an invalid number



















































































































       















    
     #  If Statement Tasks (26–30)

    )
       if(10>=5):
          print("now i think condition is true")  
       result=now i think condition is true

     27)
       
















     
