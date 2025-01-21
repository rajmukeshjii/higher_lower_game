The Higher_Lower game is a simple Python-based command-line game where players guess which of two accounts has more followers. The game provides descriptive details about the accounts, and players can input their guesses until they make an incorrect choice. This project is a fun way to practice Python programming and explore concepts like data handling, randomization, and user interaction.

Features

    Compare Accounts: Display two accounts and their descriptions.
    
    Guess the Followers: User inputs their guess about which account has more followers.
    
    Score Tracking: Keeps track of the player's score until a wrong guess is made.
    
    Replayable: Allows players to restart the game by re-running the script.


How It Works

    The game selects two random accounts from a database.
    
    It displays the name, description, and country of the accounts.
    
    The user guesses which account has more followers by typing 1 or 2.
    
    The game checks the answer and either:
    
    Increases the score if correct.
    
    Ends the game and displays the final score if incorrect.

Technologies Used
    
    Python: Core programming language used to build the game.
    
    Random Module: For selecting random accounts from the database.
    
    OS Module: To clear the console output for a seamless user experience.

Requirements

    Python 3.x
    
    A game_database module containing account data structured as a list of dictionaries. Each dictionary should have the following keys:

        name: The name of the account.
        
        description: A brief description of the account.
        
        country: The country of the account.
        
        followers: The number of followers the account has.


Example structure for game_database.data:

        {
          "data": [
              {"name": "Account1", "description": "Musician", "country": "USA", "followers": 1000},
              {"name": "Account2", "description": "Artist", "country": "UK", "followers": 1500},
              // Add more accounts
          ]
      }

How to Play

      Run the game script in your terminal.
      
      Read the descriptions of the two accounts displayed.
      
      Input 1 if you think the first account has more followers or 2 for the second account.
      
      Continue guessing correctly to increase your score.
      
      The game ends when you make an incorrect guess, and your final score is displayed.

Example Gameplay-
      Compare 1: Account1, a Musician from USA
      Compare 2: Account2, an Artist from UK
      Who has more followers? Type 1 or 2: 2
      You are right. Your score is: 1

Author

  Developed by Mukesh Raj.
