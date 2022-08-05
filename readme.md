![TIC_TAC_TOE!](TIC_TAC_TOE\Slide1.JPG)


1. First of all From App.js a condition will be passed(if click first time it will print "X" on the cell and assign that value to a player (it all happened trow props passed from app.js to GameBoard and then cells).
2. When player A or B click on any cell onClick(HandlePlayers) will trigered it will disabled the clicked cell and rotate the player turn (it will handle from APP.js throw prosp).
3. Cells return the value to App.js
4. App.js send that value(score) to Score(Components)
5. In Score there is a Condition(Game Conditon, if 3 rows or 3 columns or right to left diagonal or left to right diagonal) if this condition will true it will return the Winner And Looser or Draw to App.js
6. Accoding to the Score UI will Display the Winner/Looser/Draw and After that there will a tag comes in UI "Game Over" and a "Restart" Button.