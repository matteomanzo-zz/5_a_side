[![Code Climate](https://codeclimate.com/github/matteomanzo/5_a_side/badges/gpa.svg)](https://codeclimate.com/github/matteomanzo/5_a_side) [![Test Coverage](https://codeclimate.com/github/matteomanzo/5_a_side/badges/coverage.svg)](https://codeclimate.com/github/matteomanzo/5_a_side)
#5 A Side

Want to play a 5 a side game? Don't you want to forget who said "I'm in!" and don't know how to shuffle the teams?
This program will help you organise your weekly 5v5 game by keeping track of the players, teams and results!

[Live Version](https://makers-five-a-side.herokuapp.com/)

![ball](/soccer.png)

##Job list

- [x] Store players information;
- [x] Randomly generate teams;
- [x] Will not generate the same teams twice in a row;
- [x] Allow players to decide whether they want to play or not.

##Technologies
| Languages | Front End   | Server  | Databases | Testing |
|----  | ------------|-------------| -----      | ----- |
| Ruby | HTML & CSS  | Sinatra     | PostgreSQL | RSpec |
|      |             |             |            | Capybara |

##How to run it
Clone the repository
```
SSH:
$ git clone git@github.com:matteomanzo/5_a_side.git
HTTPS:
$ git clone https://github.com/matteomanzo/5_a_side.git
```
Change into the directory
```
$ cd 5_a_side
```
Create the databases
```
$ psql
CREATE DATABASE five_a_side_development;
CREATE DATABASE five_a_side_test;
\q
```
Install the gems
```
$ bundle install
```
Run the tests
```
$ rspec
```
Run it locally with `rackup` and go to `http://localhost:9292/`.

##ToDo

- [ ] Admin account to reset teams
- [ ] Players who join after the teams are generated have to be balanced within the teams
- [ ] <strong>Refactor controllers !!!</strong>

##Collaborators

- [Gus Powell](https://github.com/guspowell)
- [Matteo Manzo](https://github.com/matteomanzo)
