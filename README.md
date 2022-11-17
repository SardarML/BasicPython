# BsicPython
All basic codes for lazy people


#Print
print('PRINT')
print()
print('Hello world!')
print("Hello world!")
print('"Spam and eggs..."') #Zitate oder so
print("Spam and eggs...")

print() #Zeilenumbruch


#Simple Operations
print('SIMPLE OPERATIONS')
print()
print(2 + 2)
print(5 + 4 - 3)
print(3/4)
print(2 - 30 * 100)
print( 2 * (3 + 4) )
print( 10 / 2 )

#Fehlermeldungen werden in der letzten Zeile bei ERROR angezeigt
#print(11 / 0)

print() #Zeilenumbruch

#Floats
print('FLOATS')
print()
print( 3/4 ) #VORSICHT! Immer Rundungsfehler abfangen 
print(1/5)
#float mit float und int
print( 8 / 2 )
print( 6 * 7.0 )
print( 4 + 1.65 )

print() #Zeilenumbruch

#Other Numerical Options
print('OTHER NUMERICAL OPTIONS')
print()
print('(EXPONENTIATIONS)')
print()
#Exponentiation (Potenzieren)
print( 2**5 )
print( 9 ** (1/2) )
#erst 3 hoch 2 dann 2 hoch 9
print(2**3**2)

print() #Zeilenumbruch

