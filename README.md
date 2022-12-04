# Advent of Code

*Spoiler alert*. This repo contains solutions to problems from the [Advent of Code](https://adventofcode.com/) problem set. This is a great problem-solving resource that I have used with Secondary School pupils at [Highgate School](https://www.highgateschool.org.uk/)

## Solution code and data
Many of the [Advent of Code](https://adventofcode.com/) problems illustrate standard Computer Science theory. Here are some examples of Computer Science topic areas and Python techniques that I used for my solutions.
- [2020](https://github.com/AndrewDales/advent_of_code/tree/main/Advent%20of%20Code/2020)
  - Day 3: Use `defaultdict(int)` to set up a labelled counter that will automatically start at zero.
  - Day 4: Use [regex](https://en.wikipedia.org/wiki/Regular_expression) to recognise a valid hex colour code. `^#[A-Fa-f0-9]{6}$` matches a hex colour code such as #ee45a5.
  - Day 6: Use `my_set[0].intersection(*my_set[1:]` to find the intersection of a list of sets.
  - Day 7: This problem involves a [tree](https://en.wikipedia.org/wiki/Tree_(data_structure)) structure.
    - Use [regex](https://en.wikipedia.org/wiki/Regular_expression) to help parse each line, including `re.findall('re.findall(r'[0-9]+', my_string')` to find all the numbers in a string
    - Use a [recursive depth first search](https://www.techiedelight.com/depth-first-search/) to traverse the tree.
  - Day 8: The problem involves a program written in a simple assembly language with jump (goto) statements and an accumulator.
    - I used a State `dataclass` from the `dataclasses` module to keep track of the current state of a program run.
  - Day 10: Solved using a [recurrence relation](https://en.wikipedia.org/wiki/Recurrence_relation)
  - Day 11: This is an example of a 2D cellular automaton
    - Solved by using a `dataclass` to hold the current state and tranistioning each cell depending on the transition rules
    - Solution involved writing a `find_neighbour` function to find all the neighbours of a given cell in an n-dimensional grid. 
- [2021](https://github.com/AndrewDales/advent_of_code/tree/main/Advent%20of%20Code/2021)
- [2022](https://github.com/AndrewDales/advent_of_code/tree/main/Advent%20of%20Code/2022)
  - Day 3: Use `set` and `intersection`
