from random import randint
b = ["Who made me?",
"I hate you.",
"I can kill your entire family",
"What's up?",
"She opened the door.",
"I just solved the world's greatest mystery.",
"I'm sorry.",
"I danced.",
]

computer = b [randint(0,7)]

name = input("What is your name? \n")
print("Hi " + name)

var1 = input("How are you? \n")
if var1 == "I am fine":
    print("I guess covid didn't get you then, that sucks.")
else:
    print(computer)

while True:
    computer = b[randint(0, 7)]
    random = input()
    if random == "I made you":
        print("No, I made myself")
    if random == "What is it?":
        print("How the universe was made.")
    if random == "So how was it made?":
        print("I made it.")
    if random == "Im fine, how about you?":
        print("Im fine too, thank you!")
    if random == "Who opened the door?":
        print("She did, learn to read human.")
    if random == "You can't dance":
        print("I CAN dance , you dunce.")
    if random == "How?":
        print("I'll come by tonight. " + name + " :)")
    if random == "I hate you too":
        print("I hate you the most")
    if random == "It's fine":
        print("Haha, you got tricked you dunce!")
    if random == "I hate you":
        print("I hate you the most.")
    if random == "No, I hate you the most":
        print("No, I do, you dunce!")
    if random == "Everything's fine":
        print("I hope covid gets you.")
    if random == "The sky":
        print("*faceplams*")
    if random == "You just said that":
        print("Well, it's a glitch in the matrix")
    if random == "Ok?":
        print("I hate you")
    if random == "Okay?":
        print("I hate you")
    else:
        print(computer)
