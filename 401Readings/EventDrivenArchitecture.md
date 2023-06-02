# Event Driven Architecture

## Two Ideas: Simon Clicks : Type-action

### Simon Clicks

- Two people join a room and subscribe to a queue of click events. On player one's turn they click in a pattern on the screen for 2 seconds then player 2 has 5 seconds to view the pattern (displayed as a queue of events being passed with a time to make it animate long enough to track) and trace it score is based on how close each person's clicks are to the center point for 3 rounds and then the game starts over.

### Type-action

- Two players are in a game like previously, the first player types like any typical typing test, and the second player has to copy. The score is calculated on points for accurate typing and instead of WPM, how long it takes to copy a letter from when it was received. Typing events can be sent and stored as queued items