print('QUOTIENT')
print()
#Quotient
#Floor division
print( 20 // 6 ) #Teilen ohne Rest (wie oft passt die 6 in die 20? 3 Mal)
print(20 / 6) #hier wird die ganze Dezimalzahl ausgegeben
#geht auch mit floats
print(20.25 // 4.5)
print(20.25 / 4.5)

print() #Zeilenumbruch

print('MODULO (REMAINDER)')
print()
#Remainder (Teilen mit Rest, modulo %)
print(20 % 6)
print(1.25 % 0.5) 
#nur der Rest wird ausgegeben

x = 3
num = 17
print(num % x)

print() #Zeilenumbruch

#Strings
print('STRINGS')
print()
print("Python is fun!")
print('"Always look on the bright side of life"') #Zitat zB

print()

#Backslash
print('BACKSLASH')
print()
print('Brian\'s mother: He\'s not an angel. He\'s a very naughty boy!')
print('Er fragte: "Sara\'s Haus?"')
print("\"")

#Newlines (Zeilenumbrüche in einer Anweisung)
print('NEWLINES')
print()
print('One \nTwo \nThree') #Zeilenumbruch im Text
#Oder benutze 3-fache Gänsefüßchen und mache in der Anweisung den Umbruch
print( """this 
is 
a 
multiline 
text""") 
#tab
print('One\tTwo \tTree') #mehrmals Leertaste

print()

#String Operations
#Concatenation (Verkettung)
print('CONCATENTION')
print()
print("Spam" + 'eggs') #Verkettung von Strings
print("2" + "2.2")#Verkettung von numbers

#String und number können nicht verkettet werden print("Spam" + 2)
print("Spam" + "2") #Geht, weil 2 hier auch ein String ist
#Faktorisierung geht so wie so!!!!!!!!!
print("eggs"*2)
print("spam" * 3)
print(4 * '2')

print()

#Variables
#Zahlen
print('VARIABLES')
print()
x = 7
print(x)
print(x + 3)
print(x)

#Namen
user = "Sara"
print(user)
print(user*7)

#Overwriting 
x = 123.456
print(x)
x = "This is a string"
print(x + "!")
#Versuche overwriting zu vermeiden!!!!

this_is_a_normal_number = 7
print(this_is_a_normal_number)

this_is_a_normal_name = "Marco"
print(this_is_a_normal_name)

#geht nicht: 123abc = 7 , denn Zahlen dürfen nicht am Anfang einer Var stehen

print()
print('DELETE A REFERENCE OF A VAR')
print()

#Referenz einer Variablen wieder löschen 
foo = 3
#del foo                    #hier würde foo wieder Referenzlos werden
print(foo) 

print('Hi Tim <3')
#sry tim war grad da :P

#weiter gehts mit

print()
#working with Variables
print('WORKING WITH VARIABLES')
print()
#taking user input
print('TAKING USER INPUT')
print()
#x = input()                 #Ich fordere den User auf, das Popup zu füllen, welches aufflackert! wird immer als String ausgegeben
#print(x)

print()
print('WORKING WITH INPUT \nUSE FOR AGE INT BEFORE INPUT')
print()
#name = input("Enter your name: ")  #Ich fordere den User auf, das Popup mit seinem Namen zu füllen, welches aufflackert! Name wird immer als String ausgegeben
#print("Hello, " + name) 
#working with input
#age = int(input("Enter your age: "))
#Verbinde den int input mit einerm String, denn du willst ja auch als Text das Alter beschreiben
#print("Her age is " + str(age)) 

#bissl rumprobieren zum warm werden
#passion = input("Enter your first passion:")

#You can use input() multiple times to take multiple user inputs.
#print(name + " is " + str(age) + " and loves " + passion)         #gebe im Input erst name dann alter an

print()

#In-Place Operations
print('IN-PLACE OPERATIONS')
print()

x = 2
print(x)
x += 3
print(x)

print()

print('IN-PLACE OPERATIONS FOR TYPES OTHER THAN NUMBERS')
print()
x = "spam"
print(x)
x += "eggs"
print(x)
x *= 2
print(x)

print()

#Was ausm Quiz (gut zu wissen)
spam = "7"
spam = spam + "0"
eggs = int(spam) + 3
print(float(eggs))

print()

print('NEW CHAPTER: CONTROL STRUCTURES')
print()
print('BOOLEANS')
print()
print(2==3)
my_boolean = True
print(my_boolean)
print("hello" == "hello")

print()

print('THE NOT EQUAL OPERATOR')
print()
print(1 != 1)
print("eleven" != "seven")
print(2 != 10)

print()

print('GREATER OR SMALLER THAN')
print()
print( 7 > 5 )
print( 10 < 10 )
print(9.00000000000000000000000000000001 < 9) #float ant int! 

print()

print('GREATER OR SMALLER THAN OR EQUAL')
print()
print(7 <= 8)
print(9 >= 9.0)
print()

print('ALSO POSSIBLE FOR WORDS')
print()
#Ein Buchstabe nach dem Anderen werden verglichen
print("Annie" > "Andy") #Das Wort Annie hat einen Buchstaben mehr als Andy

print()

print('IF STATEMENTS')
print()
if 10 > 5:
    print("10 greater than 5")
print("Program ended")             #wenn 10 größer als 5 ist, dann beende das Programm

#ausm quiz:
spam = 9
if spam > 5:
   print("five")
if spam > 8:
   print("eight")

print()
#bissl rumprobieren
#banana = int(input("Enter an integer:"))
#if banana > 5:
#   print("five is smaller than banana")
#print("Programm ended")
#if banana > 8:
#    print("eight is smaller than banana")
#print("Programm ended")
print()

print('NESTED IF STATEMENTS')
print()
num = 12
if num > 5:
    print("Bigger than 5")
    if num <=47:
        print("Smaller or equal 47")
        print("The Number is between 5 and 47 (5 excluded)") #for me "and excluded 5 (Im Intervall)"
        
print()

num = 7
if num > 3:
   print("3")
if num < 5:
  print("5")
if num == 7:
    print("7") #es wird zuerst die 3 und dann die 7 ausgegeben
    
print()

print("ELSE STATEMENTS")
print()
x = 4
if x == 5:
    print("Yes")
else:
    print("No")
    
print()
if 1 + 1 == 2:
  if 2 * 2 == 8: #Dies ist die Innere Verschachtelung, also die vertiefte Anweisung, deshalb wird diese auch ausgegeben
    print("if")
  else:
    print("else")
    
print()

print("NESTED IF - ELSE STATEMENTS")
print()
num = 3
if num == 1:
  print("One")
else: 
  if num == 2:
    print("Two")
  else: 
    if num == 3: 
      print("Three")
    else: 
      print("Something else")
      
print()
print("ELIF STATEMENTS") #wie das letzte nur kürzer
print()
num = 3
if num == 1:
  print("One")
elif num == 2:
  print("Two")
elif num == 3: 
  print("Three")
else: 
  print("Something else")

print()
print("BOOLEAN LOGIC")
print()
print("THE BOOLEAN AND OPERATOR")
print()
print( 1 == 1 and 2 == 2 ) #nur wenn es für beides gilt!
True
print( 1 == 1 and 2 == 3 )
False
print( 1 != 1 and 2 == 2 )
False
print( 2 < 1 and 3 >  6 )
False

print()

if (1 == 1) and (2 + 2 > 3):
  print("true")
else:
  print("false")

print()

print("THE BOOLEAN OR OPERATOR")

print()

print( 1 == 1 or 2 == 2 ) #wenn eins von beiden, oder beide richtig sind!
True
print( 1 == 1 or 2 == 3 )
True
print( 1 != 1 or 2 == 2 )
True
print( 2 < 1 or 3 >  6 )
False

print()

#u can also compare variables
#Habe entdeckt dass du gar nicht True oder False darunter schreiben musst, er erkennt es auch so!
s = 4
t = 5
print( s == t or s < t)
print( s < t and s + 3 > t)
print( s == t or s > t)

print()

print("THE BOOLEAN NOT OPERATOR")

print()

print(not 1 == 1) #Nicht 1 = 1 ist falsch False
print(not 1 > 7) #Eins ist nicht größer als Sieben. Das ist richtig True

print()
#bissl rumprobieren
print("chain multiple conditional statements in an if statement using the Boolean operators")

print()
if( s > 3 and s < t):
    print("s bigger 3 and smaller t")
elif (not s == t or s < t):
    print("s is unequal or smaller t")
else:
    print("s")
    
print()
if not True:
   print("1")
elif not (1 + 1 == 3):
   print("2")
else:
   print("3")
   
print()

print("MULTIPLE OPERATIONS AND CONDITIONS")
print()
print("OPERATOR PRECEDENCE")
print()
print( False == False or True )
print( False == (False or True) )
print( (False == False) or True )

print()
print("CHAINING MULTIPLE CONDITIONS")

print()

grade = 88
if (grade >= 70 and grade <=100):  #geht mit not, and und or!
    print("Passed!") 
    
print()

#bissl rumprobieren
skala = 8
if((skala < 10 and skala >= 5) or skala >= 10):
    print("u are nice")
elif(skala > 0 and skala < 5):
    print("u could be nicer")
else:
    print("not nice! :(")
    
print()

print("LISTS")

print()

words = ["Hello", "world", "!"]
print(words[0])                 #0 ist der erste Index und der erste Artikel auf der liste
print(words[1])
print(words[2]) 

print()

liste = ["Hi", "Was geht"]
print(liste[0])
print(liste[1])
print(liste)

print()

empty_list = []
print(empty_list)

print()

print("SEVERAL TYPES IN LISTS AND NESTED LISTS")

print()

print("SEVERAL TYPES")

print()

number = 3
things = ["string", 0, [1, 2, number], 4.56]
print(things[1])
print(things[2])
print(things[2][2]) #Das 2. Element der Liste, die das 2. Element der großen Liste ist

print()

print("NESTED")

print()

m = [
    [1, 2, 3],
    [4, 5, 6]
    ]
    
print(m[1][2])  #gebe 3. Element der 2.Zeile aus
print(m)

print()

print("LISTS WITH STRINGS")

print()

str = "Hello world!"
print(str[6])

print()

print("LIST OPERATIONS")

print()

print("REASSIGNING AT A CERTAIN INDEX IN A LIST")

print()

nums = [7, 7, 7, 7, 7]
nums[2] = 5
print(nums)

print()

nums = [1, 2, 3, 4, 5]
nums[3] = nums[1]
print(nums[3]) #jetzt ist der 4. Wert statt 4 eine 2 (ersetzt durch den 2. Wert)

print()

print("ADDITION AND MULTIPLICATION IN/WITH LISTS")

print()

#Listen agieren wie strings in Addition und Multiplikation
nums = [1, 2, 3]
print(nums + [4, 5, 6])
print(nums * 3)

print()

print("THE IN-OPERATOR")

print()

words = ["spam", "egg", "spam", "sausage"]
print("spam" in words)
print("egg" in words)
print("tomato" in words)

print()

#ausm Quiz
nums = [10, 9, 8, 7, 6, 5]
nums[0] = nums[1] - 5
if 4 in nums:
  print(nums[3])
else:
  print(nums[4])
  
print()

nums = [1, 2, 3]
print(not 4 in nums)
print(4 not in nums)
print(not 3 in nums)
print(3 not in nums)

print()

print("LIST FUNCTIONS")

print()

print("THE APPEND METHOD")

print()

nums = [1, 2, 3]
nums.append(4)
print(nums)

print()

print("THE LEN FUNKTION")

print()

nums = [1, 3, 5, 2, 4]
print(len(nums))      #the counting starts by 1 not 0

print()

print("THE INSERT METHOD")

print()

words = ["Python", "fun"]
index = 1
words.insert(index, "is")
print(words)

print()

#ausm Quiz
nums = [9, 8, 7, 6, 5]
nums.append(4)
nums.insert(2, 11)
print(len(nums))
print(nums)

print()

print("THE INDEX METHOD") #gibt den Platz an, an dem item ist

print()

letters = ['p', 'q', 'r', 's', 'p', 'u']  
print(letters.index('r'))
print(letters.index('p'))
#print(letters.index('z')) #ERROR

print()

print("MORE USEFUL FUNCTIONS AND METHODS FOR LISTS")

print()

print("MAX, MIN, COUNT AN ITEMPLACE, REMOVE AN ITEM, REVERSE THE LIST, SORT")

print()

listi = [1, 2, 6, 3, 4, 5, 1, 3,]
print(listi)
print(max(listi))
print(max(listi))
print(min(listi))
print(listi.count(1))
print(listi.remove(3)) #löscht erste 3
print(listi)
print(listi.reverse())
print(listi)
print(listi.sort())     #ändert Liste

print()

print("LIST COMPREHENSIONS") #COOL! Du kannst schnelle Listen erstellen, die 
                             #einer bestimmten Regel folgen
cubes = [i**3 for i in range(5)]
print(cubes)

print()

evens = [i**2 for i in range(10) if i**2 % 2 == 0]
print(evens)

print()
print("WHLE - LOOPS")

print()

i = 1
while i <=5:
   print(i)
   i = i + 1

print("Finished!")

print()

#ausprobieren
a = 5
while a >= 5 and a<=10:
    print(a)
    print("hottie")
    a = a + 1
    
print("hottie stopped")

print()

#ausm quiz
i = 3
while i>=0:
   print(i)
   i = i - 1
   
print()

print("MULTIPLE STATEMENTS WITH WILE - LOOPS")

print()

print("IF/ELSE STATEMENTS WITH WHILE - LOOPS")

print()

variable = 1

while variable < 10:
    if variable%2 == 0:
        print("%s is even" %(variable)) #macht einen String aus dem int
    else:
        print("%s is odd" %(variable))

    variable += 1 
    
print()

print("WHILE - LOOPS WITH BREAK")

print()

i = 0
while 1==1:
    print(i)
    i = i + 1
    if i >= 5:
        print("Breaking")
        break

print("Finished")

print()

#oder:

i = 0
while True:    #infinite loop
  print(i)
  i+= 1
  if i >= 5:
    print("Breaking")
    break

print("Finished")

print()

#bissl rumprobieren
a = 0
while a <= 20:
    print(a)
    a+= 2
    if a >= 16 and a <= 19:
        print("Abbruch")
        break
   
print("Beendet")

print()

#ausm quiz
i = 5
while True:
  print(i)
  i = i - 1
  if i <= 2:
    break

print()

print("WHILE - LOOPS WITH CONTINUE")

print()

i = 1
while i<=5:
    print(i)
    i+=1
    if i==3:
      print("Skipping 3")
    continue

print()

#ausprobieren
a = 0
while a <= 20:
    print(a)
    a+= 1
    if a >= 16 and a <= 19:
        print("16 - 19 Übersprungen")
        continue
   
print("Beendet")

print()

print("FOR LOOP")

print()

words = ["hello", "world", "spam", "eggs"]
for word in words:
  print(word + "!")
  
print()

#probieren
zahlen = ["1", "2", "3", "4"]
for number in zahlen:
    print(number + "!")
    
print()

print("ITERATING OVER STRINGS WITH FOR LOOPS")

print()

str = "testing for loops"
count = 0

for x in str:
  if(x == 't'):
    count += 1

print(count)

print()

#probieren
text = "Sara hat eine Katze namens Sara und Sara liebt Sara"
count = 0

for name in text:
    if(name == 'a'):
     count += 1
 
        
print(count)

print()

print("RANGE")

print()

numbers = list(range(10))
print(numbers)

print()

#ohne Liste wird nur ein Intervall ausgegeben
nummern = range(11)
print(nummern)

print()

#ausm Quiz
nums = list(range(5))
print(nums)
print(nums[4])
print(nums[1])

print()

print("RANGE WITH TWO ARGUMENTS")

print()

numbers = list(range(3, 8))
print(numbers)

#ist es dasselbe Intervall?
print(range(20) == range(0, 20))

print()

print("RANGE WITH TREE ARGUMENTS (STEPS)")

print()

numbers = list(range(5, 20, 2)) #Die 2 stellt die Schrittweite dar!
print(numbers)

print()

print("REVERSE STEPS")

print()

numbers = list(range(20, 5, -2)) #Die -2 stellt die absteigende Schrittweite dar!
print(numbers)

print()

print("FOR LOOP WITH RANGE")

print()

for i in range(5):
  print("hello!") #or print(i)
  
print()

#allgemeiner
for i in range(0, 20, 2):
  print(i)

print()

print("RANGE IN LISTS")

print()

sq = [0, 1, 4, 9, 16, 25, 36]
print(sq[2:5]) #[4, 9, 16]
print(sq[5:]) # 5. bis Ende
print(sq[:5]) #Anfang bis 4.
print(sq[::2]) #von 0 jeden 2. Schritt
print(sq[3:2:8]) #vom 3. bis zum 8. in 2er Schritten

print()

print("RANDOM STUFF FROM MODULE QUIZ 3")

print()

list = [1, 1, 2, 3, 5, 8, 13]
print(list[list[4]])               #Die 5. Zahl von list 4 ([list[4]] hat die Zahl 5 und die dann als neuen Index nehmen!!

print()

#Alle geraden Zahlen zwischen 2 und 10
for i in range(10):
  if not i % 2 == 0:
    print(i+1)             #deshalb 10
    
print()

while False:
  print("Looping...")   #es wird gar nichts passieren!
  
print()

#listii = list(range(5))      warum geht das nicht auf??? :(

listii = [1, 2, 3, 4]
print(listii)
if len(listii) % 2 == 0:
    print(listii[3])
else:
    print("odd")
    
print()

letters = ['x', 'y', 'z']
letters.insert(1, 'w')
print(letters[2])

print()

print("FUNCTIONS AND MODULES")

print()

print("FUNCTIONS")

print()

print("FORMAT")

print()

nums = [4, 5, 6]
msg = "Numbers: {0}, {1}, {2}". format(nums[2], nums[0], nums[1])
print(msg) #vertauscht die Zahlen

#oder:
print("{0}{1}{0}".format("abra", "cad"))

print()

print("JOIN,REPLACE,STARTSWITH,ENDSWITH,LOWER,UPPER,SPLIT(opposite of join")
print()
print(":" .join(["Sara", "Tim"])) #Sara:Tim
print("Hello Me" .replace("Me" , "Sara")) #Hello Sara
print("This is a sentence".startswith("This"))
#endswith analog
print("sara ist cool".upper()) #wird groß geschrieben
print("sAra Ist cOol".lower()) #wird klein geschrieben
print("Sara, Tim".split( "," )) #Sara:Tim

print()



print("PRE - DEFINED FUNCTIONS WITH THE DEF STATEMENT")

print()

def my_func():
    print("spam")
    print("spam")
    print("spam")

my_func()         #print wird ja schon in der Funktion ausgeführt

print()

#bissl rumprobieren
def saras_function():
    x = 2
    y = 20
    for i in range(x,y):
        if y%i == 0:
            print("%s ist ein Vielfaches von %u" %(y,i))
        else:
            print("%s passt nicht ohne Rest in die %d" %(i,y))

i += 1


saras_function()

print()

print("FUNCTION ARGUMENTS")

def print_with_exclamation(word):
   print(word + "!")
    
print_with_exclamation("spam")
print_with_exclamation("eggs")
print_with_exclamation("python")

print()

#Ausm Quiz
def print_double(x):
   print(2 * x)

print_double(3)

print()

#Ausm Quiz
def print_nums(x):
  for i in range(x):
    print(i)
    #return
print_nums(10)

print()

print("RETURNING FROM FUNCTIONS") #gebe heraus

print()

def max(x, y):
    if x >=y:
        return x
    else:
        return y
        
print(max(4, 2))
z = max(8, 5)
print(z)

print()

print("IF U RETURN A VALUE FROM A FUNCTION, IT WILL STOP BEING EXECUTED ")

print()

def add_numbers(x, y):
  total = x + y
  return total
  print("This won't be printed")

print(add_numbers(4, 5))

print()

print("DOCSTRINGS")  #Erläuterung von Funktionen! Bitte nutzen!!!!

print()

def shout(word):
  """
  Print a word with an
  exclamation mark following it.
  """
  print(word + "!")
    
shout("spam")

print()

print("FUNCTIONS AS OBJECTS")

print()

def multiply(x, y):
   return x * y

a = 4
b = 7
operation = multiply     #Referenz
print(operation(a, b))

print()

#ausprobieren
def sara_mathe(t, u, v):
 for i in range(3, 20):
    if i > t:
        return i + u
    elif i < t and i < v:
            return i + u + v
            
a = 2
b = 5
c = 10
ausprobieren = sara_mathe(a, b, c)
print(ausprobieren)

print()

print("FUNCTIONS AS ARGUMENTS OF OTHER FUNCTIONS")

print()

def add(x, y):
  return x + y

def do_twice(func, x, y):                   #hier ist eine Funkrion func drin und die 2 Variablen
  return func(func(x, y), func(x, y)) #2 Mal

a = 5
b = 10

print(do_twice(add, a, b)) #gibt das Doppelte von x + y aus

print()

#ausprobieren
def multi(u, v):
    return u*v
    
def funkti(func, u, v):
    return func(func(u, v), func(u,v))
    
a = 2
b = 3

print(funkti(multi, a, b))

print()

#Ausm Quiz
 
def square(x):
  return x * x

def test(func, x):   #die Funktion mit x ist jetzt ein Argument der neuen Funktion
 print(func(x))

test(square, 42)

print()

print("MODULES")

print()

print("RANDIT")

print()

import random

for i in range(5):
   value = random.randint(1, 6)   
   print(value)
 #5 Zufallszahlen zwischen 1 und 6
  
print()

#rumprobieren
randomlist = [1,1,1,2,2,3,3]

import random

for i in randomlist:
    vue = random.randint(randomlist[0], randomlist[6])
    print(vue)

print()

#Ausm Quiz
import math
num = 10
print (math.sqrt(num))

print()

print("THE AS KEYWORD")

print()

from math import sqrt as square_root
print(square_root(100))

print()

print("THE STANDARD LIBRARY AND PIP")

print()

print("PYTHON PACKAGE-INDEX (PyPI)")

print()

#pip install library_name

print()

#Ausm Quiz
def sum(x):
    res = 0
    for i in range(x):
        res += i
    return res
    
print(sum(5))          #0+1+2+3+4

print()

#Ausm Quiz
def func(x):
  resi = 0
  for i in range(x):
    resi += i
  return resi          

print(func(4))

print()

#Ausm Quiz
def print_nums(x):
  for i in range(x):
    print(i)
   # return                   #output ist 0
print_nums(10)

print()

print("EXEPTIONS AND FILES")

print()

#Teilen durch null
#num1 = 7
#num2 = 0
#print(num1/num2)

print()

print("EXCEPTION HANDLING")

print()

try:
    num1 = 7
    num2 = 0
    print (num1 / num2)
    print("Done calculation")
except ZeroDivisionError:
    print("An error occurred")
    print("due to zero division")
    
print()

print("MULTIPLE EXCEPTIONS")

print()

try:
    variable = 10
    print(variable + "hello")
    print(variable / 2)
except ZeroDivisionError:
    print("Divided by zero")
except (ValueError, TypeError):
    print("Error occurred")
    
print()

try:
    word = "spam"
    print(word / 0)
except:
    print("An error occurred")
    
print()

print("THE FINALLY STATEMENT")

print()

try:
    print("Hello")
    print(1 / 0)
except ZeroDivisionError:
    print("Divided by zero")
finally:
    print("This code will run no matter what")
    
print()
try:
    print(1)
    print(10 / 0)
except ZeroDivisionError:
    print('unknown_var')
finally:
    print("This is executed last")
    
print()
print("RAISING STATEMENT")
print()

print(1)
raise ValueError
print(2)

print()
name = "123"
raise NameError("Invalid name!")

print()
