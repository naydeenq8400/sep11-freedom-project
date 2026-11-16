# Entry 1
##### 11/9/26
## Content
In Sep, we are in the beginning stage of learning how to create an app based on something that interests us. For me, I have a habit of overworking myself too much at times, and not knowing what to do when I just need a break. Because of this, I've decided to make a simple game with minimal obstacles for players to play. I want to learn how to allow users to chose their avatar, collect tokens, and maybe even upgrade the game based on their skill in some way. There are many things I have to do to get here, like choosing a tool, tinkering with it, and processing it in my writeups and learning logs.

## Tool
To create this game, I've chosen the tool Kaboom. Kaboom is a tool used for making games and projects similar to mine, and to make 2D games. It’s designed to be easy to learn, letting me create games with understandable code. It helps with graphics and animations, so I can focus on the fun parts of game designwithout having to worry too much on the technical details.

## Tinkering with Kaboom
I used Kaboom.js by adding the library to my code and testing different features to make a simple game. It gives me tools for adding objects and movement. I learned that it needs to load before the game can use its functions. One way to load it in an HTML file is with a script tag:
```html
<script src="https://unpkg.com/kaboom/dist/kaboom.js"></script>
```
After loading the library, I started  to create my game. For example:
``` html
kaboom();


add([
    rect(50, 50),
    pos(100, 100),
    color(0, 0, 255)
]);
```
The first line starts Kaboom.js. The add() function creates an object in the game. The rect() function makes it a rectangle. Pos() sets where it appears on the screen, and color() makes it blue. I learned that these functions work together to create objects in a game.

I also experimented with adding a character that the player can control:
``` html
const player = add([
    rect(40, 40),
    pos(100, 100),
    area(),
    body(),
    color(255, 0, 0)
]);
```
This creates a red square that acts as the player. The area() function allows the game to detect when the player touches other objects, and body() gives the player physics, such as gravity. I learned that adding these features makes the game more interactive.

My next goal is to learn movement, and how to control the "character" using the arrow keys on my keyboard, or w a s d.

## Kaboom in the Game
Kaboom.js could help me create a simple game by allowing me to add characters, and  movement. For example, I could use it to create a player that moves around the screen, jumps over obstacles, and collects items. The game could also have different levels, backgrounds, and goals to make it more interesting. I still need to plan exactly how the game will work and which Kaboom features I want to include. My next steps are to keep experimenting with Kaboom, learn more about its functions, and decide what extra features I’ll use if I have time.

## Engineer Design Process
The Engineer Design Process is deciding how exactly I'm going to use my tool. I know I'll be using Kaboom, but I don't know what features I'll be using yet. The reason I'm making this app is to have a way to wind down when others and I need a break. 

## Skills
I learned how to tinker with my tool and learn code relevant to what I want to make. Instead of writing code that is very random, I tinkered with code to make a characrer, which was the red square. I also acnowledged that I need to tinker with code that allows me to move the character to get closer to creating the game. 

[Next](entry02.md)

[Home](../README.md)
