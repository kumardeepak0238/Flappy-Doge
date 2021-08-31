# Flappy-Doge

Introduction:
   We try to bring the popular game Flappy Bird, which is originally on Android platform, to the FPGA board. This game is a side-scroller where the player controls a bird,            attempting to fly between columns of pipes without hitting them. The objective was to direct a flying doge, named "Flappy Doge”, who moves continuously to the right, between      sets of Mario-like pipes. If the player touches the pipes, they lose. Doge briefly flaps upward each time that the player click the mouse, if the mouse is not clicked, Doge        falls because of gravity. Each pair of pipes that he navigates between earns the player a single point, with medals awarded for the score at the end of the game.

Scope:
    The goal of the project is to learn a policy to have an agent successfully play the game Flappy Bird. The player must time flaps/jumps properly to keep the bird alive as it       passes through these obstacles. Our main goal in this game was to recreate and modify it by creating several levels in the game which allows the user to choose whichever level     he desires to play.
    
Module Description
    We have used unity 2D to implement this game using C# and built-in unity tools and libraries, containing several classes and functions. We have used these 5 following classes.
    1) Bird.cs
    2) Column.cs
    3) GameControl.cs
    4) RepeatingBackground.cs
    5) ScrollingObject.cs    
