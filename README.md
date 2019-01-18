# name_generator

Project "Startup name generator". This project has a goal to generate a random Startup name.
Project has two lists - business terms and random words.
Project consist of four parts (Name, Age, Merge, color):

1. In the first part your name is asked. Then your name is sliced to every other character (leters) and those letters become upper letters.
Then every word in some_list (random words list) are iterated and if word starts with sliced letter, that word is added to new_list. From new_list random word is chosen. This is second word of the startup name.

2. In the second part your age is asked. Then your age number becomes seed for pseudo random number. From business_terms list a word is taken according to the number of pseudo random number.

3. In the third part two words are combined, you get your random startup name and you are asked if you are happy with your name. If your are not happy, you get one more Startup name, this time name is chosen randomly without taking into account your name or age. Then you are asked again if you are happy with the name.

4. If you are still not happy with random name you got, you are asked to say what is your favorite color. Then every color gets a random value (startup name) and the Startup name is printed according to your chosen color.
