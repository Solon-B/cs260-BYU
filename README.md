# SnakeKing
## Description deliverable
### Elevator pitch
SnakeKing, the ultimate destination for classic gaming excitement! SnakeKing brings back the nostalgia of the iconic snake game in a modern online platform. Challenge your reflexes and strategy as you guide your snake to devour food and grow longer. Compete with players from around the world for the top spot on the leaderboards and become the SnakeKing. SnakeKing is easy to pick up and play, making it perfect for a quick gaming session or hours of entertainment.
### Design 

<img width="501" alt="Screenshot 2023-09-23 at 4 25 38 PM" src="https://github.com/Solon-B/cs260-BYU/assets/145093586/84e6c245-085a-413a-8944-01cf7974ace3">

<img width="501" alt="Screenshot 2023-09-23 at 4 23 03 PM" src="https://github.com/Solon-B/cs260-BYU/assets/145093586/cfff21c4-c155-4b86-a15a-caf48574330d">

<img width="501" alt="sample" src="https://github.com/Solon-B/cs260-BYU/assets/145093586/389dc375-c705-4460-8077-6ec536f1ccbd">

<img width="501" alt="Screenshot 2023-09-23 at 4 24 40 PM" src="https://github.com/Solon-B/cs260-BYU/assets/145093586/ba904d66-8ad7-4548-81ab-4d4166a7d08a">



### Key features
Secure login over HTTPS

Classic Gameplay: Experience the nostalgia of the classic Snake game.

Intuitive Controls: Easily maneuver your snake with responsive and user-friendly controls.
Display of GamePlay
Leaderboards: Compete for the top spot on global leaderboards and prove you're the ultimate SnakeKing.

Display milestones of other players (probably ever increase of 10)
Choose a difficulty level (easy,medium,hard)
### Technologies:
I am going to use the required technologies in the following ways.

**HTML**: Uses correct HTML structure for application. Several  HTML pages. One for log in, one for choosing difficulty, one for actually playing and one for the scoreboard. 



**CSS**: Mainly making the separate pages look good and for the game play to be fun and cool.

**JavaScript**: Powers the game logic and interactivity. Handling snake movement and collisions.

**Authentication**: An input for your user to create an account and login. I will display their name and score above the game. 

**Service**: Manages user profiles and scores

**DB**: Store the Highest Scores of players.

**Login** - Register and login users. Credentials securely stored in the database.

**WebSocket**: This will be realtime data sent when a player hits a mile marker. At the moment I'm thinking about every increase of ten points.

### HTML deliverable
For this deliverable I built out the structure of my application using HTML
- **HTML pages** - Several HTML pages. One for log in (index.html), one for choosing difficulty (difficulty.html), one for actually playing (play.html)and one for the scoreboard(scores.html).
- **Links** - I added the Difficulty page to the menu at the top of each page. add my git hub at the bottom. I have it so when you submit your name it takes you to the difficulty page then the submit linked to play.
- **Text** - I just changed the titile of things to snakeking
- **Longin** - the first page asks you to login with a grayed out "Your name here" that will desplay it above the game.
- **Images** - I changed the place holder photo to somtihng cool
- **Database** -  the idea that it will desplay the top highest score of the website on the score page and changed the colums for that a little.
- **Websocket** - it will show when people reach an increase of score of 10 and notify other players. 

### CSS deliverable
- **Header, footer, and main content body**
- **Navigation elements** - I added in the difficulty page and built the whole page with very nice colord buttons that link you to  the play page. set the github to my git. 
- **Responsive to window resizing** - My game looks great on all window sizes and devices
- **Application elements** - Used good contrast and whitespace 
- **Application text content** - Consistent fonts also changed the colors to colors i liked 
- **Application images** -  I changed the ico file to relate to my game and to desplay as a place holder in for my game. 


### JavaScript deliverable
For this deliverable I implemented by JavaScript so that the application works. I also added placeholders for future technology.
- **Login** - You can now put in a username and once you press the pretty Login button it will take you to choose what difficulty you want to play on 
- **database** - it will now actuly save your name and desplay your name when playing aswell as a working score board.
- **WebSocket** - I made a similar game chat to simon thats just a place holder for a chat that will tell you if someone reaches a increase of 10 points.
- **Application logic** - You can now play the snake game aswell as the difficulty bottons change the difficulty by changing the speed of the snake all still update the score board. with a reset button that resets the game.  

### Service deliverable 
The about page gives photos and quotes 
- **Node.js/Express HTTP service** - done!
- **Static middleware for frontend** - done!
- **Backend service endpoints** - Placeholders for login that stores the current user on the server.
- **Frontend calls service endpoints** -  I did this using the fetch function.