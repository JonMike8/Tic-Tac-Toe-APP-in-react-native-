# Tic-Tac-Toe-APP-in-react-native-
Project was for me to try and learn the basics of react native by coding a simple game. The app uses ios alerts to declare winners and a reset button in case there is a tie. The game also includes a hidden hard mode that can be activated by tapping on the stevens logo above the board. This turns off the ability for the players to see the icons but the game can otherwise be played normally. Hard mode also resets after the round is over. 


# Running the Code 
Installation and Basics of React Native with expo: https://docs.expo.dev/get-started/installation/

Node.js, Git, expo CLI, as well as VS code must be installed in order to run this program. 
  -expo CLI can be installed by typing "npm install --global expo-cli" into the command window. Links to others can be found at the above website.
  
In order to see the program work on a phone, the "Expo Go" app must be installed on your phone.

After all the necessary programs have been installed, the "ENGR 116 Final Project All Files must be opened in VS code. 

After this is done, navigating to the 'App.js' section and typing "expo start" into the command terminal will start the program. 

A QR code will then be generated which can then be scanned with your phone. The app can then be opened and used in the expo go app. 

Once the server is running, any changes saved to the program will update in real time on the expo go app. The server can be stopped by typing ctrl+C in the command terminal. 

The above link also has instructions on how to run/install the programs. 

## App.js
Some important aspects of the code: 

'playerMoves:' a 2D array that represents the tic tac toe board. A 1 means that player 1 has made a move and an x is currently in that spot, a -1 means that player 2 has made a move and an O is currently in that spot. The initializeGame() function resents all these numbers to 0 meaning that no player has made a move on that space yet. Bigger games could eaisily be made by expanding the array to add an extra row and column. 

currentPlayer and hardMode: state variables that control the players turn as well as weather or not an icon is shown when a tile is pressed.

checkWinner(): the checkWinner function uses loops to check rows and columns for winners, which would make implementing larger games significantly eaiser since each win condition isn't hard coded. 

'renderIcon()': uses the "import { MaterialCommunityIcons as Icon} from 'react-native-vector-icons';" feature to make including the X's and O's significantly eaiser. 

Stylesheet: the stylesheet at the bottom of the code controls the appearance and size of almost all of the components in my code. Changing the variables in the stylesheet will change the style for all components that use that syle, which simplifies changing the appearance of components. 










