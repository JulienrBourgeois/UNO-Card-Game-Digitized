# UNO-Card-Game-Digitized
This project was my first every computer science project. I completed it my sophomore year of high school for the Create Performance Task for my AP Computer Science Principles class. Making this program was a great experience and really sparked my love for programming. However, looking back at it all of these years later, I realized how much more I could have optimized and expanded upon this game.

The Create Performance Taskl recquired me to put togethr a working program that used and applied all of the core fundamentals of programming such as for-loops, while loops, if statements etc. After about 3 hours of going back and forth between ideas, I decided to create a digitized version of UNO. 

To begin my project, I knew that I had to have access to every image of every card in the UNO set. Being the inexperienced person that I once was, I went and downloaded every single card one by one instead of downloading the entire collection of cards at once. 

Once I had access to all of my images, I began to work on my User Interface. First, I made a title screen, something that every game must have. On this title screen I kept data such as the player's name, their win streak and even a game score. I knew that I wanted there to be a user going up against a randomized computer, but instead of making 2 views of each player, I just added a title at the top of the screen, saying who's turn it was. The cards that I showed to the screen were the user's cards and the cards in play, while the computer's cards were done completely in the background. 


In this game, I allowed both the user and the computer to stack cards. This was aimed to speed up the experience and make it satisfying for the user. After multiple test runs, I leveled out the game, making it pretty easy to both win and lose. After the game ended, the end screen appeared, allowing the user to return to the start screen and play again.


So that's the procedures and interface of my project. Now let's get down to the code...

Knowing that I had to deal with all of the UNO cards, I started off with making lists for their pngs, number values, colors and whether or not they had a special value. Keep in mind that this was my first ever project, which was way before I discovered the conveniences of OOP using structs and classes. After making these lists, I also made containment lists for the player and the computer decks. 

The first method I wrote was to draw the initial cards to the screen. This method removed the cards from the lists, just like removing them from decks in real life, and placed them on the screen and into the player lists for the player to see. In the background, this also occured for the computer. 
I then wrote a player turn method and a computer turn method. I used a modulus to decide who's turn it was- this was a core coding memory unlocked for me because I was freaking out when I did this I thought I had cracked the code 😂 . 

After wrapping up these methods, it was time to make a method to end the game once a player had one, which was pretty straight forward. All I did was check for a varying amount of instances within the current game. Once one was reached, I called it and sent the game to the end screen. The only challenge left was being able to play a game over from scratch.

After hours of thinking , I managed to solve this problem of not having access to previously used cards by instead of just removing them and losing them forever, putting them into a trash list and reimporting them after the game was over. 

That is it! UNO was my first every project and just typing out this description makes me want to go back and optimize this program so badly. There are so many things I could have done better with this app. Being able to to look back and pick up on things like that is why I love programming. Being able to pick up new skills and grow every day is what it's all about!



