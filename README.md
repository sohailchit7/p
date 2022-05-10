score = 0

name = ""

last = ""

celsius = "<35 or >38"

#This is where you put the brief story

print("Jesse Enriquez, 58 was born in Batangas City some 100 kms south of Manila, The capitol of the Philippines. Early on, he demonstrated a talent for drawing and illustrations. As a result, he studied Bachelor in Fine Arts major in Visual Communications. He decided to migrate to New Zealand. Together with his family they landed in Auckland in 2005.He has since evolved to become a teacher of Digital Technologies and is now the Head of Digital Tech Department in Manurewa High School. \n")

 

print("Kia ora, this is a small quiz to get to know me better.")

#Keep asking for name till it is given.

while name == "":

              name = input("What is your name?: ")

while last == "":

              last = input("What is your last name?: \n")

 

print("Now, let's begin! \n")

#Asking about people's temperature.

 

temperature = int(input("\nWhat is your temperature(In celsius, although no need for symbol)?"))

if temperature <= 0:

 

              print("\nSorry, you cannot do the quiz. Please come back once your tempertaure is between 35 and 38. Good bye!")

              quit

elif temperature < 35 or temperature > 38:

              print("\nSorry, that is a high temperature. You may have Covid. Please try again. Good bye!")

              quit

else:

              score = score + 1

      

#Question 1

answer1 = input("What is the capital of New Zealand? \na. Manurewa \nb. Wellington \nc. Auckland \nAnswer:")

if answer1 == "b" or answer1 == "Wellington":

               score += 1

               print("Correct!")

               print("Score: ", score)

               print("\n")

 

else:

  print("Incorrect! The answer is Wellington.")

  print("Score: ", score)

  print("\n")
 
