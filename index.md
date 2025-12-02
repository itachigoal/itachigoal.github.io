
# Chenghao Xue's Portfolio

My name is Chenghao Xue and I am a student at [Cal State Fullerton](https://fullerton.edu/) and my major is computer science. I plan to graduate in 2029.

## Github Profile

My Github page is [https://github.com/itachigoal](https://github.com/itachigoal)

### Favorite CPSC 120L Labs

* Lab 9, part 1

    This lab was one of my favorites because it was both challenging and required a unique approach to problem-solving. The goal was to build a spelling checker from scratch in C++. It sounded simple, but it forced me to figure out how to make several different pieces of code work together. First, I had to learn how to read words from files, both for the dictionary and the document, which was my first real hands-on experience with file input/output. Then, I used vectors, which are like flexible arrays, to store all those words in the program's memory. The real puzzle was writing the function that loops through every word in the document and checks it against the dictionary vector. Seeing the final program successfully output a list of misspelled words was incredibly satisfying. It took a lot of trial and error, but it finally clicked, and it showed me how these basic concepts can combine to create a actually useful program.

* Lab 10, part 1

    This specific lab was listed as one of my favorite labs because it required a lot of problem interpretation and it forced us to carefully look over the header file to understand what functions we needed to implement. The challenge wasn't just writing code, but designing the logic to work with a complex data structure. Throughout the lab, I learned how to use 2D vectors to organize California’s population data by county, where each inner vector represented a single county, storing its name and population as strings. It was fascinating to manipulate this structure by writing functions that iterated through each row of the data. For instance, I created a function that compiled all county names into a single string, another that searched for a specific county by name and returned its population—which required using std::stoi() to convert a string to an integer—and a final function that calculated the total state population by summing the values from every county. It is really interesting how you can utilize and access different files, using the functions in one file to process and validate the data from another, seeing the practical power of breaking down a large problem into smaller, manageable tasks that all work together cohesively.

* Lab 11, part 2

    This specific lab is my most favorite because it was my first deep dive into using classes, which required me to carefully understand the distinction between public and private members. Instead of managing loose variables in the main program, I learned to bundle all the game's data and functionality into a single, organized GameState object. This approach meant I that had to utilize the class's constructor to properly initialize the game's starting state which sets the secret number and the number of guesses. What I actually learned from this lab was in implementing the various member functions that act upon this private data, in which I created accessor functions to safely check how many guesses were left, and mutator functions to count down a guess. The main logic of this was in functions like GuessCorrect and GuessTooBig, which used conditional checks to compare the player's input to the secret number and guide the player. By summarizing all of this logic within the class, the code became dramatically simpler and cleaner in the main program file. This lab taught me how to use object-oriented design to minimize complexity, as all the messy details of game state management were hidden away, making the final program much easier for other coders to visualize, understand, and build upon compared to a more procedural version I had done before.
