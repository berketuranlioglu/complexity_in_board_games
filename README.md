# complexity_in_board_games
UniMi Information Retrieval project that aims the measure the complexity of the rulebooks and predict the difficulty level of board games.

In this project, rulebooks of various games were analyzed and their text complexity measured over simple metrics. Then, these complexity metrics
were used to calculate its own difficulty measurements with "Linear Regression with OLS" method. These measurements were then compared
to actual weights of the games.

Metadata for this project are fetched from BoardGameGeek's database with BGGXMLAPI2. Rulebooks are taken manually and combined with their
metadata to have single file that may contribute to future board games databases.

Guiraud Index and Gunning Fog Index are the main two interests of this project, while the inner elements of these equations are also included
to the complexity calculations. Linear Regression with Ordinary Least Squares method is by SciPy's stats library.
