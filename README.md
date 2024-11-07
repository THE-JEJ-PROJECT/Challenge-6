# Challenge-6 - CCOM 4995
# Joxanniel J. Irizarry Estrella, Eduardo A. Caceres Vazquez, Jeremy J. Sanchez Diaz
# Prof. David Flores Granados

In this step, walls are created to form the boundaries of the game stage. Side walls and corner walls are configured to handle different collision events later on:

![7](https://github.com/user-attachments/assets/15270985-d50e-4078-b921-78affdcf25b0)

Floor panels are added in a 4x4 grid to form the base of the stage. Each panel is a separate game object that can be individually destroyed. These floor panels give the player a platform, which will disappear as part of the game mechanics:

![3](https://github.com/user-attachments/assets/c6856eff-feb1-4d13-8afe-813a93ea3fee)

Four enemy spawners are placed in each corner of the stage. These spawners are set to spawn enemies until a specific limit is reached. The placement in the corners allows enemies to enter the game from multiple directions:

![1](https://github.com/user-attachments/assets/ce154f8f-ee24-4952-9148-101f06bdafe8)

When the player shoots a wall, an event is triggered that changes the wall’s color to red:

![2](https://github.com/user-attachments/assets/6b8eddd2-1919-4a88-9c2b-07671760aae3)

With each wall hit, a random floor panel is deleted:

![4](https://github.com/user-attachments/assets/36c82cc2-d74a-465e-a640-e31dcf9dcf7b)

Different events are triggered based on whether the player hits a side wall or a corner wall. Hitting a side wall removes a single random floor panel, while hitting a corner wall removes all remaining floor panels at once:

![5](https://github.com/user-attachments/assets/4a23881c-c0f4-40e7-9fa3-c7269ad1165e)

A Rainspawner is added above the stage, dropping raindrops onto the play area. These raindrops interact with other elements. This mechanic adds an additional obstacle for the player.

![8](https://github.com/user-attachments/assets/14b6f5e8-a1db-4383-8086-2e620ac87ef5)

Victory screen:

![6](https://github.com/user-attachments/assets/7e0ddaa1-dfb9-44f1-b577-cc7c36e5ba10)

Losing screen:

![9](https://github.com/user-attachments/assets/549c2fe0-6cd8-4de3-b4da-5b170fd770ff)

