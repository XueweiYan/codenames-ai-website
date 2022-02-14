# The Codenames AI
## by Yongqing Li, Xuewei Yan, and Cameron Shaw

## What is Codenames?

Codenames is a board game with a fairly simple premise, guessing words. There are two teams and one board. On the board, there is a 5 by 5 grid of words chosen from a predetermined pool. Each word is designated either an agent word, a neutral word, or an assassin word. The objective for both teams is to guess their respective set of agent words.

![codenames_board](img/codenames_game_example_3)

Each team has a set of agent words that they have to guess on the board. In order to help the teams guess the correct word, each team has one designated Spymaster, who can see the entire board and can also see what words their team must guess to win.

![codenames_spymaster_view](img/codenames_game_example_2)

The rest of the team, the Field Agents, or Guessers, don't know which words on the board are theirs. Thus, since the Spymaster can't tell the Field Agents exactly what words the Field Agents must guess, the Spymaster has to provide their team a hint. Using the Spymaster's hint, the Field Agents then have to guess which words on the board are theirs. Once a word has been guessed, that word is removed from the field. Both teams repeat this until one team has guessed their words or a team guesses the assassin word. If a team guesses the assassin word, that team immediately loses.

![codenames_hint_giving](img/codenames_game_example_1)

## Our AI

Our AI is written to simulate both a Guessing role and Spymaster role.
`TODO`

## How we did it

We wrote this AI using a few algorithms trained on several datasets.
`TODO`

## What we learned

We learned several things from doing this project.
`TODO`
