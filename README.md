typo
====

Command-line script used to improve keyboard typing. Fast and easy to use with custom training texts.

## Background
I always find myself typing some specific words/characters wrong. The idea is to create a simple program which collects typing statistics and captures problematic areas. Which also should be able to generate custom training data aimed at improving the user's typing skill based on previous results.

## Usage
    // Command-line training text
    $ typo "This is a command-line text"

    // Text file containing training text
    $ typo -f /tmp/train.txt

    // Piped training text
    $ echo "This is a piped text" | typo

## Releases
No releases yet.

## License
This project is licensed under GPLv3.

