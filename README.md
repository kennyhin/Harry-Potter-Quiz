# Harry-Potter-Quiz

print('''
*******************************************************************************
          |                   |                  |                     |
 ___      ____
                  .'* *.'
               __/_*_*(_
              / _______ \
             _\_)/___\(_/_
            / _((\- -/))_ \
            \ \())(-)(()/ /
             ' \(((()))/ '
            / ' \)).))/ ' \
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Hello there, it is me, dumbledore ")
print("Find out who you truly desire... (case-sensitive)")


opening_question = input("Are you boy or girl? ")
opening_question1 = opening_question.lower()

#Girl Questions
if opening_question1 == "girl":
    dog_question = input("Yorki or Corgi or Owl? ")
    dog_question1 = dog_question.lower()
    if dog_question1 == "yorki":
        print("You desire the strong and brave. You shall marry Harry Potter.")
    elif dog_question1 == "owl":
        print(
            "You desire the shy and intelligent . You love: Neville Longbottom.") 
            #Three questions
    elif dog_question1 == "corgi": 
        food_question = input("Carrots or Mints or Celery ? ")
        food_question1 = food_question.lower()
        if food_question1 == "carrots":
            print(
                "You value humor and friendship. Your man is: George Weasley.")
        elif food_question1 == "mints":
            print("You desire fame and fortune. Your husband is: Draco Malfoy")
        elif food_question1 == "celery":
            print("You desire the quirky and fun-loving, Seamus Finnigan.")

#Boy Questions
elif opening_question1 == "boy":
    color_question = input("Green or Purple or Blue? ")
    color_question1 = color_question.lower()
    if color_question1 == "green":
        print("You desire the rude girls, Pansy Parkinson.")
    elif color_question1 == "purple":
        print("You desire the kind and sweet . You love: Luna Lovegood.")
    elif color_question1 == "blue":
        drink_question = input("Tea or Coffee or Water? ")
        drink_question1 = drink_question.lower()
        #Three questions
        if drink_question1 == "coffee": 
            print("You are attracted to the smart and witty, the woman you desire is, Ms. Hermione Granger.")
        elif drink_question1 == "tea":
            print("You like the shy and smart, you marry Cho Chang.")
        elif drink_question1 == "water":
            print("You desire the basic. You end up with Ginny Weasley.")
