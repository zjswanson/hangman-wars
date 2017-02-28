# _Speed Hangman (Hangman wars?)_

#### _27 February 2017_

#### By _**Zach Swanson, Erica Wright**_

## Description

gameplay overview: a rendition of the game hangman, with speed and accuracy being important.  Application randomly selects a phrase, quote, or literary excerpt and the player must guess each unique word in the passage by playing a hangman-like game.  Rather than a set number of guesses per word (a la hangman), players have an overall number of mistakes they can make, represented by an "army" of toy soldiers.  As each incorrect guess is made, a soldier dies.  If they run out of soldiers, the player loses, if they correctly fill in the phrase then they win.

features to consider:
when the phrase is guessed, their army strength is compared to an enemy strength, with a random chance of victory.
rather than a set starting number, each new word gives a certain number of reinforcements.
a method to guess either the whole phrase or large chunks of it at once (high risk/reward).


## Setup/Installation Requirements

* Ensure [composer](https://getcomposer.org/) is installed on your computer.

* In terminal run the following commands:

1. _Fork and clone this repository from_ [gitHub].
2. Navigate to the root directory of the project in which ever CLI shell you are using and run the command: `composer install`.
3. To run tests enter `composer test` in terminal.
4. Create a local server in the /web directory within the project folder using the command: php -S localhost:8000 (assuming you are using a mac), or php -S localhost:8888 (if using windows).
5. Open the directory http://localhost:8000/ (if on a mac) or http://localhost:8888/ (if on windows pc) in any standard web browser.
6. Start server with MAMP and make sure your mySQL server is set to 3306.
7. Open phpMyAdmin and import the database zip files named hair_salon.sql.zip and hair_salon_test.sql.zip located in the project folder to import the databases needed.

## Specifications

|    *Behavior*   |    *Input*    |     *Output*    |
|-----------------|---------------|-----------------|
|

## Known Bugs

_None so far._

## Support and contact details

_Please contact ericaw21@gmail.com with concerns or comments._

## Technologies Used

* _Composer_
* _CSS_
* _HTML_
* _MySQL_
* _PHP_
* _PHPUnit_
* _Silex_
* _Twig_

### License

*MIT license*

Copyright (c) 2017 **Zach Swanson, Erica Wright** All Rights Reserved.
