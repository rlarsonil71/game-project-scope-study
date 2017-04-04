# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.

    Picture:  http://imgur.com/8nwKLCm

-   The data structure you plan to use.

    series: {
      [
      game: {
        id: 1,
        gameboard: ['x', 'o', 'x', 'x', 'o', 'x', 'o', 'o', 'x',],
        playerX: {
          id: 1,
          username: 'uniqueUserName1',
          email: 'email1@gmail.com'
        }
        playerO: {
          id: 2,
          username: 'uniqueUserName2',
          email: 'email2@gmail.com'
        }
        gameWinner: function () {...}
      }
      ]
    }

-   How you will take the markup of the game board and represent it in JS

    Create a gameboard which is an array of length = 9.  Draw static empty
    gameboard (2 horizontal and 2 intersecting vertical lines).  Each of the
    9 separate gameboard squares will be represented by an unique ID that will
    be used in the HTML, CSS, and JavaScript files.  Loop through JavaScript
    gameboard array and populate the (`X`, `O`, or blank) value of each
    gameboard index.

-   How you plan to approach this project.

    - Review requirements, feedback, suggested schedule, tips and bonuses within
      https://github.com/ga-wdi-boston/game-project
    - Follow project schedule
    - https://github.com/ga-wdi-boston/game-project/blob/master/schedule.md
      (Go slowly and stay methodical!)
    - Review Project Planning Wireframes practice
      https://github.com/ga-wdi-boston/project-planning-wireframes-practice
    - Review Game Project API
      https://github.com/ga-wdi-boston/game-project-api
    - Start slowly and be methodical throughout each phase of the project,
    - Identify each component and brainstorm what each component will do and what
      each component will need.  Separate each component as much as possible.
    - Add each component to a project schedule.
    - Design preliminary wireframes of what the front end will look like.
    - Write out 4-8 user stories for the app.
    - Whiteboard a model using the wireframe(s) and the user stories.
    - Create a simple HTML and CSS of the designed wireframe.
    - Create psuedocode logic for game board.
    - Code game board logic using JavaScript.
    - Using the Game Project API and recent studies for AJAX requests/responses,
      start communicating with the back-end using curl.   Once each curl command
      is successful, use this as a blueprint to begin writing the AJAX code for
      that specific command,
    - Test often and commit often,
    - Complete documentation.
    - Review requirements for any gaps.
    - Refactor code where necessary,


-   4-8 user stories for your game project.

    1. As user, log in using password and plays game as either X_Player or O_Player
        (randomly set to allow for fair play)
    2. As user, change password.
    3. As user, exit game (logs off).
    4. As X_Player user, select a blank game board position and a 'X' is displayed
        in the selected game board position.
    5. As O_Player user, select a blank game board position and a 'O' is displayed
        in the selected game board position.
    6. X_PLayer and O_Player alternate turns until a winner is found (3 O's or
        3 X's in a horizontal, vertical or diagonal row on the game board)).

-   How you plan to keep your code modular.

    Use existing training GIT repos as templates in which their directory and
    file structures are modular by design separating app funcionality into
    separate JavaScript, HTML and CSS files.

-   What creative spin will you add to your project?

    Add CSS features such as animation dependent on available time.

-   How will you use version control to backup / track your project?

    Initiate and complete a GIT repo that will be uploaded to GITHUB

-   Do you plan to attempt any of the bonuses?

    Yes, depending on time and completion of project requirements.

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
