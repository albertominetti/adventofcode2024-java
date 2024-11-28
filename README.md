# Advent of Code 2024

Solutions in Java for the Advent of Code in 2024

## Goals

1. Do not spend too much development time on a solution
2. Write tests with the example input to ensure that everything works and keeps working (also to test the second part)
3. Improve readability when writing an algorithm
4. Lower down the complexity and improve the performances when not impacting too much the readability
5. Try some new features of the languages or libraries when possible
6. Use the [Darkyen's Time Tracker](https://plugins.jetbrains.com/plugin/9286-darkyen-s-time-tracker) to inject the time spend of each puzzle`

## Automatic tool

This year I create an automation to quickly setup the environment; the script download the daily input to the `test/resources` folder, it prepares the initial Java code for the main algorithm and it prepares the tests to run the algorithm with the proper input. The code is in [DaySetup.java](src/main/aminetti/adventofcode2024/DaySetup.java) and it uses [DayXX.java](src/main/aminetti/adventofcode2024/dayXX/DayXX.java) and [DayXXTest.java](src/test/aminetti/adventofcode2024/dayXX/DayXXTest.java) as templates for the main code and the tests.
