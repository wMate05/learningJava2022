# learningJava2022
DIVE and DIVES (ADVENT OF CODE 2021)
  Dive is a class for the dive object. It has a String direction and int count. The class has get methods for both the direction and count. The toString() method return a string that identifies the direction and the count. It demonstrates Java's core feature of being object-oriented language.
  Dives is a class for the dives object. It has an Arraylist made up of Dive objects. The method DisplayDepthHoriz() returns the depth and horizontal position of the dive objects in the arrayList through the directions and values given. The toString method returns the direction and count of each dive object in the Arraylist.



FORTUNETELLER APP

FortuneCookie: It makes a Fortune Cookie Object with a string of fortunes that are imported through code from Dive. We have a luckyNumber() method and a randomFortuneCookieMessage() method that return a random number 1-100 and return a random fortune respectively.

Magic8Ball: It makes a Magic8Ball object with 3 string arrays,fortunes, riddles, and answers. In the constructor, the arrays are filled through importing files through the DIVE import method. There are get methods for each array as well as a the UserQuestionRun  method that retruns a random fortune out of the fortunes array.[

Horoscope: It makes a horoscope object with and int[] Rat, int[] Ox, int[] Tiger, int[] Rabbit,int[] Dragon, int[] Snake, int[] Horse, int[] Goat, int[] Monkey, int[] Rooster, int[] Dog, int[] Pig. The constructor constructs these arrays to include the years that correlate to each animal. The ZodiacSign method takes in an int year and returns which animal corresponds to the year.

SpiritAnimal: It constructs ArrayLists of braveAnimals, independentAnimals, spiritualAnimals, socialAnimals. We have return methods that return the animal at index 0 for each of the arraylists. There are also methods that remove top halves of each arraylist and methods thta remove the bottom halves of each arraylist.

GUI: It makes a GUI with a frame and panel. Buttons and labels are made visible and unvisble depending on what part of the app you are using. Clicking on the fortune cookie button gives you a fortune and lucky number and lets you play again. With the Your Horoscope button you are asked your birth year, zodiac sign, and birth month. It then gives you your horoscope and lets you pay again. With the Ask Us a question button, you must first answer a riddle question before being allowed to ask a question. If it's incorrect you will be given another riddle question. The user then inputs their question and is given a random answer of yes, no, or other types of answers. They are then given a play again buttton. For the Spirit Animal button the user answers 3 questions and is given a spirit animal based on their answers to the questions. They are then given a button that allows them to play again.



