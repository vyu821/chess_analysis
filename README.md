# chess_analysis

### To-do list
- create api to lichess to extract games
    - maybe have user input to filter games by username
- store games data, clean it
    - create dataframe
        - winner, white/black player id/rating, moves in standard chess notation, opening ECO code, opening name
- questions to answer
    - wins/losses as white/black
    - most common openings/played moves
        - as white, open with 1.e4, 1.d4, etc.
        - as black, against 1.e4, 1.d4, etc.
    - win percentage per opening, based off ECO (encyclopedia of chess openings) classification
    - recommends best opening as white/black
        - openings with most losses to work on
- display moves on chess board
    - interactive board, go through moves of games