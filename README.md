# Python-Study
some records of learning Python.

# this program says hello and asks for my name.

print('hello world!')
print('what is your name?')  # ask for their name
myName = raw_input()   #Python3将raw_input 与 input
print('It is good to meet you,' + myName)
print('The length of your name is :')
print(len(myName))
print('What is your age?')    #ask for their age
myAge =raw_input()
print('You will be ' + str(int(myAge) + 1) + ' in a year.')
