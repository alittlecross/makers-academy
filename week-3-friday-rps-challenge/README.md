# Rock, Paper, Scissors, Lizard, Spock.

Makers Week 3 (Friday) - This project is a game for one or two players to play rock, paper, scissors, extended to include lizard, and spock.

## Getting started

Assuming you have `git` installed, in the location of your choice, in Terminal:

`git clone git@github.com:alittlecross/rps-challenge.git`

`cd` into the `rps-challenge` folder.

Assuming you have `Ruby` and `Bundler` installed, in that same location, in Terminal:

`bundle`

## Usage

In that same location, in Terminal:

`rackup`

Then in the browser of your choice:

`http://localhost:9292/`

You should see the page to enter names:

![enter-names-a](images/a.png)

You can enter one name (or no name) to play a one player game:

![enter-names-b](images/b.png)

Entering two names to play a two player game:

![enter-names-c](images/c.png)

Enter no name and the game will address the player accordingly:

![choose-weapon-a](images/d.png)

Similarly, if you enter one name:

![choose-weapon-b](images/e.png)

If you enter two names the game will ask the second player to look away while the first player chooses a weapon:

![choose-weapon-c](images/f.png)

And the opposite when the second player chooses a weapon:

![choose-weapon-d](images/g.png)

The game will refer to the player as 'you' if no name was entered at the start:

![result-a](images/h.png)

And player two as 'computer' if playing a one player game:

![result-b](images/i.png)

The game will show what each player chose and who wins:

![result-c](images/j.png)

With the option of playing again. If a one player game was started then a one player game will continue, likewise for a two player game.

## Running tests

In that same location, in Terminal:

`rspec`

## Linting

In that same location, in Terminal:

`rubocop`
